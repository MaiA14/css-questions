# CSS questions

**1. What is CSS?**\
     CSS stands for Cascading Style Sheet. It is a popular styling language which is used with HTML to design websites.
     cascading means the process of combining several style sheets and resolving conflicts between them.\
**2.  How can you integrate CSS on a web page?**\
     - Inline method - It is used to insert style sheets in HTML document
     - Embedded/Internal method - It is used to add a unique style to a single document
     - Linked/Imported/External method - It is used when you want to make changes on multiple pages.\
 **3.  What are the CSS frameworks??**\
      CSS frameworks are the preplanned libraries which make easy and more standard compliant web page styling. The frequently used CSS frameworks are: -
      - Bootstrap\
      - Foundation\
      - Semantic UI\
      - Gumby\
      - Ulkit\
 **4.  Why background and color are the separate properties if they should always be set together?**\
      - It enhances the legibility of style sheets. The background property is a complex property in CSS, and if it is combined with color, the complexity will further
        increase.
      - Color is an inherited property while the background is not. So this can make confusion further.\
 **5. What is Embedded Style Sheet?**\
      An Embedded style sheet is a CSS style specification method used with HTML. You can embed the entire stylesheet in an HTML document by using the STYLE element.
 **6. What are the advantages of Embedded Style Sheets?**\
      - You can create classes for use on multiple tag types in the document.\
      - You can use selector and grouping methods to apply styles in complex situations.\
      - No extra download is required to import the information.\
  **7. It is a string that identifies the elements to which a particular declaration apply. It is also referred as a link between the HTML document and the style sheet. It is
       equivalent of HTML elements. There are several different types of selectors in CSS?**\
      - CSS Element Selector\
      - CSS Id Selector\
      - CSS Class Selector\
      - CSS Universal Selector\
      - CSS Group Selector\
 **8.  What is the use of CSS Opacity?**\
       The CSS opacity property is used to specify the transparency of an element.\
 **9. Explain universal selector( * ).**\
      The universal selector matches the name of any of the element type instead of selecting elements of a specific type.\
 **10. Name the property for controlling the image repetition of the background.**\
       The background-repeat property repeats the background image horizontally and vertically. Some images are repeated only horizontally or vertically.\
 **11. Name the property for controlling the image position in the background.**\
       The background-position property is used to define the initial position of the background image. By default, the background image is placed on the top-left of the
       webpage. You can set the following positions: center, top, bottom, left, right.\
 **12. Name the property for controlling the image scroll in the background.**\
       The background-attachment property is used to specify if the background image is fixed or scroll with the rest of the page in the browser window.\
 **13. What is the difference between class selectors and id selectors?**\
       An overall block is given to class selector while id selectors take only a single element differing from other elements.\
 **14) What are the advantages of External Style Sheets?**\
       - You can create classes for reusing it in many documents.\
       - By using it, you can control the styles of multiple documents from one file.\
       - In complex situations, you can use selectors and grouping methods to apply styles.\
 **15. What is RWD?**\
       RWD stands for Responsive Web Design. \
 **16. What are the benefits of CSS sprites?**\
       If a web page has a large number of images that take a longer time to load because each image separately sends out an HTTP request. The concept of CSS sprites is used
       to reduce the loading time for a web page because it combines the various small images into one image. It reduces the number of HTTP requests and hence the loading
       time.\
**17. What is physical tag and logical tag in HTML?**\
      Logical tags are used only to give information about the text, written in the HTML pages. For example: <strong> </strong>.
      uses physical style tags to change the appearance of text. If you want your text to appear in a particular style such as bold or italics etc., you must use physical
      style tags.\
**18. What is the CSS Box model and what are its elements?**\
      The CSS box model is used to define the design and layout of elements of CSS.\
      The elements are:\
       - Margin - It removes the area around the border. It is transparent.\
       - Border - It represents the area around the padding\
       - Padding - It removes the area around the content. It is transparent.
       - Content - It represents the content like text, images, etc.
**19. What is the float property of CSS?**\
      The CSS float property is used to move the image to the right or left along with the texts to be wrapped around it. It doesn't change the property of the elements
      used before it.\
**20. What is the purpose of the z-index and how is it used?**\
      The z-index helps to specify the stack order of positioned elements that may overlap one another. The z-index default value is zero and can take on either a
      positive or negative number.
      An element with a higher z-index is always stacked above than a lower index.
      - Z-Index can take the following values:
      - Auto: Sets the stack order equal to its parents.
      - Number: Orders the stack order.
      - Initial: Sets this property to its default value (0).
      - Inherit: Inherits this property from its parent element.\
**21. Explain the difference between visibility: hidden and display: none?**\
      visibility: hidden hides the element, but it occupies space and affects the layout of the document.\
**22.  What is tweening?**\
       It is the process of generating intermediate frames between two images.\
       It gives the impression that the first image has smoothly evolved into the second one.\
       It is an important method used in all types of animations.\
       In CSS3, Transforms (matrix, translate, rotate, scale) module can be used to achieve tweening.\
**23.  What is tweening?**\
       It is the process of generating intermediate frames between two images.
       It gives the impression that the first image has smoothly evolved into the second one.
       It is an important method used in all types of animations.
           In CSS3, Transforms (matrix, translate, rotate, scale) module can be used to achieve tweening.\
**24.  What is the difference between CSS2 and CSS3??**\
       The main difference between CSS2 and CSS3 is that CSS3 is divided into different sections which are also known as modules. Unlike CSS2, CSS3 modules are supported 
           by many browsers.\
**25.  What are pseudo-elements?**\
       Pseudo-elements are like getting extra DOM elements for free. They allow us to add extra content, decoration and more to our pages without adding extra HTML, and
       they can be animated. For example: ::before, ::after.\
**26.  Name all the modules which are used in the current version of CSS.**\
       There are several modules in CSS as stated below:
       - Selectors
       - Box Model
       - Backgrounds and Borders
       - Text Effects
       - 2D/3D Transformations
       - Animations
       - Multiple Column Layout
       - User Interface.
**27. Define CSS image scripts.**\
      CSS image scripts are a group of images that are placed into one image. It reduces the load time and request number to the server while projecting multiple images
      into a single web page.\
**28. What are CSS counters?**\
      CSS counters are variables that can be incremented by rules of CSS that inspector track how many times the variable has been used.\
**29. What is CSS specificity?**\
       CSS specificity is a score or rank that decides which style declaration has to be used to an element. (*) this universal selector has low specificity while ID
       selectors have high specificity.\
 **30. Write all the properties of the flexbox.**\
       - flex-direction
       - flex-wrap
       - flex-flow
       - justify-content
       - align-items
       - align-content
**31. How to align image vertically in a division that spans vertically on the whole webpage?**\
      It can be done by using the syntax verticle-align: middle in the <div1> element and even we can bind the two text spans around with another span and after this,
      we have to use verticle-align: middle in the content #icon.\
**32. What is the use of the Box Model in CSS?**\
      In CSS, the box model is a box that binds all the HTML elements and it includes features like margins, border, padding, and the actual content.
      By using a box model we will get the authority to add the borders all around the elements and we can also define the space between the elements.\
**33. What is a CSS pseudo-class?**\
      It is a class that is used to define a special state of an HTML element. For example: hover.\
**34. Write all the position states used in CSS.?**\
       - Static(default) - it is always positioned according to the normal flow of the page.\
       - Relative - Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position.\
       - Fixed - it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.\
         A fixed element does not leave a gap in the page where it would normally have been located.\
       - Absolute -  is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
         However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.
         Note: A "positioned" element is one whose position is anything except static.\
 **35. What are navigation bars in CSS?**\
       By using navigation bars we can make an ordinary HTML page into a user-specific and more dynamic web page. Basically, it is a list of links, hence use of ul
       and li elements makes the perfect sense.\
 **36. Differentiate between inline and block element?**\
       Inline element does not have an element to set width and height and also it does not have the line break.Block element specification:
       They do have the line break. They define the width by setting a container and also allow setting height.
       It can also contain an element that occurs in the inline element\
 **37. Differentiate between inline and block element?**\
       Inline element does not have an element to set width and height and also it does not have the line break.\
 **38.  What are attributes and how are they used?**\
        input tags can have a type (text, number, radio, etc) and a tags can have href.You can target elements with particular attributes by using square brackets\
        [attribute="value"].\
 **39.  What does it mean to be mobile first?**\
        A “mobile-first” approach involves designing a desktop site starting with the mobile version, which is then adapted to larger screens (contrary to the\
        traditional approach of starting with a desktop site and then adapting it to smaller screens).\
 **40.  What are functions/mixins?**\
        Mixins are a very handy way of adding a number of styles, based on a particular input parameter. For example, you might always want to add fallback styles when
        adding border-radius, but you don’t necessarily know what value you might want.\
 **41. What is file splitting and why should you use it?**\
       File splitting helps organize your CSS into multiple files, decreasing page load time and making things easier to manage. If you’re working with any of the
       preprocessors above, you can start splitting up your files.\
 **42. What are the benefits of SVG?**\
       SVG is an image format that is vector based. It’s an efficient format for that (small file sizes). You can scale them and they retain their sharpness at any\
       size (bonus points for mentioning raster might have the upper hand at tiny sizes).\
 **43. Explain display properties: inline, block, inline-block**\
       - inline - Displays an element as an inline element (like <span>). Any height and width properties will have no effect.\
       - block - Displays an element as a block element (like <p>). It starts on a new line, and takes up the whole width.\
       - inline-block - Displays an element as an inline-level block container. The element itself is formatted as an inline element, but you can apply height and\ 
         width values.\
 **44. What are the differences between css variables and scss variables?**\
       - inline - Displays an element as an inline element (like <span>). Any height and width properties will have no effect.\
       - block - Displays an element as a block element (like <p>). It starts on a new line, and takes up the whole width.\
       - inline-block - Displays an element as an inline-level block container. The element itself is formatted as an inline element, but you can apply height and\ 
         width values.\
 **45. What are the differences between css variables and scss variables?**\
       SASS variables are replaced with their values as the preprocessor produces its CSS output long before the browser interprets the code,
       while CSS custom properties are evaluated by the browser at runtime.
       Custom properties (sometimes referred to as CSS variables or cascading variables) are entities defined by CSS authors that contain specific values to be reused
       throughout a document. They are set using custom property notation (e.g., --main-color: black;) and are accessed using the var() 
       function (e.g., color: var(--main-color);).
           
         Sources: https://www.javatpoint.com/css-interview-questions \
                    https://hackr.io/blog/css-interview-questions \
                    https://www.w3schools.com/css/css_positioning.asp \
                    https://www.softwaretestinghelp.com/css-interview-questions \
                    https://www.goskills.com/Development/Resources/CSS-interview-questions-answers \
                    https://css-tricks.com/interview-questions-css/ \
         

