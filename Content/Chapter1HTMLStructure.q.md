# HTML Basic Page Structure

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Page Structure</title>
    </head>
        <body>
            <p style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```
/// type=SS, answer=[4]

What is the purpose of the `<!Doctype html>`?

- It serves as the comment section of HTML.

- It is the portal for saving files.

- It is the documentation of HTML.

- It defines the type of document.

- It does not have any purpose.

/// type=SS, answer=[2]

What type of tag is `<title>`?

- An ending tag.

- An opening tag.

- A beginning tag.

- A closing tag.

- A starting tag.

/// type=SS, answer=[3]

What does `Line 7` of the code above represent?

- It represents the `text` tag.

- It represents the `content` tag.

- It represents the `paragraph` tag.

- It represents the `thought` tag. 

- It represents the `header` tag.

/// type=SS, answer=[3]

Which of the following line of code will information be seen inside the browser tab?

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

Which of these statements correctly describes the output of the HTML code above?

- It does not show anything, just a blank page.

- The code shows a text `Welcome to HTML` in red.

- The text is aligned at the `center` of the page

- The name in the browser tab of the browser window is `HTML`

- The text font is in `comic sans`

/// type=SS, answer=[1]

On line 7, which of the following is an element name?

- p

- style

- color: red

- text-align

- font-family

/// type=MS, answer=[1,4,5]

Which of the following is an attribute `value` on line 7?

- color: red

- Welcome to HTML

- style

- text-align: center

- font-family: comic sans

/// type=SS, answer=[1]

What color will be applied to the text?

- Blue

- Black

- Red

- Nothing

- Cannot be identified.

:::

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
       <style="color: red; font-family: courier; font-size: 20">HTML Basic Page Stucture
    </body>
</html>

```
/// type=SS, answer=[3]

What is incorrect with the nesting of the HTML code?

- It lacks the opening html tag.

- It lacks a paragraph tag. 

- It lacks the closing body tag. 

- It lacks the html tag.

- Everything is correct with the HTML code.

/// type=SS, answer=[4]

What font type will be applied to the text `HTML Basic Page Structure`?

- Comic sans

- Courier

- Times new Roman

- Default HTML font

- Arial

/// type=SS, answer=[3]

What color will be applied to the text `HTML Basic Page Structure`?

- Red

- Blue

- Black

- Yellow

- Orange

:::

+++

+++

### Part 2: Knowledge Assessment

///type SS, answer=[4]

What does the acronym HTML stand for?

- Hypertext Mark Languages

- Hyperlink Markup Language

- Hypertext Mark Language

- Hypertext Markup Language

- Hyperlink Mark Language

/// type=SS, answer=[1]

Which of the following correctly shows how HTML code should be written?

- Using angle brackets `< >`.

- Using brackets `[]`.

- Using double quotes `""`.

- Using exclamation points `!`.

- Using number sign `#`.

/// type=SS, answer=[4]

What tag will information be inside the main browser of a web page?

- `<title></title>`

- `<head></head>` 

- `<html></html>`

- `<body></body>`

- `<!DOCTYPE html>`

/// type=SS, answer=[3]

How are attributes written in HTML?

- `element name`, `element value` seperated by an `=` equal sign.

- `element name`, `element value` seperated by a `:` colon.

- `attribute name`, `attribute value` seperated by an `=` equal sign.

- `attribute name`, `attribute value` seperated by a `:` colon.

- `element name`, `attribute value` seperated by a `:` colon.

/// type=MS, answer=[1,3,5]

Which characters is needed to construct an HTML `tag`?

- A `+` plus sign.

- An `!` exclamation point

- A `/>` closing angled bracket

- A `?` question mark.

- An `<` open angled bracket

/// type=SS, answer=[4]

What does a `<head></head>` tag contain?

- Information

- Nothing

- Text

- Metadata

- Content

/// type=MS, answer=[2,4,5]

Which are metadata for the head tag `<head></head>`?

- `<body>`

- `<title>`

- `<html>`

- `<link>`

- `<style>`

/// type=SS, answer=[5]

What character is used to inidicate an end tag?

- The double quotes character `""`

- The back slash character `\`

- The percent character `%`

- The ampersand character `&`

- The forward slash character `/`

/// type=SS, answer=[4]

Which of the following tags represents the beginning of a paragraph?

- `<body>`

- `<html>`

- `<head>`

- `<p>` 

- `<paragraph>`

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

/// type=SS, answer=[2]

Run the HTML code. Which statement best describes the error?

- The text are not aligned at the center.

- There is no paragraph tag `<p></p>`.

- The HTML code is not properly nested.

- The attribute name `style` is written incorrectly.

- Everything is written correctly.

/// type=CR, answer=[path]

Correct the HTML code so that it outputs the correct instruction per line of text given inside the paragraph tag in the HTML code.

- `This text wil be centered, italicized heading(size 3)`
-  `This text will be centered aligned and bolded.`

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Practice</title>
    </head>
    <body>
        <p style="text-align: center; color:red"><i><h3>This text will be centered, italicized heading (size 3)</i></h3>
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

Observer proper HTML nesting. Run the HTML code to view the result.

```html






```



