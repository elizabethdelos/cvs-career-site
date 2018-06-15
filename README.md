# CVS Career Site
Custom CSS and Javascript files for landing pages on CVS/SmashFly Career Site

### custom-page_styles.css

This is the main css file to edit that overrides or adds existing styles to the SmashFly landing pages.

### Lity, OwlCarousel, & RoyalSlider

These are all third-party css and javascript plugins to add dynamic elements to certain pages like carousels and lightboxes. It is recommended to not make edits to these files but instead override styles in the custom-page_styles.css file.

### Instructions for referencing files in SmashFly html editor


If the html file you're editing is referencing muliptile css files and javascript files (like the example below), make sure to place the custom-page_styles.css file or any newly created css files after the Lity, OwlCarousel and RoyalSlider files. Also, if the page you're editing has is referencing a script, make sure you hit the <strong>Design</strong> button and then <strong>Update</strong> after editing the html, or else SmashFly will for some reason strip the rest of your code. It's always a good idea to keep a local copy of the html file/code in the case that this happens. 

Here is an example of what should be added to the top of each landing page (if the scripts are needed):

```
<link href="https://cvshealthtaadvertising.github.io/cvs-career-site/lity/lity.css" rel="stylesheet">
<script src="https://cvshealthtaadvertising.github.io/cvs-career-site/royalslider/jquery-1.8.3.min.js"></script>
<script src="https://cvshealthtaadvertising.github.io/cvs-career-site/lity/lity.js"></script>
<link rel="stylesheet" href="https://cvshealthtaadvertising.github.io/cvs-career-site/custom-page_styles.css">
<div class="searchBar gray-search">&nbsp;</div>
<section id="howtoapply">
```
If scripts are not needed, just add the custom-page_styles.css file.

### Still need help?

Contact steve.rouse@hireclix.com

