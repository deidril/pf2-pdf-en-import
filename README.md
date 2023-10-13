# Deidril's Pathfinder 2 PDF Import
This foundry vtt plugin allows to import PDFs into the current world. 

# Licenses
helyx.bundle.js code is under the MIT license
pdf.worker.min.js code is under the apache license

images in ~/datas/images are generated through Midjourney by Deidril. Their use is restricted to this module scope.


# Supported PDFs 

## Adventures
- Shadows at Sundown
- Crown of the Kobold King
- The enmity's cycle

## Core Books
- Dark Archive (adventures only) + the extra content pdf

## Free RPG Day Adventures
- A Fistful of Flowers
- Threshold of Knowledge
- Little Trouble in big Absalom
- A Few Flowers More

## Bounties
- #19 : Grim Tidings
- #20 : Burden in Bloodcove
- #21 : Against the Unliving

## Pathfinder Society Quests
- #14 : The Swordlord’s Challenge

## Pathfinder Society Season 3
- Episode 12 : Fury's Toll
- Episode 13 : Guardian's Covenant
- Episode 14 : The tomb between worlds
- Episode 15 : Cavern of the Sundered Song
- Episode 17 : Dreams of a Dustbound Isle

## Pathfinder Society Season 4
- Episode 01 : Year of Boundless Wonder
- Episode 02 : Return to the Grave
- Episode 03 : Linnorm's Legacy
- Episode 04 : To Seek the Heart of Calamity
- Episode 05 : The Arclord Who Never Was
- Episode 06 : Signal from the Electric Laboratory
- Episode 07 : A Most Wondrous Exchange
- Episode 08 : Battle Star’s Fate
- Episode 09 : Killer in the Golden Mask
- Episode 10 : Arclord’s Abode
- Episode 11 : Prisoners of the Electric Castle
- Episode 12 : Negociations for the Star Gun

# Known issues

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

