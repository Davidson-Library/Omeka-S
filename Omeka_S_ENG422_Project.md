# Omeka S Documentation for ENG 422: Creating Narratives

## Davidson Context

This page is intended to give guidance on adding items and creating pages for the group project in ENG 422: Creating Narratives at Davidson College.

## Overview of Process

* [Create Item Set for Group Items](Omeka\_S\_ENG422\_Project.md#create-item-set-for-group-items)
  * [Create Item Set](Omeka\_S\_ENG422\_Project.md#create-item-set)
* [Create an Item in Omeka S](Omeka\_S\_ENG422\_Project.md#create-an-item-in-omeka-s)
  * [Add New Item](Omeka\_S\_ENG422\_Project.md#add-new-item)
  * [Select Resource Template](Omeka\_S\_ENG422\_Project.md#select-resource-template)
  * [Add Media](Omeka\_S\_ENG422\_Project.md#add-media)
  * [Add Media Description](Omeka\_S\_ENG422\_Project.md#add-media-description)
  * [Add Item to Item Set](Omeka\_S\_ENG422\_Project.md#add-item-to-item-set)
  * [Mapping for Locations and Buildings](Omeka\_S\_ENG422\_Project.md#mapping-for-locations-and-buildings)
* [Page Setup in Omeka S](Omeka\_S\_ENG422\_Project.md#page-setup-in-omeka-s)
  * [Add New Page](Omeka\_S\_ENG422\_Project.md#add-new-page)
  * [New Page Setup](Omeka\_S\_ENG422\_Project.md#new-page-setup)
  * [Details for Adding Content to Pages](Omeka\_S\_ENG422\_Project.md#details-for-adding-content-to-pages)
* [How to Build Pages](Omeka\_S\_ENG422\_Project.md#how-to-build-pages)
  * [Type Text in HTML Blocks](Omeka\_S\_ENG422\_Project.md#type-text-in-html-blocks)
  * [Add Media Embed Block](Omeka\_S\_ENG422\_Project.md#add-media-embed-block)
  * [Timeline Block](Omeka\_S\_ENG422\_Project.md#timeline-block)
  * [Mapping Block](Omeka\_S\_ENG422\_Project.md#mapping-block)
  * [Save and View each page for consistency and accessibility](Omeka\_S\_ENG422\_Project.md#save-and-view-each-page-for-consistency-and-accessibility)

### Create Item Set for Group Items

#### Create Item Set

Create a new Item Set by clicking on **Item Sets** under the **Resources** menu on the left and **Add new item set** on the top right.

![Item Sets Menu Button](help\_files/Item\_Set\_Menu.png) _Item Sets Menu Button_

![Add New Item Set Button](help\_files/Item\_Set\_Add\_New.png)\
_Add New Item Set Button_

Make sure the Resource Template is **"Text."** Fill in the **Title and Description**, **"unlock" the set** for others to add to, and click **Save**.

![New Item Set Information](help\_files/Item\_Set\_New\_Save.png) _Fill in Item Set Info and Save_

This will allow your items to be organized by each group project for greater control and display of each group's item set.

### Create an Item in Omeka S

#### Add New Item

Under Resources on the left panel, select Items then click the Add new item button near the top-right corner.

![items menu](help\_files/Items\_Menu.png) _Resources > Items Menu_

![Add New Item](help\_files/Add\_New\_Item\_Button.png) _Add New Item_

#### Select Resource Template

From the **Resource Template** dropdown **select** the appropriate template, e.g., **Image** (scanned photo), **Text** (letter), **Physical Object** (building), **Person/Agent** (person) depending on the item. This will add Dublin Core element fields to fill in. Since most sites we're building/migrating from aren't rich in metadata, fill in as many as you can, but certainly the following three elements: **Title, Description, and Date**.

I gathered the metadata in the image below from the following sources: image file name, hover-over text and paragraph text from original encyclopedia page, and alt-text via Dev Tools, if available

![Item Metadata](help\_files/Item\_Metadata\_Laundry.png) _Fill out Item Metadata_

#### Add Media

Select the Media tab, click Upload under Add media on the right, give the media a Title (I used the same item title), choose file and select Save.

![Upload Media](help\_files/New\_Item\_Media.png) _Upload or Link Media_

#### Add Media Description

Media descriptions are used for the alt text. Follow [WebAIM](https://webaim.org/techniques/alttext/#context) for media descriptions to edit the media description to match good practices for alt text. Remove any "image of" or "graphic of" in the description. [WebAIM suggests](https://webaim.org/techniques/alttext/#context) removing these phrases from images.

![Edit Media](help\_files/Edit\_Media.png) _Edit Media_

![Type Desc](help\_files/Edit\_Media\_Desc\_Alt.png) _Type Media Desc._

There's an alt text tab but there's a [Alt Text Module](https://github.com/zerocrates/AltText) where the alt text is pulled from the Media dc:description field by default. This adds to the richness of metadata and allows increased accessibility.

**Be as descriptive as you can with the media description, but be concise.**

#### Add Item to Item Set

Your group should have an Item Set where all your items should be added. This will allow greater control over all your items and allow you to display your items on pages differently.

Click on the **Item sets (1)** tab and **search/filter (2)** for your group's item set. **Select the item Set (3)** and **click Save (4)**.

![Add Item to Item Set](help\_files/Item\_Set\_Add\_Item.png) _Add Item to Item Set_

#### Mapping for Locations and Buildings

If you're adding an item that has a location, e.g., campus building, add data to the **Mapping** tab. Follow the [instructions on my other Omeka S documentaion.](broken-reference)

### Page Setup in Omeka S

The items and media are ready to be contextualized and embedded into pages, which are used as "exhibits" or as more typical web pages.

#### Add New Page

Once the site has been created, **click on Pages** on the left panel and the **Add new page** button near the top right.

![Pages Menu](help\_files/New\_Page\_Panel.png) _Pages Menu_

![Add New Page](help\_files/New\_Page\_Button.png) _Add New Page_

#### New Page Setup

Add all info for the new page, including a **Title** and **URL Slug**. Depending on the page, **check the box next** to **Add to navigation**. Then **click Add**.

![New Page Setup](help\_files/New\_Page\_Info.png) _New Page Setup_

#### Details for Adding Content to Pages

Now that the page has been created under the site, you can start adding content. Below are two screenshots to provide an overview snapshot, including **HTML Blocks** and **Media Embed Blocks**

![Page Layout Example](help\_files/Page\_Layout.png) _Page Layout Example_

The image above :point\_up: is a snapshot of what a typical page looks like: HTML block as intro text/context, and the Media Embed block.

Below :point\_down: is what it looks like in the public view.

![Layout Public View](help\_files/Layout\_Pub\_View.png) _Layout Public View_

### How to Build Pages

Details on adding Blocks to Omeka S pages.

#### Type Text in HTML Blocks

**Add HTML block** and **type** the text in the HTML Block. If there's a heading, use **Heading 3** `<h3>` since Heading 1 `<h1>` (site title) and Heading 2 `<h2>` (page title) are already used.

![HTML Block](help\_files/Add\_HTML\_Block.png) _Add HTML Block_

#### Add Media Embed Block

**Add Media Embed block** and **change Alignment** to **center**, **left**, or **right**, depending on the look and feel.

![Media Embed Block](help\_files/Embed\_Media\_Block.png) _Embed Media Block_

**Add attachment** (quick add item on right panel) and **click Apply changes**

![Select Item for Embed Block](help\_files/Quick\_Add\_Item.png) _Add Item to Media Embed Block_

![Media Embed Apply Changes Button](help\_files/Embed\_Media\_Apply\_Changes.png) _Media Embed Apply Changes_

#### Timeline Block

If you plan on adding a Timeline to your page, don't worry about creating a new TimelineJS Google Sheet. Omeka has a plugin module for Timelines. See my [other documentation on Timelines](Timeline\_Config\_Block.md).

#### Mapping Block

If you're working with campus buildings, follow the [instructions on my other page for the Mapping Block](broken-reference) on pages.

#### Save and View each page for consistency and accessibility

**Click Save** then **View** to see what the public view looks like. You may need to adjust the alignment, but **medium** and **left/right** for the media embed seems to do best as "center" doesn't look all that great.

Run a [WAVE test](https://wave.webaim.org/) to check for missing alt text, or other accessibility errors. Make sure you have 0 errors.

![Wave Test Screenshot](help\_files/WAVE\_Test.png) _Wave Test_
