# Material-Swapping-Application
A web-application to swap food items in real-time with other users.
 

This is the first step toward developing this web application by creating a set of static HTML5 pages for several core parts of the application flow. These pages serve as a look-and-feel design prototype for later functional / dynamic application development. 


### Standards used for Web Page Design

The fundamental standards for web page design applied here are - 

1.	Pages has valid HTML5 standard. 
2.	No site-builder or automatic site generation tools used here. 
3.	All pages render sensibly cross-browser. 
4.	All pages have full and complete separation of CSS into separate files – only the link(s) to load the CSS are present in the HTML document. No style definitions are within the page. 
5.	All pages have full and complete separation of JavaScript into separate files – only  the link(s) to load are present in the HTML document. 
6.	All resources (CSS, JavaScript, Media) are locally stored with the web application  (e.g., local copy of JavaScript libraries). 

### Application Description:

Here four HTML pages have been developed, according to the following specifications.

1.	Here the material swapping domain is for food items. It has its own unique site branding, categories, and items. 
2.	Each of the pages specified are standalone, individual HTML page. They are not something like framed or one single page with main content section visibly switching. 
3.	Each of the pages have a common design to preserve the look-and-feel of the site. Common look-and-feel elements render exactly the same, so there are seamless transitions with no jitter between pages for common elements. 
4.	Within each of the sections of the overall page layout structure, the content might style differently than the representative theme (color scheme, alignment, etc.), but the illustrated types of content are present and represented in a reasonable and understandable way. 
5.	All of the content are represented using HTML directly (no JavaScript DOM generation). 
6.	For this application, the following specific design standard requirements are considered:
  a.	Validation of HTML5 was performed by the following tool: http://html5.validator.nu/  
  b.	Cross-browser checking for Firefox and Chrome  


<b> Page Structure </b>

All pages use the following foundational layout structure:<br>
•	Full-width containers of sensible height for (1) page header area, (2) area for user specific navigation elements, (3) page footer area.<br>
•	Partial-width containers of the same height sensibly divided for (1) general site navigation and (2) main content area.<br>

<b> Page 1 – Home Page </b>

Common content elements described here (navigation, header, footer) also apply to the other pages:- <br>
•	Logo / primary branding in the header. <br>
•	Placeholder for login name.<br>
•	Breadcrumb for current place in site structure. <br>
•	Representative links for user-specific navigation (sign-in, my Meals, my swaps, cart).<br> 
  o My Meals link provide navigation to user’s meals for swap page. <br>
•	Representative links for general site navigation (home, catalog, store, about, etc.).<br>
  o	Categories link provide navigation to category page.<br>

<b>Page 2 – Categories Page</b>

This page provides the following content / functionality in addition to common content:-<br>
•	All Categories of items. <br>
•	All items per category.<br>
•	All item listings link to the same item page.<br>
•	Representative footer information (copyright, etc.) <br>

<b>Page 3 – Item Detail</b>

This page provides the following content / functionality in addition to common content:-<br>
•	Picture of item. <br>
•	Item highlights, including category and average rating. <br>
•	Item detail description. <br>
•	Button to add the item to items for swap list.<br>

<b>Page 4 – My Books</b>

This page provides the following content / functionality in addition to common content:-<br>
•	Main content container provides a table structure listing a representative item, rating average (stars > 0), and description. <br>
•	“Update” button links to the “item” page.<br>
•	“Delete” button links back to the “myItems” page.<br>

