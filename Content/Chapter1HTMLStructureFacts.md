### Facts for HTML Basic Page Structure

1. Understanding Structures

    - The use of `headings` and `subheadings` reflects the hierarchy of information.
    
    - A document might start with a large heading followed by an introduction then expanded upon subheadings. 
    
    - Each topic might have new paragraphs and each section can have headings to describe what it covers.

2. Tags and Elements

    - Tags are used to mark the start and end of an HTML element.

     - Tags consists of an open angle bracket `<`, followed by an `element name` and a closing angle bracket `/>`.

    - HTML code is made up of characters that live <u>inside</u> angled brackets `< >` these are called the `HTML elements`. 
    
    - Tags are like containers. They tell you about the information that lies between the opening tag `<>` and the closing tag `</>`. 

    Code:

    ```html
    <!DOCTYPE html>
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
    - The `<!Doctype >` goes before the HTML `<html>` tag, it tells the browser wether the page contains `HTML`, `XHTML` or both. 

    - The opening `<html>` tag and the closing `</html>` tag, identifies the start of the HTML document.
    
    - Anything written between the `<body></body>` tags will appear in the main browser window or web page.
    
    - The `<head>` tag contains information about the page. Inside the `<head></head>` tag is the `<title>` tag.

    - The contents of the `<title>` tag is usually located at the top part of the browser window where you usually type the URL of the page.	

3. Attributes

    - Attributes provide more information about the contents of an `element`. 
    
    - An attribute defines a property of an `element`. 

    - Attributes appear on the opening tag and are made up of two parts: `name` and `value` and are separated by an  `=` equal sign.

    Code 1: Shows a tag with no attribute: 
    
    ```html

    <p>My first HTML coding inside a paragraph</p>

    ```

    Code 2: Shows a tag with an attribute:

    ```html
    <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>
    
    ```

    Output 1:
     <p>My first HTML coding inside a paragraph</p>

     Output 2:
     <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>

    - The attribute `name` which is `lang` and `style` indicates the kind of information you provide on the element’s content, it should be written in lowercase.

    - The attribute `value` which is `eng-us` and `color:red` is the information or the setting for the declared attribute of `name`. It should be placed inside the double quotes `“ ”` . 

    - In the example code the attribute `name` which is `lang` is used to indicated the language used in the element. The `value` of this attributes specifies it to US English

    - Different `attributes` have different `values`.
    
    - Most attribute values are pre-defined or follow a stipulated format.  

4. Nesting

    - HTML code should be `nested` in a proper order, the opening tag `<>` is always followed by a closing tag `</>`.

    - In the code below shows the proper nested HTML coding.

    - An open tag for `<html>` is paired with a closing tag `</html>`

    - Inside the `<html></html>` tag are other nested tags to build up the html code.

    - Proper `nesting` should be observed in using HTML coding.

    Code:

    ```html
    <!DOCTYPE html>
      <html>
        <head>
            <title></title>
        </head>
            <body></body>
      </html>  

    ```
    


 
    



