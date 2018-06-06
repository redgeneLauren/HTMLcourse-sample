### Facts for HTML Nesting 

1. Nesting

    - Nesting is the placement of HTML elements within another HTML element. 

    - HTML tags should be nested in a proper order. `Inner tags` should be closed first before closing the `outer tags`.

    Good Nesting:

    `<head><title>HTML Nesting</title></head>`

    Poor Nesting:

     `<head><title>HTML Nesting</head></title>`

    - When an HTML code is not properly nested it may affect the visual appearance of a web page. The HTML code will not render properly due to HTML elements and tags are out of place.

    - The code below shows proper nested HTML document.

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

- The `<html>` is the root element that contains the `<head>` and `<body>` as its inner elements.

- The `<head>` element contains the `<title>` as its inner element. The inner element `<title>` should be closed first before closing the `<head>` tag.

- The `<body>` element contains the `<h1>` and `<p>` as its inner elements. The inner elements `<h1>` and `<p>` should be closed first before closing the `<body>` tag.

2. Indentation 

    - Indentation enhances the readability of the code. Each element within an element should be indented properly to help avoid improper nesting.

    - All inner elements should be indented from the outer element.

    - The example code below shows proper `indentation` of the elements.

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

- The inner elements `<head>` and `<body>` are indented from the outer element `<html>`.

- The inner element `<title>` is indented from its outer element `<head>`.

- The inner elements `<h1>` and `<p>` are indented from their outer element `<body>`.






 
    



