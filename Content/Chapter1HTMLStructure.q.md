# HTML Basic Page Structure

+++

### Part 1: Sample Code Analysis

///type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Page Structure</title>
    </head>
        <body>
            <p style="color:red; text-align: center; font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```

/// type=SS, answer=[4]

What is the purpose of the `<!Doctype html>`?

- It serves as the comment section of HTML.

- It is the portal for saving files.

- It is the documentator of HTML.

- It identifies the type of document for the web browser.

- It does not have any purpose.

/// type=SS, answer=[2]

What type of tag is the `<title>`?

- An ending tag.

- An opening tag.

- A beginning tag.

- A closing tag.

- A starting tag.

/// type=SS, answer=[3]

What is `Line 7` of the code above represent?

- It represents the `text` tag.

- It represents the `content` tag.

- It represents the `paragraph` tag.

- It represents the `thought` tag. 

- It represents the `header` tag.

/// type=SS, answer=[3]

Which of the following line of code that can be seen in the browser tab of a browser window?

- `Line 2`

- `Line 3`

- `Line 4`

- `Line 6`

- `Line 1`

/// type=SS, answer=[4]

What is `style` in line 7?

- The attribute `value`

- The attribute `property`

- The attribute `setting`

- The attribute `name`

- The attribute `description`

/// type=MS, answer=[2,3,5]

Select which of the following statements correctly describes the code above?

- It does not show anything, just a blank page.

- The code shows a text `Welcome to HTML` in red.

- The text is aligned at the `center` of the page

- The name in the browser tab of the browser window is `HTML`

- The text font is in `comic sans`

+++

+++

### Part 2: Knowledge Assessment

:::

///type SS, answer[4]

What does the acronym HTML stand for?

- Hypertext Mark Languages

- Hyperlink Markup Language

- Hypertext Mark Language

- Hypertext Markup Language

- Hyperlink Mark Language

/// type=SS, answer[1]

Which of the following correctly shows how HTML code should be written?

- Using angled brackets `< >`.

- Using brackets `[]`.

- Using double quotes `""`.

- Using exclamation points `!`.

- Using number sign `#`.


/// type=SS, answer[4]

What tag will information be inside the main browser or on the web page?

- `<title></title>`

- `<head></head>` 

- `<html></html>`

- `<body></body>`

- `<!DOCTYPE html>`

/// type=SSS, answer[3]

How are attributes written in HTML?

- `element name`, `element value` seperated by an `=` equal sign.

- `element name`, `element value` seperated by a `:` colon.

- `name`, `value` seperated by an `=` equal sign.

- `name`, `value` seperated by a `:` colon.

- `element name`, `value` seperated by a `:` colon.

/// type=MS, answer[1,3,5]

Select the following items that is needed to construct an HTML `tag`?

- An `element name`.

- An `!` exclamation point

- A `/>` closing angled bracket

- A `?` question mark.

- An `<` open angled bracket

:::

+++

+++

### Part 3: Finding and Fixing Errors

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
    <html>
        <head>
            <title>HTML Practice</title>
        </head>
         <body>
            <p style="text-align: center"><i><h3>This text will be a centered, italicized heading (size 3)</i></h3>
            <b>This text will be right aligned and bolded</b>
        </body>
    </html>

   
```
Render the HTML code. Which statement best describes the error?

- The text are not aligned at the center.

- There is no closing tag `</p>` for paragraph.

- The HTML code is not properly nested.

- The attribute name `style` is written incorrectly.

- There seems to be no problem with the code.

/// type=CR, answer=[path]

Correct the code so that it outputs the correct instruction per line of text given inside the HTML code.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Practice</title>
    </head>
    <body>
        <p style="text-align: center"><i><h3>This text will be centered, italicized heading (size 3)</i></h3>
        <b>This text will be centered aligned and bolded</b>
    </body>
</html>

```

:::

+++

+++

### Part 4: Practice

:::

/// type=CR, answer=[path]

Write an HTML document that outputs the text "My Travel Places Goals" with the following charactertics: `text-aligned: center`,  italicized `<i></i>`, heading size 1 `<h1></h1>`, `font-color: red`,  `font-family: comic sans `. 

Followed by another text below "New York, Paris, Singapore and Japan." With the following characteristics: `text-aligned: center`,text is bolded `<b></b>`, `font-color: pink`, `lang= eng-us`, `font:family: courier`.

Observer proper HTML nesting. Render the HTML code to view the result.

```html



```



