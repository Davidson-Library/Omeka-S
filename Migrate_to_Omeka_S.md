# Migrate a Webpage from HTML/WordPress to Omeka S

## Davidson Context

This page is intended to give guidance on migrating static HTML sites or WordPress sites to an Omeka S site. Many of the examples are from the ASCC Encyclopedia Migration Project

## Overview of process

- [Migrate a Webpage from HTML/WordPress to Omeka S](#migrate-a-webpage-from-htmlwordpress-to-omeka-s)
  - [Davidson Context](#davidson-context)
  - [Overview of process](#overview-of-process)
    - [Create Site in Omeka S.](#create-site-in-omeka-s)
    - [Download images from HTML site and back up in Google Drive folder.](#download-images-from-html-site-and-back-up-in-google-drive-folder)
    - [Create an item in Omeka S for each image with media.](#create-an-item-in-omeka-s-for-each-image-with-media)
    - [Create pages in Omeka mirroring the pages or headings in HTML site depending on the structure.](#create-pages-in-omeka-mirroring-the-pages-or-headings-in-html-site-depending-on-the-structure)
    - [Add blocks to each Omeka S page, e.g., HTML and Media Embed to mirror the structure of original HTML site.](#add-blocks-to-each-omeka-s-page-eg-html-and-media-embed-to-mirror-the-structure-of-original-html-site)
    - [Save and View each page for consistency and accessibility.](#save-and-view-each-page-for-consistency-and-accessibility)



### Create Site in Omeka S.

[COMING SOON]

### Download images from HTML site and back up in Google Drive folder.
### Create an item in Omeka S for each image with media.

1. Under Resources on the left panel, select Items then click the Add new item button near the top-right corner.
![items menu](./help_files/Items_Menu.png "Item Menu")
![Add New Item](./help_files/Add_New_Item_Button.png "Add New Item")
2. From the **Resource Template** dropdown **select** the appropriate template, e.g., **Image** (scanned photo), **Text** (letter), **Physical Object** (building), **Person/Agent** (person) depending on the item. This will add Dublin Core element fields to fill in. Since most sites we're building/migrating from aren't rich in metadata, fill in as many as you can, but certainly the following three elements: **Title, Description, and Date**. If available, put the Record Group #, e.g., 9-0431, 29-0056, in the Identifier field.
If the item is a person, search [Library of Congress Name Authority File (LCNAF)](https://id.loc.gov/authorities/names.html), [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page), and [VIAF](https://viaf.org/) to add a URI to the item record in Omeka S.
If they are in any of the locations above (LCNAF, Wikidata, or VIAF), add each URI as an identifier in the Omeka S item record.

_I gathered the metadata in the image below from the following sources: image file name, hover-over text and paragraph text from original encyclopedia page, and alt-text via Dev Tools, if available_

![Item Metadata](./help_files/Item_Metadata_Laundry.png "Item Metadata")


### Create pages in Omeka mirroring the pages or headings in HTML site depending on the structure.
### Add blocks to each Omeka S page, e.g., HTML and Media Embed to mirror the structure of original HTML site.
### Save and View each page for consistency and accessibility.