# INFO ON FOLDER 'IIIFVIEWER'

This is the readme to initialize and use the dataset of teapots with a mirador viewer via a html script.
To run this script you need to download it and then run it. This will open a browser with a Mirador interface.
Via this interface you can immediatly find the collection and scroll through the different items.

In this folder you can find:

**Preview_Images_Teapots_Dataset**: this folder contains all thumbnail images of the dataset.
The script to do this, was written in chapter four.

**iiif_manifest_urls.txt**: this is a text file made in Notepad. 
I exported and copied all iiif manifest urls into a file to create a iiif collection manifest in a later step

**IIIFCollectionURLS.json**: this json is a structured collection of all separate iiif collection manifests, or better said,
an organized way in which the iiif manifest urls of the records are combined. This file is uploaded on Github, because it
is used by the script 'collectionthroughmiradorviewer' (see below).

**CollectionThroughMiradorViewer.html**: This script can be downloaded as a html file. When opened it shows
