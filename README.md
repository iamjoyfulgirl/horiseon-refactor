# Accessibility and SEO optimization task
**Assignment: Refactor the HTML for the Horiseon site to improve accessibility standards and optimize it for search engines.**

## Acceptance Criteria
```
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
```

The Horiseon website has been refactored to meet accessibility standards and is optimized for search engines.

### HTML Changes:
* Added a descriptive page title
* Changed all div to section elements
* Added comments to make code more readable
* Added alt text to each image on the site for accessibility
* Added an aside to benefits class to allow for consolidation of CSS styles
* Changed footer h2 to h4 to keep h tags consecutive
* Updated copyright year from 2019 to 2022

### CSS Changes:
* Changed classes with div to section to match HTML
* Added comments to make code more readable
* Added aside class=benefits to consolidate styling for the three benefits shown
* Consolidated all h3 elements to use one set of styling properties
* Consolidated element properties in the Content section
* Consolidated images max height for all images in .content class
* Consolidated all h2 elements to use one set of styling properties


![Partial screenshot of completed website:](/horiseon-refactor.png)

* The deployed application can be viewed at: https://iamjoyfulgirl.github.io/horiseon-refactor/
* The GitHub repository can be found at: https://github.com/iamjoyfulgirl/horiseon-refactor
