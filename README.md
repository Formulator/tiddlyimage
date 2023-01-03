# TiddlyImage
## Beautifully compose & curate visual narratives

- Designed so that you can easily collate, compose and display digital resources

- View it anywhere.  Share it online or keep it private, your choice!

- Checkout the [vision](https://formulator.github.io/tiddlyimage/)

## Envisaged uses
- Curation & presentation of image, audio & video collections
- Storyboarding your creative vision
- A tool for creative learning & expression
- An open-source [TiddlyWiki](https://tiddlywiki.com/) showcase app

## Goals    
- Intuitive, slick interface facilitating batch upload, grouping and annotation of resources
- Bulk import/export/backup via JSON files :heavy_check_mark: Solved by TiddlyWiki core :heavy_check_mark:
- Create plugin to extend TiddlyWiki file importing functionality
- Designed to accommodate diverse file types; image, audio, video and more
- Easily construct themed narratives from related resources
- Keep responsive performance whilst managing a sizeable collection
- Auto-composing narratives and compellingly present the data
    - Display random or filtered narratives at intervals.
    - Visual guessing game

## Call out    
-    Do you have the skills to help build it?
-    Lets collaborate!
-    Code contributions and comments are welcome :heart_eyes:

## Roadmap
- ~~Prepare sample images for ease of experiment~~ [See here](https://github.com/Formulator/tiddlyimage/tree/main/source_images)
- ~~Create GitHub repo~~
- ~~Build first (limited functionality) demo and host on GitHub Pages~~
- ~~Callout for skills & help~~
- Explore for plugins & snippets which solve aspects of desired functionality
- Build necessary interfaces & functions
- Build a plugin to extend TiddlyWiki file import functionality :
    - Drag & drop image files & urls with...
        - Option to store files or fetch url resources to a local-but-external folder
            - Important to prevent the wiki file from ballooning
        - Keep reference to sources
            - Tiddlers to be named with the filename or source url
        - Ability to accommodate various user scenarios
            - remote-url-hosted-images
            - local-but-external-images
            - images-embedded-in-the-wiki (Possible but inadvisable)
        - Option to group related resource tiddlers
            - Allocate a group `uuid` to a tiddler `field`
            - Permit multi-group membership
            - Add/remove a tiddler to/from an existing group
            - Code to assign a friendly name to the group
                - Keep a list of {friendly-name : uuid} `key:value` pairs for reference
        - Capability to parse file names for date & time and subject matter
            - Facilitates sorting & selection
        - Option to generate & export the JSON pertinent
            -  The current input episode
            -  A selected narrative
        - Interface to auto-generate visual narrative tiddlers from a membership group
            - This is the `uuid` superpower
- Permit easy editing of narrative tiddler
     - Backpropogate changes to source tiddler
     - Abstract away from the user the complexity of `fields`, `uuids` etc.
     - Drag & drop to rearrange elements of a narrative tiddler
- Develop engaging data presentations
    - Tiddlers to auto display rotating narratives
    - Develop interactive guessing game
        -  Present images
        -  Match user guesses to actual tags
        -  Keep score, how close were you?

## And then...
- Presentation mode
    - Iterate through elements of a narrative
    - Control the flow, dwell time, autoplay etc.
- Screencasting
- Morph into a distributed, collaborative, sharing, multi-user, narrative-led wiki?
- Blockchain derived content licensing. Revenue to the creator?
- A source of labelled data for machine learning?