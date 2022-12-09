# 01_Code_Refactor_JGR
Module 1 Challenge

## The Challenge
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Additional requirements for long term sustainability:
- Ensure all links are functioning correctly
- Clean up the CSS selectors and properties to make it efficient
  - Consolidate CSS selectors and properties
  - Organize CSS selectors and properties to follow the semantic structure of the HTML elements
  - Include comments before each element or section of the page


## The Process
In orther to accomplish the challege, the following steps were done:
- Understand clearly the webpage purpose and content
- Research sources to understand key concepts
  - What code refactoring is
  - Semantic HTML
  - Web accesibility standards
  - How to edit Markdown files
  - Proper use of a README.mb file
- Apply above concepts in the revision and editing of the HTML and CSS files
  
\
The specific findings and modifications to the HTML file
```
Structure and descriptive comments were added

<!-- Header -->

<!-- Main content -->

<!-- Additional indirect content -->

<!-- Page footer -->


Changed title to "Business Digital Strategies"

Changed <div>  for <header> tag

Changed <div>  for <nav> tag in HTML, and .header nav CSS rules

Changed to meetingMainImage, and included into the header section.

Added some empty lines for making the HTML sections easier to identify


Added <main> tag to group the main content

Added <footer> tag at the bottom of the page

Changed content class name for mainContent both in the HTML and CSS files

The benefits <div> tag was changed to <aside> tag


Included alt properties with related description for each image

Changed the class search-engine-optimization to id search-engine-optimization

Changed the classes  benefit-lead, benefit-brand and benefit-cost to id benefit-lead, benefit-brand and benefit-cost

Removed the online-reputation-management class and rules in CSS updated to id

Removed the social-media-marketing class and rules in CSS updated to id

The </img> was removed
```
\
The specific findings and modifications to the CSS file
```
Structure and descriptive comments were added to the CSS file, and the css rules were clasified accordingly:

/* ================================= 
 Global rules and element rules
==================================== */


/* ================================= 
 Structural content style
==================================== */

/* ---------- The Header ---------- */

/* ---------- Main content ---------- */

/* ------- Additional content ------- */

/* --------- The Page Footer --------- */


The rules were ordered in terms of specificity to provide clearance in cascading rules application. Element rules first, then class selector rules and finally id selector sules.

I could not find CSS rules that could be deleted or simplified. The rules that were overwritten were mainly from user agen stylesheet and the * universal selector

Rules that were simplified into one rule:

background: url("../images/digital-marketing-meeting.jpg") center / cover;

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```


## The Output
With the research, application of concepts, and specific changes made to the files, was able to ensure an accesible, efficient, and easy to read project.  


## References
[Code refactoring](https://en.wikipedia.org/wiki/Code_refactoring)

[Semantic HTML](https://teamtreehouse.com/library/semantic-html-header-footer-and-section)

[Web accessibility standards](https://www.w3.org/standards/webdesign/accessibility)

[Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview)

[Make a README](https://www.makeareadme.com/#template)

[Interactive tutorial](https://commonmark.org/help/tutorial/)

