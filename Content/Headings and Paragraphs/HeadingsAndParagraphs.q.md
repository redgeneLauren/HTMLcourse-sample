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
        <h2 style="color: red">The Cask of Amontillado</h2>
        <h3>(1846) by Edgar Allan Poe</h3>
	    <p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p>
        <h6>Source: americanliterature.com</h6>
    </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its ouput?

- <h2 style="color: red">The Cask of Amontillado</h2><h3>(1846) by Edgar Allan Poe</h3><p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> <h6>Source: americanliterature.com</h6>

- <h1>Short Stories</h1><h2 style="color: red">The Cask of Amontillado</h2><h3>(1846) by Edgar Allan Poe</h3><p> A classic revenge story in the horror genre.</p> <h6>Source: americanliterature.com</h6>

- <h1>Short Stories</h1><h2>The Cask of Amontillado</h2><h3>(1846) by Edgar Allan Poe</h3><p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> <h6>Source: americanliterature.com</h6>

- <h1>Short Stories</h1><h2 style="color: red">The Cask of Amontillado</h2><h3>(1846) by Edgar Allan Poe</h3><p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> 

- <h1>Short Stories</h1><h2 style="color: red">The Cask of Amontillado</h2><h3>(1846) by Edgar Allan Poe</h3><p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> <h6>Source: americanliterature.com</h6>


/// type=SS, answer=[3]

How many header tags are used in the code above?

- 6

- 1

- 3

- 2

- None


/// type=SS, answer=[5]

Which element appears to be the smallest text?

- `<title>Using Headings</title>`

- `<h1>Short Stories</h1>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`


/// type=MS, answer=[1,3,4,5]

Which of the following line of code has the HTML `headings` written?

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


/// type=SS, answer=[3]

What color is applied to the second subheading in the code above?

- Purple

- Blue

- Red

- Yellow

- Orange


/// type=SS, answer=[2]

Which element appears to be the largest text?

- `<title>Using Headings</title>`

- `<h1>Short Stories</h1>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`


/// type=SS, answer=[3]

Which element is the second subheading in the code above?

- `<h3>(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `


/// type=SS, answer=[4]

On the second subheading, what attribute was added to the heading tag?

- color:red

- font-size

- font-family

- style

- color


/// type=SS, answer=[1]

Which element is the third subheading in the code above?

- `<h3>(1846) by Edgar Allan Poe</h3>`

- `<h1>Short Stories</h1>`

- `<h2 style="color: red">The Cask of Amontillado</h2>`

- `<h6>Source: americanliterature.com</h6>`

- `<p style="font-family: courier; font-size: 20px"> A classic revenge story in the horror genre.</p> `


:::

+++

+++

### Part 2: Knowledge Assessment

What tag is used to construct an HTML paragraph?

- `<paragraph></paragraph>`

- `<content></content>`

- `<c></c>`

- `<p></p>`

- `<section></section>`


/// type=SS, answer=[5]

Which of the following `header tag` makes text appear the smallest?

- `<h2></h2>`

- `<h4></h4>`

- `<h1></h1>`

- `<h6></h6>`

- `<h5></h5>`


/// type=SS, answer=[3]

Which of the following `header tag` makes text appear the largest?

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
    <h1> </h1>
    <p style : color = red>This text should be red.</p>
</html>
```

/// type=SS, answer=[]

Execute the program. What is its output?

-

-

-

-

-



Rewrite the HTML code above to print a text in red with a header.

```html


```


+++

+++

### Part 4: Practice

Write an HTML document that uses three headings. The first heading `<h1>` with a text `dfdsfs`, the second heading `<h2>` with a text `sdsdfsd` and the third heading `<h3>` with a text `fdsfsdfsdfasfds`. All headings should be aligned at the center. Then, add a paragraph text `fsfsfsdfsdf` between the second and third heading place `style` attribute inside the paragraph tag with the following characteristics: `font-family: verdana`; `font-size: 20px`; `font-color: blue`; `text-align: center`. Run the HTML code to view the result. 

```html

```