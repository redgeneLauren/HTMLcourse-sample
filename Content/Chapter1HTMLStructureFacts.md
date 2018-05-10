### Facts for HTML Basic Page Structure

HTML stands for Hypertext Markup Language. It is the most widely used language for writing web pages.

1. Tags and Elements

    - HTML is composed of characters that live inside angle brackets `< >`, which are called the `HTML elements`.

    - Tags consists of an open angle bracket `<` followed by an `element name` and a closing angle bracket with a forward slash character `/>`.

    - Tags are like containers. They carry information found between the opening tag `<>` and the closing tag `</>`. 

    Code:

    ```html
    <!DOCTYPE html>
    <html>
	    <head>
		    <title>My homepage</title>
	    </head>
	    <body>
		    <h1>My first heading inside a header tag</h1>
                <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>
	    </body>

    </html>

    ```
    - The `<!Doctype >` goes before the HTML `<html>` element; it defines the document whether the page will contain `HTML`, `XHTML` or both. 

    - The html tag `<html></html>` encloses the complete HTML document.
    
    - The head tag `<head></head>` serves as a container for metadata in HTML. Some of these metadata are `<title>`,`<style>`, `<link>`, `<script>` and `<base>` elements.

    - The contents of a `<title></title>` tag is located at the top part of the browser window above the URL section. It is seen in the browser tab. 

     - Anything written between the body tag `<body></body>` will appear in the main browser window or web page.
    
3. Attributes

    - An attribute defines the characteristics of an `element`. 

    - Attributes are written inside the opening tag after the `element name`; they are made up of two parts: `name` and `value` and they are separated by an `=` equal sign.

    Code:

    ```html
     <!DOCTYPE html>
    <html>
	    <head>
		    <title>My homepage</title>
	    </head>
	    <body style="font-family: courier">
		    <h1>My first heading inside a header tag</h1>
                <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>
	    </body>

    </html>
    
    ```
     
     Output:

    <!DOCTYPE html>
    <html>
	<head>
	<title>My homepage</title>
	</head>
	<body style="font-family: courier">
	<h1>My first heading inside a header tag</h1>
    <p lang="eng-us"; style="color: red">My first HTML coding inside a paragraph</p>
	</body>
    </html>

    - The attribute `name` in the example code above are `lang` and `style`. 

    - Attribute `name` indicates the kind of extra information you are supplying about the content of the `element`. It should be written in lowercase.

    - The attribute `value` in the example code above are `eng-us` and `color:red`. 
    
    - Attribute `value` is the setting for the declared attribute of `name`. It should be placed inside the double quotes `“ ”` . 

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
    


 
    



