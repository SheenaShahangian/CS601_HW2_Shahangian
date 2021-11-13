# Read Me - MET CS 601 Sheena Shahangian

This iteration of my website contains the HTML for 4 pages all styled using CSS. The homepage is the filename "index.html". I have placed stylesheets in the css directory, and all photos within the "multimedia" directory. Please see below for a description of where I have included the requested elements (and where I have provided extras).

My objective with this version was to build out a comprehensive stylesheet which will make adding and styling new pages for the term project much more streamlined. 

The website has been tested in Google Chrome, Firefox, and Safari. It has also been tested for responsiveness.


## GitHub

To view this project on GitHub, please visit this link: https://github.com/SheenaShahangian/CS601_HW2_Shahangian

The repository is public, however should you have any trouble accessing it, please do not hesitate to reach out to me. I can be reached at sheenas@bu.edu.

## Incorporation of Feedback from Last Week

In order to incorporate feedback from last week, I have changed all external links to open in a new tab. 

## A Couple Notes Before We Begin

* In last week's version of the website, I specified image and iframe dimensions in the HTML. Now that we have learned CSS and per the textbook's instructions to not have dimensions specified in both files, I am using CSS to style the images. This works particularly well as for all images, with the exception of the logo and the height of the video iframe, I have set image sizes to be relative. For example, I have used percentages to indicate how much space an image should take up, which allows my site to be more responsive and friendly to different devices. In some cases, media queries are actually used to modify these percentages, based on screen size as well.
* This website was deigned in such a way that the brand and design is consistent, no matter the screen size, while also making sure that the design adapts based on the screen size the user is viewing the site on. I was inspired by real websites, where you have to ensure the website still looks like it belongs to the same company, even when its viewed on a different devices. For this reason, my changes based on device size center on things like modifying the navigation bar, adapting the number of columns based on device type, changing typeface size on headings and paragraphs according to device size, hiding elements when on very small screens, etc.
* For the embedded YouTube videos, I have opted for a very wide display on large screens, as these videos are shot in a cinematic way and the wide screen quality really complements that. As you move down to tablet and mobile, it takes more of a square-like dimension.

## Requested Elements

1. Per the assignment instructions, all pages are styled using the same single external stylesheet. As it is quite long, I have used comments to organize the code. Media styles for tablet screen sizes and mobile screen sizes are located at the bottom of the stylesheet.
2. Each element has at least one property value pair (and most of them have a lot more than just one, given I was aiming to create a professional design).
3. In regards to creativity, I have attempted to treat this as a professional website, with clean branding, good amounts of whitespace, consistent brand palette/color usage, and the like.
4. There are well more than the three required distinct differences in how the pages are presented based on screen size. Per the professor's recommendation, the branding and colors remain consistent, no matter the screen size. This is to ensure that the viewer doesn't get confused about which site they are on: it's best practice for the branding to stay the same. Where I have incorporated changes is in doing things like modifying the navigation bar for mobile, changing font size depending on screen size, hiding elements on smaller screens for a more streamlined view, changing text alignment on smaller screens to make reading easier, etc. I go into full detail on how media queries were used to accomplish this below:

I have used media queries to make the following substantial changes, based on screen size:

Before we begin, these are the screen sizes and names I'll be referring to in this report:

* The navigation bar adapts based on screen size. From desktop to tablet dimensions, the navigation links get smaller to acommodate the smaller screen size.  In the mobile version, the links are stacked on top of each other, rather than horizontal.
* The h1, h2, and h3 elements have all been modified based on screen size. Specifically,.....
* The paragraph font size has been modified, based on screen size as well. Specifically...
* You'll notice, headings and paragraphs of text are left aligned on mobile, versus center aligned on tablet and desktop. This is due to the fact that smaller devices are more difficult to read on, and left aligned text is better for that screen size.
* On the home page, the two article cards are represented by two columns on desktop and tablet, but are stacked one on top of the other for mobile. This is to keep the screen from being too cluttered.
* For paragraphs of text on the mobile screen size, because they are left aligned and I didn't want to have any text pushing up against the browser window's boundaries, I have used media queries to add in a unique left and right margin. The same has been applied to h1 and h2.
* Media queries have been used on the shop page to ensure the number of landscape prints in a row scales down depending on screen size.
* On mobile, I hid the publication location on the table in the biography page to avoid clutter. This was non-essential information that was a good fit for hiding.

### Incorporation of Other Additional Elements Presented During Class - How I Went Above and Beyond

I've attempted to add some new features beyond the standard requirements listed in the rubric. These include: 

* I have used Google Fonts rather than system fonts to give my website an elevated and customized look. However, I have also specified fallback fonts as well, in case my website visitors' devices cannot render the Google Fonts.

* I have used a variety of selectors, including class selectors, element/type selectors, id selectors, and descedant selectors. As much as possible, I have aimed to focus on element/type and class selectors to ensure greater resuability on the code.

* I have included more than one property:value pair on nearly every selector I've used to make sure I fine-tuned my design.

* I have organized my css document with thorough comments to ensure the design choices are clear and easy to find (which will make this website easier to modify in the future). I have also used comments to break up my stylesheet into sections that make it more digestible. This will make it easier to modify the css in the future.

* Per the professor's recommendations, I have placed all media queries at the bottom of the stylesheet for easy identification.

* I have incorporated well more than the three required distinct differences based on screen size, as I wanted each device size to really be comprehensive and beautiful on its own. Specifically, I have used media queries on 15 different elements on screens with a max width of 640 pixels, and I have used media queries on 7 different elements on screens with a min width of 641 pixels and a max width of 1024 pixels. Generally speaking, the 641 - 1024 pixel screens have more real estate and thus incorporate a lot of the same structure and design as larger screens, which is why they have less elements leveraging media queries. On the other end of the spectrum, smaller screen sizes require much resizing and redesigning.

* I have chosen and used a color palette that I have based my styles on to ensure consistency in branding.

* I have intentionally limited my font families to two distinct primary fonts (both Google Fonts) in order to keep with design best practices of not having too many fonts on a single page.

* Per the professor's encouragement to look into newer tools like Flexbox, I have incorporated Flexbox for some of my two column layouts (as I read online that floats are less and less common these days and should start to be phased out, although I did use floats too to get some practice in).

  