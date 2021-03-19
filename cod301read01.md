# SMACSS and Responsive Web Design  

## Responsive Web Design 

- **Responsive Web Design (RWD)**: building websites suitable for all users and work on every device and every screen size, no matter how large or small, mobile or desktop by focusing on providing an intuitive and gratifying experience for everyone.

![](https://designmodo.com/wp-content/uploads/2015/09/designmodo-responsive.jpg)

- Responsive design websites continually and fluidly change based on different factors, such as viewport width, they react quickly and positively to any change.

- **Adaptive websites** are built to a group of preset factors, they are easily modified for a new purpose or situation, such as change. 

- The perfect functional websites are responsive and adaptive. 

- **Mobile website**: is a separate website commonly on a new domain solely for mobile users, they can be extremely light but they do come with the dependencies of a new code base and browser sniffing, all of which can become an obstacle for both developers and users.

- The best solution in web designing is building a responsive, adaptive and mobile website. This solution includes a design that dynamically adapts to different browser and device view ports, changing layout and content along the way. 

- The main components of responsive websites are :
  
   1.  **Flexible layouts**: is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly ***percentages*** or ***`em`*** units. These relative lengths are then used to declare common grid property values such as`width`, `margin`, or `padding`. The fixed measurement units restrain the adaptation of website layout when the viewport height and width change from device to device.

   ![](https://www.javascriptwillrule.com/static/f1fb309f4ef99330c0dacd94898cf4db/8cdda/css-units-list-1.png)


    An easy formula to help identify the proportions of a flexible layout using relative values is the formula of ***Ethan Marcotte***:
    
    ` Target width of an element  ÷ Width of it’s parent element (context) = The relative width of the target element`

   2.  **Media queries**: is an extension to media types commonly found when targeting and including styles. They provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Using media queries are a popular technique for delivering a tailored style sheet to desktops, laptops, tablets, and mobile phones.
       
       - Initializing Media Queries:
          
          +  Linking to a separate style sheet from within the HTML document. In HTML page : `<link rel="stylesheet" media="mediatype and|not|only (expressions)" href="print.css">`
          
          +  Using the `@media` rule inside of an existing style sheet, importing a new style sheet using the `@import` rule. *Recommended way*.
             
             *Syntax* : `@media not|only mediatype and (expressions) { CSS-Code; }`
             
![](https://1.bp.blogspot.com/-AIZHWSqKoGI/XIGASkN8CJI/AAAAAAAAC9Q/lSBC5zoD0A4miVSe0FM1Z9V6V2ucQwpCQCLcBGAs/s1600/%25D8%25AF%25D9%2588%25D8%25B1%25D8%25A9%2B%25D8%25A3%25D8%25B3%25D8%25A7%25D8%25B3%25D9%258A%25D8%25A7%25D8%25AA%2B%25D9%2584%25D8%25BA%25D8%25A9%2Bcss%2B%25D9%2584%25D9%2584%25D9%2585%25D8%25A8%25D8%25AA%25D8%25AF%25D8%25A6%25D9%258A%25D9%2586%2B%2528%2B%25D8%25A7%25D9%2584%25D8%25AF%25D8%25B1%25D8%25B3%2B18%2B%2BMedia%2BTypes%2B%2529.png)

   *Logical operators in media queries*:
             
   + **not**: The not keyword inverts the meaning of an entire media query.

   + **only**: The only keyword prevents older browsers that do not support media queries with media features from applying the specified styles. It has no effect on modern browsers.

   + **and**: The and keyword combines a media feature with a media type or other media features.

   *Media Features (expression)*:

![](https://image.slidesharecdn.com/mediaqueries-110718145319-phpapp01/95/css3-media-queries-mobile-elixir-or-css-snake-oil-18-728.jpg?cb=1311282768)

   **Mobile first** is an approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

   **Viewport** is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.
             
   -  The viewport meta tag with either the height or width values will define the height or width of the viewport respectively.`<meta name="viewport" content="width=device-width, initial-scale=1.0, target-densitydpi=device-dpi">`
             
   - `@viewport` provides another way to determine and control viewport in CSS sheet instead of meta tag in HTML sheet.
   
   
   3.  **Flexible media**: changing the size of images, videos, and other media types in according to change in viewport size by making them scalable using the `max-width` property with a value of 100%.

      - `iframe` and embedded media are not responsive to `max-width` property , therefore; they absolutely positioned within a parent element. The parent element needs to have a width of 100% so that it may scale based on the width of the viewport. The parent element also needs to have a height of 0 to trigger the hasLayout mechanism within Internet Explorer.Padding is then given to the bottom of the parent element, the value of which is set in the same aspect ratio of the video.



## Floats in CSS

- **Float** is a CSS positioning property.

- Values of the float property are **Left**, **Right**, **None** (the default) ensures the element will not float and **Inherit** which will assume the float value from that elements parent element.

- `float` property is used in wrapping text around images and creating entire web layouts.

- `clear` property allows elements to specify where they should align in comparison to the floated elements. For example: “Clear: left” make each element floating left to be aligned behind the first element that is floated left.

- `clear` values are : `clear: none|left|right|both|initial|inherit;`.

- Other techniques for clearing floats are: 

   + Using empty div. `<div style="clear: both;"></div>`.

   + Using the overflow CSS property on a parent element by setting it to `auto` or `hidden`.

   + Using CSS pseudo selector `(:after)`.


![](https://sathyalog.files.wordpress.com/2014/10/10-10-2014-11-15-12.png?w=750)


## Grid Layout in CSS

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns and without using floats and positioning, this layout consists of a parent element, with one or more child elements.

- The parent element with the `display` property set to `grid` or `inline-grid` (the grid container), and the direct child element(s) of the grid container automatically becomes grid items.


![](https://miro.medium.com/max/1042/1*8-5_iM-cx-TO_CGI5mWAxQ.png)


## SMACSS

- **SMACSS** stands for Scalable and Modular Architecture for CSS and it has 2 core goals.

   1.  Increase the semantic value of a section of html and content.
   
   2.  Decrease the expectation of a specific html structure.


- SMACSS is an approach to writing css and html with more emphasis placed on using classes. It includes 5 general categories of css rules:

   1. Base — These are your defaults (html, body, h1, ul, etc).

   2. Layout — These divide the page into major sections.

   3. Module — These are the reusable modular components of a design.

   4. State — These describe how things look when in a particular state (hidden or expanded, active/inactive).

   5. Theme — These define things like a color scheme or typographic treatment across a site. 

![](https://habrastorage.org/files/4dc/24a/8dc/4dc24a8dc3fb4e758adf89af4f73f66c.png)

