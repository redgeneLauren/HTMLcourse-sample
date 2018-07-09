# Working with Text

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Sample Code Analysis</title>
    </head>
    <body>
        <h1>Working with Images</h1>
        <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)">
    </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <h1>Working with Images</h1><img src="CodeStop_Logo.png">

- <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)">

- <h1>Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)">

- <h1>Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" width="200px">

- <h1>Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" height="100px">


/// type=SS, answer=[3]

On line 8, what does the the element `<h1>Working with Images</h1>` represent?

- The text element.

- The content element.

- The heading element.

- The thought element.

- The paragraph element.


/// type=SS, answer=[3]

On line 7, what does the `<h1>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It defines the most important heading.

- It contains information about the page.

- It specifies the content to display on the web page.


/// type=SS, answer=[3]

What is `src` inside the `<img>` element?

- It is an attribute that sets the file type of an image.

- It is an attribute that sets the description of an image.

- It is an attribute that sets the source location of an image.

- It is an attribute that specifies the width size of an image.

- It is an attribubte that represents the alternative text to appear for the image.


/// type=SS, answer=[5]

What is `alt` inside the `<img>` element?

- It is an attribute that sets the file type of an image.

- It is an attribute that sets the description of an image.

- It is an attribute that sets the source location of an image.

- It is an attribute that specifies the width size of an image.

- It is an attribubte that represents the alternative text to appear for the image.


/// type=SS, answer=[2]

What is `title` inside the `<img>` element?

- It is an attribute that sets the file type of an image.

- It is an attribute that sets the description of an image.

- It is an attribute that sets the source location of an image.

- It is an attribute that specifies the width size of an image.

- It is an attribubte that represents the alternative text to appear for the image.


:::

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Sample Code Analysis</title>
    </head>
    <body>
        <h1 style="text-align: center">Working with Images</h1>
        <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" height="50px" width="250px">
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" height="50px" width="250px">

- <h1 style="text-align: center">Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)">

- <h1>Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" height="50px" width="250px">

- <h1 style="text-align: center">Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" title="CodeStop is where you learn to code by hurdling over questions and solving interactive challenges (https://codestop.io/about-us)" height="50px" width="250px">

- <h1 style="text-align: center">Working with Images</h1><img src="CodeStop_Logo.png" alt="Codestop Beta Logo" height="50px" width="250px">


/// type=SS, answer=[4]

What is `style="text-align: center"` inside the element `<h1>`?

- It is the unique id to identify the element.

- It is the description tag for the `<p>` element.

- It is a local tag supported by the `<p>` element

- It is an attribute that defines a specific style to the element.

- It is an identifier that sets the style settings for the `<p>` element. 


/// type=SS, answer=[3]

On line 7, which statement best describes `text-align: center` inside the element `<h1 style="text-align: center">Working with Images</h1>`?

- It is a unique id value that identifies the element.

- It is the local tag value supporting the `<p>` element.

- It is the attribute value of the attribute name `style`.

- It is an attribute name that defines a specific style to the element.

- It is an identifier value that sets the style settings for the `<p>` element.


/// type=SS, answer=[2]

What is `text-align` inside the element `<h1 style="text-align: center">Working with Images</h1>`?

- It is a CSS value.

- It is a CSS property.

- It is an element label for a paragraph.

- It is a property value of the `style` attribute.

- It is the text description of the paragraph element.


/// type=SS, answer=[2]

What is `50px` inside the `<img>` element?

- It is an attribute value that sets the width of an image.

- It is an attribute value that sets the height of an image.

- It is an attibute value that describes the meaning of an image.

- It is an attribute value that specifies the source location of an image.

- It is an atttibute value that serves as an alternative text for an image.


/// type=SS, answer=[1]

What is `250px` inside the `<img>` element?

- It is an attribute value that sets the width of an image.

- It is an attribute value that sets the height of an image.

- It is an attibute value that describes the meaning of an image.

- It is an attribute value that specifies the source location of an image.

- It is an atttibute value that serves as an alternative text for an image.


:::

+++

+++

### Part 2: Knowlege Assessment

/// type=SS, answer=[2]

What element is used to embed an image to an HTML document?

- `<im>`

- `<img>`

- `<emImg>`

- `<image>`

- `<encrypt>`


/// type=MS, answer=[1,2]

Which statements correctly describe the `<img>` element?

- These are self-closing elements.

- These are elements that do not require a closing tag.

- These elements represent a closing tag of a particular element. 

- These elements tell the web browser how to structure a text document

- These are special elements that are used to format the appearance of an element.


/// type=SS, answer=[3]

What are self-closing elements?

- These are elements that sets a `CSS` value to an element.

- These are elements that sets a specific style of an element.

- These are elements that does not require to have a closing tag.

- These are elements that sets a division between element and content.

- These are elements that can be written in any section of the HTML code.


/// type=MS, answer=[1,2,3,4]

Which of the following are attributes of the `<img>` element?

- `alt`

- `src`

- `title`

- `height`

- `source`


/// type=SS, answer=[5]

What character should the `src` file directory be seperated with?

- Colon `:`.

- Period `.`.

- Backslash `\`.

- Semi-colon `;`.

- Forward slash `/`.


/// type=SS, answer=[2,5]

Which of the following are recommended to use in measuring height and width of an image in HTML?

- `time`

- `points`

- `pixels`

- `volume`

- `percentage`


/// type=MS, answer=[2,3,5]

What are the different components needed to declare on the value of the `src` attribute?

- `Status`

- `Image name`

- `Image type`

- `Properties`

- `File directory`


/// type=SS, answer=[2]

Which of the following is used to set an alternative text to an embeded image if it fails to render in an HTML document?

- `src`

- `alt`

- `title`

- `alttext`

- `alternative`


/// type=MS, answer=[2,3,4]

Which of the following are an example of an image file format?

- `i`

- `img`

- `png`

- `jpeg`

- `peng`


/// type=SS, answer=[5]

Which of the following statements assert when should the file directory be set in the `src` attribute?

- If the description of the image is unreadable.

- If there are two images with the same file name. 

- If the image is saved in a different image file format.

- If the pixelation of the image is not rendered properly.

- If the image is saved on a different folder from the HTML document.


+++

+++

### Part 3: Finding and Fixing Errors


/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <img src="Codestop_Logo.png" width: "100px">
    </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <img src="Codestop_Logo.png" width="50px">

- <img src="Codestop_Logo.png" width="10px">

- <img src="Codestop_Logo.png">

- <img src="Codestop_Logo.png" width="150px">

- <img src="Codestop_Logo.png" width="300px">


/// type=SS, answer=[4]

What makes the image not render on the specified width of `100px`?

- The attribute name used is incorrect. 

- The value `100px` is enclosed in double qoutes `""`.

- The value `100px` is not a valid measurement for the width of the image.

- The attribute `width` and its value `100px` are seperated with a colon `:`.

- The attribute `width` and its value `100px` are written inside the `<img>` element.


:::

/// type=CR, answer=[tests/WorkingWithImages/InvalidCharacterTest.html]

Correct the HTML code to have the image appear on the right width declared.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <img src="Codestop_Logo.png" width: "100px">
    </body>
</html>

```


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    <head>
    <body>
        <h1>Codestop.io</h1>
        <img src="CodeStop_Logo" alt="Codestop Logo">
        <p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p>
        <h6>(https://codestop.io/about-us)<h6>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1>Codestop.io</h1><p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p><h6>(https://codestop.io/about-us)<h6>

- <h1>Codestop.io</h1><img src="CodeStop_Logo"><p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p>

- <img src="CodeStop_Logo"><p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p><h6>(https://codestop.io/about-us)<h6>

- <h1>Codestop.io</h1><img src="CodeStop_Logo"><p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p><h6>(https://codestop.io/about-us)<h6>

- <h1>Codestop.io</h1><img src="CodeStop_Logo"><h6>(https://codestop.io/about-us)<h6>


/// type=SS, answer=[3]

What makes the image unable to render on the page?

- The element name is incorrect.

- There is no closing tag `</img>`.

- The image file lacks the image file format.

- The image file should not be enclosed in double quotes `""`.

- There is no forward slash character `/` between the attribute name and value.

:::

/// type=CR, answer=[tests/WorkingWithImages/NoFileFormatToImageTest.html]

Correct the HTML code to have the image appear in the HTML document.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    <head>
    <body>
        <h1>Codestop.io</h1>
        <img src="CodeStop_Logo">
        <p>CodeStop is where you learn to code by hurdling over questions and solving interactive challenges. Discover the amazing things you can do by writing your first line of code.</p>
        <h6>(https://codestop.io/about-us)<h6>
    </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/WorkingWithImages/EmbedImageOnDocumentTest.html]

Write an HTML document that embeds an image using the `<img>` element. The image file name is  `CodeStop_Logo.png`, no need to set the file directory for the image. Next, add a heading above the image with the text: `Welcome to Codestop,io` using the `<h1>` element with the following characteristics: `text-align: center`, `color: red`. Then, add a paragraph below the image with the text `"CodeStop is where you learn to code by hurdling over questions and solving interactive challenges." (https://codestop.io/about-us)` using the `<p>` element with the following characteristics: `text-align: center`, `color: blue`, `font-family: courier`. Observe proper nesting. Execute the program to view the output. 