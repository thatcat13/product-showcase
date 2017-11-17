# CSS Week1 Solo Project

### A product showcase page featuring CSS concepts learned this week.

#### By _Cat Janowitz_

## Description

A webpage about a tea shop that features custom blended teas.


## Specs
| Term | Description | Implementation |
| :-------------     | :------------- | :------------- |
| **border-box** | The CSS3 box-sizing property allows us to include the padding and border in an element's total width and height. | I've applied the value box-sizing: border-box universally to normalize dimensions of every container. Without it there are unwanted affects on total width and height of an element|
| **float** | The float CSS property specifies that an element should be placed along the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the web page, though still remaining a part of the flow (in contrast to absolute positioning).| I've applied float to position elements on the left or right of its parent to achieve desired locations within my layout |
|**display: block**| A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).| This is the only CSS feature I did not use in my layout; however I used display: inline-block as a technique for centering elements by placing these elements inline, but also retaining the ability to center like a block element |
| **display: inline**| An element is displayed inline, inside a current block on the same line; it takes up only as much space as it needs and does not force new lines| I've implemented display: inline for the navbar's shop/about/contact links so that each a tag is occupying the same line rather than arranged vertically |
| **centered content** | CSS has a number of properties that are used to center, including text-/content-/vertical-align, as well as transform: translate | I've used a centering technique for my main centerpiece image using the image's parent div set to text-align: center, and the child div set to display: inline-block |
| **pseudo-element** | A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s). | I've used a ::before pseudo-element to place a heart icon positionally before every h3 element. The heart icon itself is not part of the HTML code but instead added in CSS |
| **pseudo-class** | A CSS pseudo-element is a keyword added to a selector that specifies a special state of the selected element(s). | I've used a :hover pseudo-class to prompt a text box to appear above an image that is hovered over |
| **clear-fix** | The clear-fix hack is a way to combat the zero-height container problem when all of its children are floated | I've used both the diplay: table version as well as the overflow: auto; version of clearfix to prevent parent divs from collapsing when child elements were floated |
| **positional-selector** | The :nth-child() pseudo-class will modify one or more elements based on their position among a group of siblings | I've used :nth-child(an+b) to create my photo grid so that every 4th image is set to clear: both; to force a new row so that my 12 images are arranged in 3 rows of 4 |
| **selector combinator** | A combinator defines the relationship between selectors | I've used a combinator scenario to define child elements within a parent div that will be given identical properties amidst the children, instead of applying properties separately for each child|


## Setup/Installation Requirements

* access computer with internet connection and a browser
* go to github.com and search "thatcat13"
* browse thatcat13's repositories to find 'product' repository
* click on 'product' repository and copy URL link that directs to this specific repository
* access computer terminal and make sure you are at the top directory
* in terminal, after $ prompt, type in: git clone {-don't type the following, just do the following: paste URL into terminal after git clone-} then hit enter
* complete 'product' repository should be available at top directory (although desktop is suggested)
* browse folder of repository to find 'index.html'; drag file directly into browser OR in browser click file open and access 'index.html'


* or access gh-pages assigned to this project:
* thatcat13.github.io/product

## Support and Contact Details
* For any questions please reach out to any of our team members below. Here are email and GitHub account details for each:

  * [Cat Janowitz](https://github.com/thatcat13) - thatcat13@gmail.com


## Technologies Used
* CSS
* HTML


### License
* Font Awesome: License: SIL OFL 1.1
* Pixabay: CC0 1.0 Universal (CC0 1.0)


Copyright (c) 2017 **Cat Janowitz**
