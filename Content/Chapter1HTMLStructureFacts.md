### Facts for HTML Structure Lesson

1. Understanding Structures

    - The use of headings and subheadings reflects the hierarchy of information. A document might start with a large heading followed by an introduction then expanded upon subheadings. Each topic might have new paragraphs and each section can have headings to describe what it covers.

2. Tags and Elements

    - HTML code is made up of characters that live inside angled brackets `< >` these are called the HTML elements. 
    
    - Elements are made up of two tags an opening tag `<` and a closing tag `>`. 

    - Tags are like containers. They tell you about the information that lies between the opening tag `<>` and the closing tag `</>`. 

    Code:

    ```html
    <html>
	    <head>
		    <title>My homepage</title>
	    </head>
	    <body>
		    <h1>My first heading inside a header tag</h1>
             <p> My first HTML coding inside a paragraph</p>
	    </body>

    </html>

    ```

    - The opening `<html>` tag and the closing `</html>` tag, identifies the start of the HTML document.
    
    - Anything written between the `<body></body>` tags will appear in the main browser window or web page.
    
    - The `<head>` element contains information about the page. Inside the `<head></head>` tag is the `<title>` element.

    Code:

    ```html
    
    <head>
		    <title>My homepage</title>
	</head>
    
    ```

    - The contents of the `<title>` tag is usually located at the top part of the browser window where you usually type the URL of the page.	

    Code:

    ```html
    <body>
		    <h1>My first heading inside a h1 tag</h1>
                <h2>My fist subheading inside a h2 tag.</h2>
                <p> My first HTML coding inside a paragraph</p>
	</body>
    ```

    - Words between `<h1>` and `</h1>` are the main heading.
    - Words between `< h2>` and `</h2>` form the subheadings.
    - A paragraph of text appears between the tag `<p>` and `</p>`

    Output:

    <h1>My first heading inside a h1 tag</h1>
    <h2>My fist subheading inside a h2 tag.</h2>
    <p> My first HTML coding inside a paragraph</p>
    

3. Attributes
    - Attributes provide more information about the contents of an element. Attributes appear on t```he opening tag and are made up of two parts: `name` and `value` and are separated by an  `=` equal sign.

    Code: 
    ```html
    <p style="color: red">I am a paragraph</p>
    
    ```
    - The attribute `name` which is `style` indicates the kind of information you provide on the element’s content, it should be written in lowercase.

    - The attribute `value` which is `color:red` is the information or the setting for the declared attribute of `name`. It should be placed inside the double quotes `“ ”` . 

    - Different `attributes` have different `values`.
    Most attribute values are pre-defined or follow a stipulated format.   

    Output:
    <html>

     <p style="color: red">I am a paragraph</p>

    </html>



