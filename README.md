# doc-importer

# Modular Document Importer

## Plan
I plan to implement a pull and push functionality, to automatically move files from one system to another, with the ability to do mid-stream processing.
First revision will be to check for documents in a dropbox folder and import them into an ImageRight instance, or file system location.


## Requirements
- Needs to have listeners, that listen to a variety of locations, with a persistent queue for reliability.
- Needs to have extensibility so that new modules can be added at any time to accomodate new storage systems.
