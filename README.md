# Wiki
This is the wiki for the 3D Printers Discord. 

## Contribution
Contribution is currently restricted to specific members of the Discord server only due to the manual nature of adding collaborators. Once the wiki is established it is intended that any regular member of the Discord server will be able to contribute.

Please note that bots only update their internal version of this wiki once every 6 hours and so changes here may take some time to trickle down to the server. 

## Making New Pages
When a new page is created: 
* Add it to the Homepage Index [here](https://github.com/3DprinterDiscord/wiki/wiki#index-a-z) in it's alphabetically correct place (see the right hand sidebar) and to any other relevant sections on the [Homepage](https://github.com/3DprinterDiscord/wiki/wiki).

Use ` [page title](url) `

Example of markdown for this: `[Extruders](https://github.com/3DprinterDiscord/wiki/wiki/Extruders)`

* Update the total number of articles on the bottom of the Homepage [here](https://github.com/3DprinterDiscord/wiki/wiki#current-number-of-pages-on-wiki) (see the top of the right hand sidebar).

## Page Style
To make sure the wiki is as accessible as possible (by both humans and bots!) please ensure that pages follow a standard formatting. 

[GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

### Linking
Associated pages should be linked inline with body text only in the first instance of their use. 

### Capitalisation
Correct and consistent capitalisation is important. Page titles should be capitalised but full caps should not be used. The same applies to headings and body text.

Acceptable:
> Extruders

Not Acceptable:
> EXTRUDERS, extruders

### Bold Text
Bold text can be created by using a double asterix "\*\*" on either side of the text you wish to make bold. Bold text should be used to **emphasise** specific words and phrases and **not** used on entire paragraphs.

Example:
> Make sure to **enable** thermal runaway protection.

Created by:
> Make sure to \*\*enable\*\* thermal runaway protection. 

### Intro 
The first line of any page should be an introduction paragraph that describes the content on the page. Note that this will be used by the server bot as a descriptive text in bot commands. This should **not** be prefixed with a header such as "Introduction" and must begin on line 1. 

### Notes on Pages
You may come across notices at the top of certain pages, such as:

This page is incomplete. You can help by expanding upon it. For more details on how to contribute to this wiki see the [how to contribute](https://github.com/3DprinterDiscord/wiki/wiki/How-to-contribute-to-this-wiki) page.|
:--:|

> `This page is incomplete. You can help by expanding upon it. For more details on how to contribute to this wiki see the [how to contribute](https://github.com/3DprinterDiscord/wiki/wiki/How-to-contribute-to-this-wiki) page.|`

> `:--:|`

> Ensure that the `:--|` is on the next line to the appended `|`.

or 

This page may be outdated. You can help by expanding upon it or editing it to reflect current changes. For more details on how to contribute to this wiki see the [how to contribute](https://github.com/3DprinterDiscord/wiki/wiki/How-to-contribute-to-this-wiki) page.|
:--:|

as well as text boxes noting other things, for example this note from the [Types of Printing](https://github.com/3DprinterDiscord/wiki/wiki/Types-of-Printing/) page.

Note: this page ties in with the [materials](https://github.com/3DprinterDiscord/wiki/wiki/Materials) page and the [motion systems](https://github.com/3DprinterDiscord/wiki/wiki/Motion-Systems) page.|
:--:|

These use the standard markdown table formatting, as shown above. They should be put directly **beneath** the introduction paragraph.

Notices like these are added to denote exactly what they say, a 'may be outdated notice' should be used when a page contains potentially outdated information which does not reflect the current situation or views, whilst a 'this page is incomplete' notice should be added to stubs or shorter pages which need clarification or which need expanding upon. 

If you come a page with a note like this you may want to consider editing or additing to it. If you come across a page with a notice that you believe no longer needs it, it can be removed. Similarly, if you feel that your edits of a page mean that the notice is no longer required it can also be removed.



### Additional Detail Page
When further detail is required for a topic please: 

* Create a new page if one does not already exist and use the following format to link to it:
* If a page exists, add a link to that page in the following format:

`* For additional details see: 
[Page Title](url)*` 

> (`* *` makes the text *italic*)

* Follow the instructions above for Making New Pages to update the homepage


### Tables of Contents
When creating a table of contents use the following format:

*****
 ****Table of Contents****

[Materials](https://github.com/3DprinterDiscord/wiki/wiki/Materials) 
* [Filaments](https://github.com/3DprinterDiscord/wiki/wiki/Materials#filaments)  
  * [FFF/FDM](https://github.com/3DprinterDiscord/wiki/wiki/Materials#ffffdm)
    * [Filament Colours](https://github.com/3DprinterDiscord/wiki/wiki/Materials#filament-colours)
* [SLS](https://github.com/3DprinterDiscord/wiki/wiki/Materials#sls) 
* [Other Exotic Materials](https://github.com/3DprinterDiscord/wiki/wiki/Materials#other-exotic-materials)
* [Safety](https://github.com/3DprinterDiscord/wiki/wiki/Materials#safety) 
  * [Filament Safety](https://github.com/3DprinterDiscord/wiki/wiki/Materials#filament-safety) 
* [Filament Care](https://github.com/3DprinterDiscord/wiki/wiki/Materials#filament-care) 
*****

***** should be used on the lines before and after the table to display it as a separate section.

The top line of the table should contain a link to the page itself.

Each header should be added to the table and indented using bullet points (either * or - ) according to the heading type.

The [materials](https://github.com/3DprinterDiscord/wiki/wiki/Materials) page contents table can be used as an example to refer to.

### Things to Avoid
There are a couple of things which can make the wiki look confusing or inconsistent:

#### Additional Titles
Github will automatically title pages for you so there is no need to include a top level title at the top of the page. This will end up creating a double title and will confuse the bot! 

#### Not Previewing Pages
Github lets you preview you pages before you comit them to the wiki. Please use this feature to ensure the formatting looks as intended. 

#### Ignoring this style guide
If you have read this far I'm assuming that you will work within the guidance of this style guide! Please help maintain the wiki by flagging pages that are not correct within the issue tracker.
