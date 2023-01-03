# TiddlyImage
## Beautifully curate, annotate & compose visual narratives.

- Designed so that you can easily collect, upload, compose and interact with images.

- View it anywhere.  Share it online or keep it private, your choice!

- Gamified imagery consumption.  Learn from your collection, without realising!

- Checkout the [demo](https://formulator.github.io/tiddlyimage/)

## Envisaged uses
- Curation & presentation of specialist image collections.
- To develop visual recognition skills of....*whatever*....you decide.
- A tool for learning & pleasure.
- An open-source [TiddlyWiki](https://tiddlywiki.com/) showcase app.

## Goals    
- Intuitive, slick interface facilitating batch upload, grouping and annotation of resources.
- Bulk import/export/backup via JSON files :heavy_check_mark: Solved by TiddlyWiki core :heavy_check_mark:
- Create plugin to extend TiddlyWiki file importing functionality. Designed to also apply functionality to diverse file types; audio, video etc.
- Easily construct themed narratives from related resources.
- Keep responsive performance whilst managing a sizeable collection.
- Create interface tiddlers which compose narratives and compellingly present the data. For example...
    - Build tiddler to display random narratives filtered by tags at timed interval. 
    - Build game tiddlers which present images at random based on user tag selection and match user guesses to actual tags, keep score.

## Call out    
-    Do you have the skills to help build it?
-    Lets collaborate!
-    Code contributions and comments are welcome. :heart_eyes:

## Roadmap
- ~~Prepare sample images for ease of experiment~~ [See here](https://github.com/Formulator/tiddlyimage/tree/main/source_images)
- ~~Create GitHub repo, build first (limited functionality) scaffold demo and host on GitHub Pages.~~
- ~~Callout for skills & help~~
- Explore for plugins & snippets which solve aspects of desired functionality.
- Build necessary interfaces & functions
- Extend TiddlyWiki file import functionality, build a plugin:
    - Drag & drop image files & urls with...
        - Option to upload files or fetch url files to a local-but-external-to-wiki folder; prevent the wiki file from ballooning in size.
            - Name tiddlers with the filename or source url. 
        - Ability to accommodate various user scenarios; remote-url-hosted-images, local-but-external-images & (inadvisably) images-embedded-in-the-wiki.
        - Option to group related resource tiddlers by allocating a shared `uuid` to a tiddler `field`.
        - Code to assign a friendly name to the group; keep a list of {friendly-name : uuid} key:value pairs for ease of reference.
        - Capability to parse file names for date & time and subject matter.  Facilitate sorting & selection.  User provides the string format?
        - Option to export the JSON pertinent to that input episode.
        - Auto generate a visual narrative tiddler from the group.
- Create interface tiddler to easily edit & enrich tiddlers with annotations.
        - Abstract away from the user the complexity of `fields`, `file types`, `uuids` etc.
        - Drag & drop to rearrange elements of a narrative tiddler.
- Develop engaging data presentations.
    - Tiddlers to auto display rotating narratives.
    - Develop interactive gamified interface.

## Far Future
- Morph into a distributed, collaborative, multi-user, narrative-led wiki?
- Blockchain derived commercial image licensing.  Revenue to the rights holder?
- A source of labelled data for machine learning?
