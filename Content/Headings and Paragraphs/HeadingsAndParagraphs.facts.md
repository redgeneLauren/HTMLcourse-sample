### Facts for Headings and Paragraph

1. Headings

    - Any document in HTML starts with a heading. Each heading differs in size, the six levels of headings in HTML are `<h1>,<h2>,<h3>,<h4>,<h5>,<h6>`.

    - Only make use of the `HTML headings tags` for `headings sections` only. 

    - Writing headings in html adds one line before and one line after. 

    - The code belows shows the proper way in writing headings in HTML.

Code: 
```html
<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1> This is the main heading </h1>
        <h2> This is the 2nd level of subheading </h2>
        <h3> This is the 3rd level of subheading </h3>
        <h4> This is the 4th level of subheading </h4>
        <h5> This is the 5th level of subheading </h5>
        <h6> This is the 6th level of subheading </h6>
    </body>
</html>

```

Output: 

<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1> This is the main heading </h1>
        <h2> This is the 2nd level of subheading </h2>
        <h3> This is the 3rd level of subheading </h3>
        <h4> This is the 4th level of subheading </h4>
        <h5> This is the 5th level of subheading </h5>
        <h6> This is the 6th level of subheading </h6>
    </body>
</html>


- `<h1></h1>` tag is used for the main headings. 
     
- The content for `<h1></h1>` tag appears to be the largest.

- `<h2></h2>` tag is used for the subheadings.

- Any further sections under subheadings are indicated by `<h3>, <h4>, <h5>, <h6>`.
    
- The content for `<h6></h6>` tag appears to be the smallest. 

- Attributes can be used in a `heading` element.

- The code below shows a heading element with attributes. 
    
 Code:
```html

 <!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1 style="font-family: courier; color: orange"> This is the main heading </h1>
    </body>
</html>

```
Output:

 <!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1 style="font-family: courier; color: orange"> This is the main heading </h1>
    </body>
</html>

2. HTML Paragraphs

    - The paragraph element is written using the `<p></p>` tag.

    - The paragraph tag `<p></p>` structures text into different paragraphs in the document. Each paragraph of text should be between the opening paragraph tag `<p>` and the closing paragraph tag `</p>`.

    - The code below shows how paragraphs are used in HTML.

Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Headings and Paragraph</title>
    </head>
    <body>
        <p>Text here</p>
         <p>Text here 2</p>
    </body>
</html>

```
Output:

<!DOCTYPE html>
<html>
    <head>
        <title>Headings and Paragraph</title>
    </head>
    <body>
        <p>Text here</p>
         <p>Text here 2</p>
    </body>
</html>

- Attributes can be added to the `paragraph` element.

- The code below shows a paragraph element with attributes.

Code
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Headings and Paragraph</title>
    </head>
    <body>
        <p style="text-align: center; font-family: courier; font-size: 20px; color: pink">Text here</p>
         <p style="text-align: center; font-family: courier; font-size: 20px; color: green">Text here 2</p>
    </body>
</html>

 ```
Output:

<!DOCTYPE html>
<html>
    <head>
        <title>Headings and Paragraph</title>
    </head>
    <body>
        <p style="text-align: center; font-family: courier; font-size: 20px; color: pink">Text here</p>
         <p style="text-align: center; font-family: courier; font-size: 20px; color: green">Text here 2</p>
    </body>
</html>



   
    