# Links and Images in HTML

## Key Concepts:

1. **Creating Links:**
   - Links are created using the `<a>` (anchor) element.
   - Use the `href` attribute to specify the destination URL.
   
   `<a href="https://www.theodinproject.com/about">About The Odin Project</a>`

2.	Opening Links in a New Tab:
    - Use the target attribute with _blank to open links in a new tab.
    - Use the rel attribute with noopener and noreferrer for security:

    `<a href="https://www.theodinproject.com/about" target="_blank" rel="noopener noreferrer">About The Odin Project</a>`


3.	Absolute vs. Relative Links:
    - Absolute Links: Include the full URL (scheme + domain + path).
    `https://www.theodinproject.com/about`
    - Relative Links: Point to other pages within your own website, omitting the domain.
    `about.html`

4.	Creating an About Page:
    - Create an about.html file in a pages directory and link to it using relative paths.

    `<a href="pages/about.html">About</a>`


5.	Images in HTML:
    - Display images using the `<img>` element, which is a void element and does not require a closing tag.
    - Use the src attribute to specify the image location.

    `<img src="./images/dog.jpg" alt="A cute dog" width="300" height="200">`


6.	Accessing Parent Directories:
    - Use ../ to navigate to a parent directory.

    `<img src="../images/dog.jpg" alt="A cute dog">`

7.	Alternative Text for Images:
    - Use the alt attribute to describe the image, improving accessibility and providing fallback text if the image doesn’t load.
    
8.	Image Size Attributes:
    - Specify width and height attributes to prevent layout shifts when the image loads.
