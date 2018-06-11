### Facts for Headings and Paragraph

1. Headings

    - Any document in HTML starts with a heading and in each heading differs in size.

    - There are six levels of HTML headings: `<h1>,<h2>,<h3>,<h4>,<h5>,<h6>`.

    - `<h1></h1>` tag is used for the main headings. The content for `<h1></h1>` tag appears to have the largest text content.

    - `<h2></h2>` tag is used for the subheadings and any further sections under subheadings are indicated by `<h3>, <h4>, <h5>, <h6>`.
    
    - The content for `<h6></h6>` tag appears to have the smallest text content. 

    - Only make use of the `HTML headings tags` for `headings sections` only. 

    - Writing headings in html adds one line before and one line after. Adding `attributes` can be used in a `heading` element.

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

2. Paragraphs

    - The paragraph element is structured using the `<p>` tag.

    - The paragraph tag `<p></p>` structures text into different paragraphs in the document. Each paragraph of text should be between the opening paragraph tag `<p>` and the closing paragraph tag `</p>`.

    - `Attributes` can be added to the paragraph tag.

    - The code below shows how paragraphs are used in HTML.

Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Headings and Paragraph</title>
    </head>
    <body>
        <p id="p_1" title="Paragraph 1">Text here</p>
        <p id="p_2" title="Paragraph 2">Another text here</p>
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
        <p id="p_1" title="Paragraph 1">Text here</p>
        <p id="p_2" title="Paragraph 2">Another text here</p>
    </body>
</html>



