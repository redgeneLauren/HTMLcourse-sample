### Facts for HTML Basic Page Structure

HTML stands for Hypertext Markup Language and it is the most widely used language for writing web pages.

1. Tags and Elements

    - HTML is made up of characters that live inside angled brackets `< >` these are called the `HTML elements`. Elements are made up of two tags an opening tag `<` and a closing tag `>`. 

    - Tags consists of an open angle bracket `<`, followed by an `element name` and a closing angle bracket `/>`.

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
    - The `<!Doctype >` goes before the HTML `<html>` element, it defines the document wether the page will contain `HTML`, `XHTML` or both. 

    - The html tag `<html></html>` encloses the complete HTML document.
    
    - The head tag `<head></head>` represents the document's header it contains the `<title>` element and the `<link>` element.

    - The contents of the title tag `<title></title>` is usually located at the top part of the browser window above the URL section. It is seen in the browser tab. 

     - Anything written between the body tag `<body></body>` will appear in the main browser window or web page.
    
3. Attributes

    - An attribute defines a property of an `element`. 

    - Attributes appear on the opening tag and are made up of two parts: `name` and `value` and are separated by an  `=` equal sign.

    Code:

    ```html
    <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>
    
    ```
     
     Output:

    <p lang="eng-us"; style="color: red; text-align: center;">My first HTML coding inside a paragraph</p>

    - The attribute `name` in the example code above are `lang` and `style`. 

    - Attribute `name` indicates the kind of information you provide on the element’s content, it should be written in lowercase.

    - The attribute `value` in the example code above are `eng-us` and `color:red`. 
    
    - Attribute `value` is the information or the setting for the declared attribute of `name`. It should be placed inside the double quotes `“ ”` . 

    - Different `attributes` have different `values`.
    
    - Most attribute `values` are `pre-defined` or follow a stipulated format.  

4. Nesting

    - HTML code should be `nested` in a proper order, the opening tag `<>` is always followed by a closing tag `</>`.

    - An open tag for `<html>` is paired with a closing tag `</html>`

    - Inside the `<html></html>` tag are other nested tags to build up the html code.

    - Proper `nesting` should be observed in using HTML.

    - The code below shows proper nested HTML.

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
    


 
    



