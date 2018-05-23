# HTML Basic Page Structure

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Basic Page Structure</title>
    </head>
        <body>
            <h1>Welcome to HTML</h1>
            <p>Lesson1: Basic Page structure of HTML</p>
        </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- Welcome to HTML <p>Lesson1: Basic Page structure of HTML</p>

- Welcome to HTML, Lesson1: Basic Page structure of HTML

- <h1>Welcome to HTML</h1> <p>Lesson1: Basic Page structure of HTML</p>

- <h1>Welcome to HTML</h1>

- <p>Lesson1: Basic Page structure of HTML</p> <h1>Welcome to HTML</h1>


/// type=SS, answer=[2]

What is the purpose of the `<!Doctype html>`?

- It does not have any purpose.

- It defines the type of document.

- It is the documentation of HTML.

- It is the portal for saving files.

- It serves as the comment section of HTML.


/// type=SS, answer=[2]

On line 2, what does the `<html>` tag indicate?

- The end of an HTML document.

- The beginning of an HTML document.

- Contains information about the page. 

- Specifies the content to display on the web page.

- It tells the browser how to structure a text document.


/// type=SS, answer=[1]

On line 10, what does the `</html>` tag indicate?

- The end of an HTML document.

- The begining of an HTML document.

- Contains information about the page.

- Specifies the content to display on the web page.

- It tells the browser how to structure a text document.


/// type=SS, answer=[2]

What type of tag is `<title>`?

- An ending tag.

- An opening tag.

- A beginning tag.

- A closing tag.

- A starting tag.


/// type=SS, answer=[4]

On line 7, what does the `<h1>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It contains information about the page.

- It sets the largest heading of the document.

- It specifies the content to display in the web page.


/// type=SS, answer=[3]

What does the HTML element `<p>Lesson1: Basic Page structure of HTML</p>` on line 8 represent?

- The `text` element.

- The `content` element.

- The `paragraph` element.

- The `thought` element. 

- The `header` element.


/// type=SS, answer=[5]

On line 6, what does the `<body>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It sets the heading of the document.

- It contains information about the page.

- It specifies the content to display in the web page.


/// type=SS, answer=[2]

Which of the following will information be seen on the browser tab?

- `<h1>Welcome to HTML<h1/>`

- `<title>HTML Basic Page Strucure</title>`

- `<p>Lesson: 1 Basic Page Structure of HTML</p>`

- `<!Doctype html>`

- No information will be seen on the browser tab.


/// type=SS, answer=[4]

What does the HTML element `<h1>Welcome to HTML</h1>` on Line 7 represent?

- The `title` element.

- The `label` element.

- The `paragraph` element.

- The `heading` element. 

- The `identifier` element.


/// type=MS, answer=[1,4]

What elements are inside the `<body>` tag?

- `<h1>Welcome to HTML</h1>`

- `<Doctype html>`

- `<title>HTML Basic Page Structure</title>`

- `<p>Lesson1: Basic Page structure of HTML</p>`

- `<html></html>`


/// type=MS, answer=[2,3,4]

Which statements correctly describes the output of the HTML code above?

- It does not show anything, just a blank page.

- It shows a larger and bolded text `Welcome to HTML`.

- The information on the browser tab is `HTML Page Structure`.

- It shows a small text `Lesson1: Basic Page structure of HTML`.

- The text `Lesson1: Basic Page Structure of HTML` is aligned at the center of the page.


/// type=SS, answer=[2]

Which of the following produces the largest text in the web page?

- `<title>HTML Basic Page Structure</title>`

- `<h1>Welcome to HTML</h1>`

- `<p>Lesson1: Basic Page structure of HTML</p>`

- `<!Doctype html>`

- `<head></head>`


/// type=MS, answer=[2,4,5]

Which of the following are HTML elements?

- `<head>`

- `<h1>Welcome to HTML</h1>`

- `<!Doctype html>`

- `<title>HTML Basic Page Structure</title>`

- `<p>Lesson1: Basic Page structure of HTML</p>`

:::

+++

+++

### Part 2: Knowledge Assessment

///type=SS, answer=[4]

What does the acronym HTML stand for?

- Hypertext Mark Languages

- Hyperlink Markup Language

- Hypertext Mark Language

- Hypertext Markup Language

- Hyperlink Mark Language


/// type=SS, answer=[1]

Which of the following correctly show how tags are constructed?

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


/// type=MS, answer=[1,2,3,5]

Which of the following are needed to construct an `HTML tag`?

- An `element` name.

- A `/` forward slash.

- A `>` right angle bracket.

- A `?` question mark.

- An `<` left angle bracket.


/// type=MS, answer=[1,2,4]

Which of the following are HTML tags?

- `<h1>`

- `<head>`

- `<paragraph>`

- `<body>`

- `<contents>`


/// type=SS, answer=[5]

What character is used to indicate an end tag?

- The double quotes character `""` .

- The back slash character `\` .

- The percent character `%` .

- The ampersand character `&` .

- The forward slash character `/` .


/// type=SS, answer=[4]

Which of the following tag represents the beginning of a paragraph element?

- `<body>`

- `<html>`

- `<content>`

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
    This text will be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

type=SS, answer=[1]

Execute the program. What is its output?

- This text will be inside the heading</h1> <p>This text will be inside a paragraph.</p>

- <h1>This text will be inside the heading</h1> <p>This text will be inside a paragraph.</p>
    
- <p>This text will be inside a paragraph.</p> <h1>This text will be inside the heading</h1>

- <h1>This text will be inside the heading</h1>

- <p>This text will be inside a paragraph.</p>


/// type=SS, answer=[5]

Why is the text `This text will be inside the heading` not appear as a heading?

- Missing `<header>` tag in the HTML code.

- Missing `<headline>` tag for the text `This text will be inside the heading`. 

- There is no `<heading>` tag for the text `This text will be inside the heading`.

- The text `This text will be inside the heading` should be inside the `<head>` tag.

- There is no `<h1>` open tag before text `This text will be inside the heading` on line 7.


/// type=CR, answer=[tests/BasicPageStructure/CorrectErrorTests.html]

Correct the HTML code so that it outputs the text `This text will be inside the heading` as a heading in the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Practice</title>
    </head>
    <body>
    This text will be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```


/// type=REPL, readonly=true

```html
<!Doctype html>
<html>
    <head>
        <title>HTML Practice 2</title>
    </head>
    <body>
    <h1>This text will be inside the heading
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- This text will be inside the heading <p>This text will be inside a paragraph.</p>

- This text will be inside the heading This text will be inside a paragraph.

- <p>This text will be inside a paragraph.</p> <h1>This text will be inside the heading
    
- <h1>This text will be inside the heading</h1> <p>This text will be inside a paragraph.</p>

- <h1>This text will be inside the heading <p>This text will be inside a paragraph.</p>


/// type=SS, answer=[5]

What makes the text `This text will be inside a paragraph` appear to be a header?

- Missing `<heading>` tag inside the header tags.

- There is no closing tag after the `<header>` tag.

- The text `This text will be inside a paragraph` is inside the `<header>` tag.

- The text `This text will be inside a paragraph` is outside the `<heading>` tag. 

- There is no `</h1>` closing tag after the text `This text will be inside the heading`.


/// type=CR, answer=[tests/BasicPageStructure/CorrectErrorTests.html]

Correct the HTML code so that it outputs the text `This text will be inside the paragaph` appear not as a header.

```html
<!Doctype html>
<html>
    <head>
        <title>HTML Practice 2</title>
    </head>
    <body>
    <h1>This text will be inside the heading
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

:::

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/BasicPageStructure/CreateFirstHtmlDocumentTest.html]

Write an HTML document that uses the elements `<h1>` and `<p>` to display the text `Travel Goals` and `New York, Paris, Singapore and Japan` in the browser window,following the text appearance as: <h1>Travel Goals</h1> <p>New York, Paris, Singapore and Japan</p>

```html

```