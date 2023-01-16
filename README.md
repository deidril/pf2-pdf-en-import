# Deidril's Pathfinder 2 PDF Import
This foundry vtt plugin allows to import PDFs into the current world. 

# Licenses
helyx.bundle.js code is under the MIT license
pdf.worker.min.js code is under the apache license

images in ~/datas/images are generated through Midjourney by Deidril, and are copyrighted (c) Deidril as far as AI generated content could be. Their use is restricted to this module scope.


# Supported PDFs 

## Adventures
- Shadows at Sundown
- Crown of the Kobold King

## Free Adventures
- A Fistfull of Flowers
- Threshold of Knowledge

## Pathfinder Society Season 3
- Episode 12 : Fury's Toll
- Episode 13 : Guardian's Covenant
- Episode 14 : The tomb between worlds
- Episode 15 : Cavern of the Sundered Song

## Pathfinder Society Season 4
- Episode 01 : Year of Boundless Wonder
- Episode 02 : Return to the Grave
- Episode 03 : Linnorm's Legacy
- Episode 04 : To Seek the Heart of Calamity
- Episode 05 : The Arclord Who Never Was

# Known issues

      + Initial import of images may freeze foundry for up to a minute
      + Sometimes the import just fail after importing images. Cancel and retry.

      + Gender of creatures using the stat block of another creature, aren't set. Issue is on the todo list"
      + Foundry ids of imported entries are not static. Entries will not be correctly overwritten if you reimport the PDF.

# Installation
1. Install the plugin from the following url ; https://github.com/deidril/pf2-pdf-en-import/releases/latest/download/module.json
2. Start your Pathfinder 2 world, then activates the module 'Deidril's Pathfinder 2 PDF Import'
3. In the settings menu, click on 'Helyx - Import PDF'
![Settings](/img/click_helyx.png)
4. In the dialog box, click on 'PDF file' and select a supported PDF
![Dialog](/img/dialog.png)
5. Click on 'Import PDF' 
6. After all pages have been memorized, the module will identify which adventure it is and start the import
7. When import is completed, click on OK
8. Enjoy Pathfinder 2 !

