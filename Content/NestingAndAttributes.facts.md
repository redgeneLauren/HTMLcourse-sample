### Facts for Nesting and Indentation

1. Nesting

    - In an HTML code, HTML elements are contained within other HTML elements which is essential in building a web page. 

    - These HTML elements that are contained within other HTML elements are called `nested elements`.

    - HTML code is `nested` in a proper order. The opening tag `<>` is always followed by a closing tag `</>`.

    - Nesting HTML code would make it easy to see what tags are closed and where the code starts and ends. 

    - Nesting helps to easily differentiate between code and content. 

    - When an HTML code is not properly nested it may affect the visual appearance of the output of a web page. The HTML code will not render properly due to HTML elements and tags are out of place.

    - The code below shows a proper nested HTML.

Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Nesting</title>
    </head>
    <body>
        <h1>Lesson 2: Nesting</h1>
        <p>Nesting HTML elements</p>
    </body>
</html>  
```

- An open tag for `<html>` is paired with a closing tag `</html>`

- Inside the `<html></html>` are the `<head></head>`, `<title>HTML Nesting</title>`, `<body></body>`, `<h1>Lesson 2: Nesting</h1>` and `<p>HTML elements contain other HTML elements</p>` elements. 

- The `<head>` tag contains the element `<title>HTML Nesting</title>` and ends with a closing a tag `</head>`. 

- After the closing tag `</head>` is the opening tag `<body>` which contains the elements  `<h1>Lesson 2: Nesting</h1>` and `<p>HTML elements contain other HTML elements</p>` and ends with a closing tag `</body>`. 

2. Indentation 

    - In `nesting` an HTML code, `indentation` is also essential to nesting. 
    
    - Indentation enhances the readability of the code. 

    - Indentation should reflect a logical structure. An element should match the same `level` as the opening tag.

    - Indent the contents of the element between the opening tag and the closing tag base on the `level` of the element.

    - Do not use unnecessary indentation and blank lines, only indent elements base on its indentation level. 

    - Proper nesting and indentation should be observed in using HTML.

    - The code below shows proper `indentation` and `level` of the elements.

Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Nesting</title>
    </head>
    <body>
        <h1>Lesson 2: Nesting</h1>
        <p>Indenting and alignment of HTML elements</p>
    </body>
</html>  

```

- `Level 1` : The `<html></html>` element is on the first level. It is the first opening element in the HTML code. 

- Inside the `<html></html>` element are the `<head></head>` and `<body></body>` elements. 

- `Level 2` : The `<head></head>` and `<body></body>` elements are on the second level. These elements are `indented` below the opening tag `<html>`. 

- The `<head></head>` element contains an element `<title>HTML Nesting</title>`.

- `Level 3`: The `<title>HTML Nesting</title>` is on the third level. This element is `indented` below the opening tag `<head>`.

- The `<body></body>` element contains elements `<h1>Lesson 2: Nesting</h1>` and `<p>Indenting and alignment of HTML elements</p>`.

- `Level 3`: The `<h1></h1>` and `<p></p>` are on the third level. These elements are`indented` below the opening tag `<body>`






 
    



