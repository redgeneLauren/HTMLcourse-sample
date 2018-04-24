### Facts for `HTML Structure` Lesson

1. `Understanding Structures`

    - The use of headings and subheadings reflects the hierarchy of information. A document might start with a large heading followed by an introduction then expanded upon subheadings. Each topic might have new paragraphs and each section can have headings to describe what it covers.

2. `Tags and Elements`

    - HTML code is made up of characters that live inside angled brackets `< >` these are called the HTML elements. Elements are made up of two tags an opening tag `<` and a closing tag `>`. 

    - Tags are like containers. They tell you about the information that lies between the opening and closing tags. 

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
    Output:
    
    <h1>My first heading inside a header tag</h1>
    <p> My first HTML coding inside a paragraph tag</p>


    - The opening `<html>` tag and the closing `</html>` tag, indicates the start of your HTML code.
    
    - Anything written between the `<body></body>` tags will appear in the main browser window.
    
    - The `<head>` element contains information about the page. Inside the <head></head> tag is the `<title>` element.

    ```html
    
    <head>
		    <title>My homepage</title>
	</head>
    
    ```

    - The contents of the `<title>` tag is usually located at the top part of the browser window where you usually type the URL of the page.	

    ```html
    <body>
		    <h1>My first heading inside a header tag</h1>
                <p> My first HTML coding inside a paragraph</p>
	</body>
    ```

    - Words between `<h1>` and `</h1>` are the main heading.
    - A paragraph of text appears between the tag `<p>` and `</p>`
