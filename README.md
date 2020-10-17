# Book Review Site

Use the skills you've learned to build pages of an online book review website.

This is an individual, [stage 1](https://github.com/Ada-Developers-Academy/pedagogy/blob/master/rule-of-three.md) project.

##  Learning Goals:

-  Demonstrate an understanding of HTML syntax
-  Demonstrate an understanding of appropriate tag selection for specific content  
-  Demonstrate an ability to link local pages and remote pages
-  Demonstrate the creation of a external stylesheet  
-  Organize a site with [semantic](http://blog.teamtreehouse.com/use-html5-sectioning-elements) HTML


## Wave 1 - Creating Semantic HTML
### The Online Book Review Site

![Site Layout](images/layout.png "Site Layout")

In this exercise you will create the HTML to go along with content for 3 pages of HTML.  The pages of your site will be the pieces of an online book review site.  You will structure the content given in the content folder with semantic html tags providing meaning to the content.

Each page must have a:
-  Doctype, head, and body of an HTML    
-  A header/title Section
-  Navigation section with links for the site
-  A footer with a copyright notice and your name

__[Under no circumstances should you use inline html styles.](http://stackoverflow.com/questions/2612483/whats-so-bad-about-in-line-css)__

### Site Homepage

The homepage of your site is named `index.html`. This page will have:  
-  A header section with the title for your book review site
-  A section for navigation
-  A main content section with an unordered list of the top-5 book images (see the images folder)
  - Each image should link to their page in Amazon.com or a book review page.

### Book Review Pages
Create a book review page for the book *Eloquent Ruby* by Russ Olsen in a new file `eloquent-ruby.html`.  The content for that page is provided in the content folder by the text file `eloquent-ruby.txt`. The book review page should have the same overall structure as `index.html`, except the main content section should structure the information inside of the text file.  The page should also include the image of the book, included in the images folder.

Use `eloquent-ruby.html` as a template for the other review pages for the other books.

### Site Contact Page
Include a contact page for visitors to provide feedback to the maintainers.

This page should include:

-  A picture of the site maintainer. You can use a picture of yourself or use the goofy picture provided in the images folder
-  A statement welcoming feedback on the site via email, Twitter or Facebook
-  A list of methods to contact the site maintainer via email, Twitter and Facebook

When you are finished, review the site with another student at your table explaining the design choices you made.

What sectioning/semantic tags did you use and where?
-  div
-  body
-  section
-  article
-  nav
-  aside
-  header
-  footer


Make adjustments where it seems appropriate.  

## Wave 2 - Adding CSS

In this wave, you will add CSS styling to change the appearance of the site.

Create and use one main CSS document named `style.css`, which will hold styles that apply to every page. Then create three additional CSS documents for each HTML page's specific styles, named `index.css`, `eloquent-ruby.css`, and `contact.css`.

**Each html page should link to to two style sheets:** `style.css` first, and then CSS document that corresponds to it (`index.css`, `eloquent-ruby.css`, or `contact.css`). This will ensure that the specific styles override the generic one.

In the style sheet, practice the following:

-  Give the header and footer sections a border and background color
-  Give the main content section a background color
-  Apply a new font to the entire page (ex: Helvetica or Arial)
-  Italicize any book titles that appear in the text content of the page
-  Apply a new color to each heading element
-  Display a different color when the mouse rolls over the navigational links
-  Hide the bullet-points of the unordered lists in the site  


Page Specific Styling:
-  `index.html`
    -  Make all the images the same width
-  `eloquent-ruby.html`
    - Give each review a background color of light gray
    - Change the line-height of the review's paragraphs to 150%
-  `contact.html`
    - Center all the text of the main content (excluding content in header and footer elements)
    - Round the corners of the site maintainer image

When you are finished review your changes with your seat squad.

## Extensions
- Create another page for a book you have found useful and link it into the navigation of the site
- Import a new font from [Google Fonts](https://fonts.google.com/) to apply to heading elements
