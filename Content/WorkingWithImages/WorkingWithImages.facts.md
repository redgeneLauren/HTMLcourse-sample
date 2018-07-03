### Facts for Working with Images

Images can be embeded in an HTML document. In embedding images to the page you will use the empty element `<img>`.

`<img>` is referred to as an empty element because it is an element that does not require a closing tag. 

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

- `alt` - It is an attribute name and its value is a text that sets the description of the image.

- `title` - It is an attribute name and its value is a text that further explains the meaning of the image.

- `width` - It is an attribute name and its value are set either in pixels or percentage in order to declare the width size of the image.

- `height` -It is an attribute name and its value are set either in pixels or percentage in order to declare the height of the image.

The example code shows how an image is embeded in an HTML document:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Images</title>
    </head>
    <body>
        <img src="HTML.png" alt="" title="">
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
        <img src="CodeStop_Logo.png" alt="Codestop Beta" title="" width="200px" height="60px">
    </body>
</html>



 
