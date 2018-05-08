### Facts for HTML Links

1. Absolute URL Links

    - HTML Links are created using the `<a>` element or the `<a></a>` tag.

    - You can specify which page you want to link using the `href` attribute.

    Code:
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <title>Writing Links</title>
        </head>
        <body>
            <h3>Visit Codestop Now! </h3>
             <a href="https://codestop.io/">Codestop Site</a>
        </body>
    </html>
   
    ```
    Output:

     <!DOCTYPE html>
    <html>
        <head>
            <title>Writing Links</title>
        </head>
        <body>
            <h3>Visit Codestop Now! </h3>
             <a href="https://codestop.io/">Codestop Site</a>
        </body>
    </html>
   
    - The text between the tag `<a></a>` is called the `link text`

    - The `<a href="https://codestop.io/">` is the destination path of the `href` attribute where you want the users to go to when they click on the link. 
    
    - The `Codestop` would be your clickable text this is what the users will see.

    - The value `"https://codestop.io/"` of the `href` attribute is the full web address which is known as the `absolute URL`. 

2. Relative URL Links

    - When you are linking a page on the same site you use a shorthand known as the `relative URL`.

    Code:
    ```html
    <!DOCTYPE html>
        <html>
            <head>
                <title>Writing Links</title>
            </head>
            <body>
                <a href="about-us.html">About</a><br />
                <a href="index.html">Home</a><br />
                <a href="contact.html">Contact</a>
             </body>
         </html>

    ```
    Output:

    <a href="index.html">Home</a><br />
    <a href="about-us.html">About</a><br />
    <a href="contact.html">Contact</a>
   
    - The `"about-us.html"` value of the `href` attribute is the `relative URL` which is the name of the actual file.

    - When all the pages of the site are in the same folder then the value of the `href` attribute is the name of the file.

3. Email Links

    - To create a link that starts with an email address , you use the value `mailto: ` for the `href` attribute.

    Code:
    ```html

     <!DOCTYPE html>
        <html>
            <head>
                <title>Writing Links</title>
            </head>
            <body>
                <a href="regene.baldovino@codingavenue.com">Email Redge</a>
             </body>
         </html>

    ```
    Output:

    
    <a href="mailto: regene.baldovino@codingavenue.com">Email Redge</a>
    



