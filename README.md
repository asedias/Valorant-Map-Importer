# VALORANT Map Exporter Script 

Fork with additions from: https://github.com/luvyana/val-scripts

Some useful scripts & tools to be used with creating VALORANT content

## Extracting maps

Extracted Maps : https://mega.nz/folder/BqglCTzC#qJqUZ6VYysNMCnjvni69AQ

### Extract them yourself :

Blender 2.93 or higher is needed.

    0 - Download this repo, and extract to somewhere that has lots of space.
    1 - Open "settings.ini" file using a text editor
    2 - Set the "PATH" to where .pak files are located
    4 - Open Blender, go to "Scripting" Panel
    5 - Export *.umap data with FModel in export/Data/*map_name* (Ex.: export/Data/Haven)
    6 - Drag & Drop the "importMap.py" file in to script panel
    7 - Click "Window > Toggle System Console" so you can see the process
    8 - Set "MAP" to the map you exported in the script
    9 - Hit Run!

