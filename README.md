# Assignment Calculator
My Assignment Calculator uses Vue.js and tachyons.io (css framework) to help students enter a due date for a particular kind of assignment, and the program outputs a set of milestone dates from which students can work towards finishing their assignment.

## Motivation
Our library's website uses a content management system by Springshare's LibGuides.  Consequently, as a programmer, I'm limited to only creating/editing html/css/js (i.e. client-side code).  Fortunately, the javascript framework Vue.js allowed me to create this single page application without direct programming access to a webserver.

## Getting Started
Fork my code on http://codepen.io/avcoder/pen/PbZGZq  or clone this git repository.  However, my git repository is only one file which already combined my html/css/js code.  Also keep in mind, that since I used HTML5's date input field, certain browsers other than Chrome may not work properly.  I could not find a satisfactory datepicker solution that was keyboard navigable (and therefore does not meet WCAG  accessibility requirements).

### Built with
* [Vue.js](https://vuejs.org/) - The javascript framework used
* [tachyons.io](http://tachyons.io/) - The CSS framework used

## Deployment
I simply combined my html/css/js code found on my codepen and pasted it into an HTML5 boilerplate template within the body tags, saved it as an html file, and uploaded it into LibGuides as an asset.  The resulting id number given was then appended to our library URL.  For example, if our id number was 26667161, then the link to run the application would be  http://[Our library website]/ld.php?content_id=26667161

## Acknowledgments
* As a guide, I used the functionality/output of what I saw from Research Project Calculator https://rpc.elm4you.org/
* and Humber College's Assignment Calculator http://www.humber.ca/assignment-calculator/
