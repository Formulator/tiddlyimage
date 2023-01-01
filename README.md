# TiddlyImage
## Beautifully curate, annotate & compose visual narratives.

- Designed so that you can easily collect, upload, compose and interact.

- Gamified imagery consumption.  Learn from your collection, without realising!

- Store it anywhere.  Share it online or keep it private, your choice!

## Envisaged uses:
- Curation & presentation of specialist image collections.
- Build visual recognition of....*whatever*....you decide.
- A learning tool. See the image, learn the words! Rinse & repeat!
- An open-source [TiddlyWiki](https://tiddlywiki.com/) demo app.

Goals    
- Intuitive, slick interface facilitating batch upload of images and creation of `_canonical_uri` linked tiddlers, thereby preventing wiki bloat.
- Read descriptive data text files (matched to source image file name) to programatically add tags and fill tiddler fields etc.
- Option to programatically group image tiddlers using a `uuid` stored in a `field` representing the batch.  This will facilitate easy narrative building.
- Bulk upload and processing of images and their descriptive .txt into tiddlers.
- Parse date and time from filenames or tiddlers to facilitate sorting and selection etc.
- Keep responsive performance whilst managing several hundred / a few thousand images with the scheme.
- Create interface tiddlers which compose narratives and/or slice the data in interesting directions. e.g.
- Build tiddler to display a random narrative.  
- Build game tiddlers which present images at random based on user tag selection and match user guesses to actual tags, keep score.

Questions
*    What is the best suited TiddlyWiki architecture; single file or Node.js
*    Is the file import plugin, [ServerImages](https://github.com/OokTech/TW5-ServerImages), best-in-class?  Could it be extended to satisfy other desired functionality?
*    Are the goals technically attainable?
*    Do you have the skills to help build it?  Please join me on GitHub.


Roadmap
-   ~~Find a mechanism to programatically create `_canonical_uri` tiddlers~~ Imported: [ServerImages](https://github.com/OokTech/TW5-ServerImages)
- ~~Prepare sample images~~ [images](https://github.com/Formulator/tiddlyimage/tree/main/source_images) ~~
- ~~Create GitHub repo, build first (limited functionality) demo and host on GitHub Pages.~~
- ~~Callout for skills & help~~
- Build core functionality, upload, uuids, parsing and tiddler data enrichment.
- Create mechanisms for users to filter, select and display the collection.
- Tiddlers to auto display random/chosen images/narratives
- Develop interactive gamified interface