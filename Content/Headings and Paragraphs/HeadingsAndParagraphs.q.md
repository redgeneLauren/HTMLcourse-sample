# Using HTML Using Headings

+++

### Part 1:  Sample Code Analysis

:::
///type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using Headings</title>
    </head>
    <body>
        <h1>Short Stories</h1>
        <h2 id="h_1">The Cask of Amontillado</h2>
        <h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3>
	    <p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>
        <h6 id="h_6" title="Source">Source: americanliterature.com</h6>
    </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its ouput?

- <h1>Short Stories</h1><h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3><p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p><h6 id="h_6" title="Source">Source: americanliterature.com</h6>

- <p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>

- <h2 id="h_1">The Cask of Amontillado</h2><h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3><p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>

- <h1>Short Stories</h1><h2 id="h_1">The Cask of Amontillado</h2><h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3><p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p> 

-<h1>Short Stories</h1><h2 id="h_1">The Cask of Amontillado</h2><h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3><p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p><h6 id="h_6" title="Source">Source: americanliterature.com</h6>


/// type=SS, answer=[3]

What does the element `<p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>` on line 10 represent?

- The text element.

- The content element.

- The paragraph element.

- The thought element.

- The header element.


/// type=MS, answer=[1,2,3,4,5]

Which of the following elements are inside the `<body>` tag?

- `<h2 id="h_1">The Cask of Amontillado</h2>`

- `<h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>`

- `<h6 id="h_6" title="Source">Source: americanliterature.com</h6>`


/// type=SS, answer=[3]

Which of the following outputs the largest text on the web page?

- `<h2 id="h_1">The Cask of Amontillado</h2>`

- `<h3 id="h_2" title="Author">(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>`

- `<h6 id="h_6" title="Source">Source: americanliterature.com</h6>`


/// type=MS, answer=[2,3,4]

Which of the following are HTML elements?

- `<head></head>`

- `<p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>`

- `<h1>Short Stories</h1>`

- `<title>Using Headings</title>`

- `<html></html>`


/// type=MS, answer=[2,3,4]

Which of the following elements are the inner elements of the `<body>` element?

- `<title>Using Headings</title>`

- `<h6 id="h_6" title="Source">Source: americanliterature.com</h6>`

- `<h1>Short Stories</h1>`

 - `<p id="p_2" title="Summary"> A classic revenge story in the horror genre.</p>`

- `<head></head>`


/// type=SS, answer=[5]

What is `id="h_1"` inside the element `<h2 id="h_1" style="color: red">The Cask of Amontillado</h2>` ?

- It is the set paragraph tool. 

- It is an element label for paragraph.

- It is the description tool for the paragraph element.

- It is the feature to set for the paragraph element.

- It is the id attribute to give a unique identity to the element.


/// type=SS, answer=[4]

On line 7, what does the `<h1>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It contains information about the page.

- It sets the largest heading of the document.

- It specifies the content to display in the web page.


/// type=SS, answer=[3]

What does the HTML element `<p id="p_2"> A classic revenge story in the horror genre.</p>` on line 10 represent?

- The `text` element.

- The `content` element.

- The `paragraph` element.

- The `thought` element. 

- The `header` element.


/// type=SS, answer=[3]

How many header tags are used in the code above?

- 6

- 1

- 3

- 2

- None


/// type=SS, answer=[5]

Which element appears to have the smallest text?

- `<title>Using Headings</title>`

- `<h1>Short Stories</h1>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`


/// type=MS, answer=[1,3,4,5]

Which line of codes are the `HTML headings` written?

- Line 7

- Line 3

- Line 8

- Line 11

- Line 9


/// type=SS, answer=[1]

How many subheadings are there in the code above?

- 3

- 4

- 1

- 2

- 5


/// type=SS, answer=[2]

Which element appears to have the largest text?

- `<title>Using Headings</title>`

- `<h1>Short Stories</h1>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`


/// type=SS, answer=[3]

Which element is the second subheading?

- `<h3>(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `


/// type=SS, answer=[3]

On the second subheading, what attribute was added to the heading tag?

- title

- font-size

- id

- style

- color


/// type=SS, answer=[1]

Which of the following element is the third subheading ?

- `<h3>(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `


:::

+++

+++

### Part 2: Knowledge Assessment

/// type=SS, answer=[4]

Which of the following tag is used to construct an HTML paragraph?

- `<paragraph></paragraph>`

- `<content></content>`

- `<c></c>`

- `<p></p>`

- `<section></section>`


/// type=SS, answer=[5]

Which `header tag` makes text appear the smallest?

- `<h2></h2>`

- `<h4></h4>`

- `<h1></h1>`

- `<h6></h6>`

- `<h5></h5>`


/// type=SS, answer=[3]

Which `header tag` makes text appear the largest?

- `<h2></h2>`

- `<h4></h4>`

- `<h1></h1>`

- `<h6></h6>`

- `<h5></h5>`


/// type=SS, answer=[2]

How many `heading tags` are there in HTML?

- 4

- 6

- 1

- 5

- 7


/// type=SS, answer=[3]

Which of the following statement best describes an HTML paragraph?

- A set of words that is complete itself.

- Small group of words to make a conceptual unit.

- It structures the text into different paragraphs in the document. 

- Standardized parts that can be used to construct more complex structure.


/// type=SS, answer=[3]

What type of heading are `<h2>, <h3>, <h4>, <h5>, <h6>` tags?

- Structural headings

- Internal headings

- Subheadings

- Inner headings

- Alternative headings


/// type= SS, answer=[3]

What type of headings is `<h1>`?

- Inner heading

- Heading one

- Main heading

- First heading

- One headings


:::

+++

+++

### Part 3: Finding and Fixing Errors

:::

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title> 
    </head>
    <body>
        <h1 id="h_1">The first heading</h1>
        <h2 id="h_2" title="First Section">The second heading
        <p id="p_1" title="Content">First Paragraph.</p>
        <p id="p_2" title="Closing">Second Paragraph.</p>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1 id="h_1">The first heading</h1><h2 id="h_2" title="First Section">The second heading</h2><p id="p_1" title="Content">First Paragraph.</p><p id="p_2" title="Closing">Second Paragraph.</p>

- <p id="p_1" title="Content">First Paragraph.</p><p id="p_2" title="Closing">Second Paragraph.</p>

-  <h1 id="h_1">The first heading<h2 id="h_2" title="First Section">The second heading</h2><p id="p_1" title="Content">First Paragraph.</p><p id="p_2" title="Closing">Second Paragraph.</p>

- <h1 id="h_1">The first heading</h1><h2 id="h_2" title="First Section">The second heading<p id="p_1" title="Content">First Paragraph.</p><p id="p_2" title="Closing">Second Paragraph.</p>

- <h1 id="h_1">The first heading</h1><h2 id="h_2" title="First Section">The second heading


/// type=SS, answer=[3]

What makes the paragraphs `First Paragraph` and `Second Paragraph.` appear to be a heading? 

- The paragraph tag used is invalid.

- The closing tag `</p>` is missing.

- There is no closing tag `</h2>`.

- The `<paragraph></paragraph>` tag is missing. 

- The headings should be enclosed by closing tag `</heading>`.


/// type=CR, answer=[tests/HeadingsAndParagraph/CorrectHeadingTag.html]

Rewrite the HTML code above to seperate the paragraphs from the heading tag.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title> 
    </head>
    <body>
        <h1 id="h_1">The first heading</h1>
        <h2 id="h_2" title="First Section">The second heading
        <p id="p_1" title="Content">First Paragraph.</p>
        <p id="p_2" title="Closing">Second Paragraph.</p>
    </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/HeadingsAndParagraph/HeadingsAndPargraphTest.html]

Write an HTML document that uses three headings. The first heading `<h1>` with a text `Usage of Headings and Paragraph`, the second heading `<h2>` with a text `Programming Wisdom` and the third heading `<h6>` with a text `@codingwisdom`. All headings should have a `title attribute` named `h_1, h_2, h_3`. Then, add a paragraph text `"To me programming is more than an important practical art. It is also a gigantic undertaking in the foundations of knowledge." - Grace Hopper` between the second and third heading. Observe proper nesting of HTML elements. Execute the program to view the result.

```html

```