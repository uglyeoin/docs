---
title: RokSprocket: Mosaic Layout Mode
description: Your Guide to the Mosaic RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

### Mosaic
![][mosaic]
Mosaic displays content dynamically in blocks, that can be rearranged via tags or ordering commands.

![][mosaic_1]

:   1. **Title** This is the title of your module. [19%, 13%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [19%, 59%, se]
    3. **Status** Sets the publishing status for the module. [26%, 64%, nw]
    4. **Access** Sets the access level for the module. [19%, 85%, sw]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [53%, 50%, sw]
    6. **Layout Type** This is where you will select the Layout Mode you wish to use for your RokSprocket Module. [52%, 82%, sw]
    7. **Content Filter Rules** Sets the content filter rules for the module. [62%, 79%, sw]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

5. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the module. The article title will be used if this is left at *Default*.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the feature. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the feature, as well.
    * **Tags** - Comma separated list of tags for filtering on the frontend.

6. The **Content Provider and Layout Type** section gives you the ability to set the Layout Mode you wish to use for the module. This is often the first setting you want to pay attention to when creating a new RokSprocket module. The Content Provider can vary, but in most Joomla instances, this will default to Joomla.

7. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the items. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Mosaic Layout Options** and **Mosaic Article Defaults** sections below.

![][mosaic_2]

:   1. **Theme** This sets the theme for displaying features in the module. [12%, 41%, se]
    2. **Display Limit** The amount of articles to show when rendering. [15%, 74%, sw]
    3. **Columns** Sets the number of columns articles are displayed in. [19%, 41%, se]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [23%, 74%, sw]
    5. **Only Show Tags** Tags listed in this field will be the only ones that appear as filter options, and on items. [28%, 41%, se]
    6. **Strip HTML Tags** This option removes HTML tags from the description of an article. [32%, 51%, sw]
    7. **Blocks Per View** This sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear. [37%, 41%, se]
    8. **Article Details** This option gives you control over whether details like the author's name or publishing date appear in the module. [41%, 70%, sw]
    9. **Block Animation** Sets the combination of block animations used when rendering blocks in the mosaic. [46%, 41%, se]
    10. **Ordering** Ordering options available to users on the frontend. [53%, 80%, sw]
    11. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some templates. [62%, 41%, se]
    12. **Default Title** You can set a default title for all articles from this field. If this selection is set at **Default Article Title**, then the articles' given titles are used. [73%, 42%, se]
    13. **Default Article Text** This field allows you to set default article text for all features in the module. If this is not changed from its default, then the article's introductory text is used. [78%, 68%, sw]
    14. **Default Article Image** Determines which image field the module will default to when locating an image for the feature. [82%, 42%, se]
    15. **Default Link** Determines which link field the module will default to when locating a link for the feature. [87%, 68%, sw]

1. **Theme** sets the theme for displaying features in the module.

2. **Display Limit** sets the amount of articles to show when rendering.

3. **Columns** gives you the option to set the number of columns articles are displayed in.

4. The **Preview Length** option sets the amount of words you wish to limit the preview to within the module's article display.

5. Tags listed in the **Only Show Tags** field will be the only ones that appear as filter options, and on items.

6. **Strip HTML Tags** removes or preserves HTML tags in the description of an article.

7. **Blocks Per View** sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear.

8. **Article Details** gives you control over whether details like the author's name or publishing date appear in the module.

9. **Block Animation** sets the combination of block animations used when rendering blocks in the mosaic. There needs to be at least one option in this field. These animations are rendered through CSS3 and may not be available on all browsers. 

10. **Ordering** sets ordering options available to users on the frontend. There needs to be at least one option in this field. If only one option is present, the switcher will not appear on the frontend.

11. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some templates.

12. **Default Title** sets a default title for all articles in the module. If this selection is set at **Default Article Title**, then the articles' given titles are used.

13. **Default Article Text** allows you to set default article text for all features in the module. If this is not changed from its default, then the article's introductory text is used.

14. **Default Article Image** determines which image field the module will default to when locating an image for the feature.

15. **Default Link** determines which link field the module will default to when locating a link for the item.

[mosaic]: assets/mosaic.jpeg
[mosaic_link]: mosaic_mode.md
[mosaic_1]: assets/mosaic_1.jpeg
[mosaic_2]: assets/mosaic_2.jpeg
