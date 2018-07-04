### Facts for Working with Images

Images can be embeded in an HTML document. In embedding images to the page you will use the empty element `<img>`.

`<img>` is called as an empty element because it is an element that does not require a closing tag. It is referred to as a `self-closing tag`. 

In order to embed an image to an HTML document, these are the following attributes needed:

- `src` - It is an attribute name that sets the source location of the image. The attribute value of `src` sets the following: 

    - Image name - it is the file name of the image.

    - Image type - it is the file type of the image whether it is saved as `jpeg` or `png`. 

    ```html
    <img src="Codestop_Logo.png">

    ```
    - file directory - if the image is saved in a different folder outside from the HTML document it is important to specifiy the location and seperate it with a forward slash character `/` .

    ```html
    <img src="images/CodeStop_Logo.png">

    ```

- `alt` - It is an attribute name and its value is in a text format that becomes visible if the image is unable to render in the page. The value of `alt` serves as the alternative text to appear for the image. 

- `title` - It is an attribute name and its value is in a text format that describes the meaning of the image.

- `width` - It is an attribute name and its value are set either in pixels or percentage to specify the width size of the image.

- `height` -It is an attribute name and its value are set either in pixels or percentage to specify the height of the image.

The example code shows how an image is embeded in an HTML document:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Images</title>
    </head>
    <body>
        <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code. (https://codestop.io/about-us)">
    </body>
</html>

```

Output:
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Images</title>
    </head>
    <body>
        <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code. (https://codestop.io/about-us)" height="50px" width="200px">
    </body>
</html>


 
