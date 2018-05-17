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

Execute the program. What is the output?

- Welcome to HTML
    <p>Lesson1: Basic Page structure of HTML</p>

- Welcome to HTML, Lesson1: Basic Page structure of HTML

- <h1>Welcome to HTML</h1>
    <p>Lesson1: Basic Page structure of HTML</p>

- <h1>Welcome to HTML</h1>

- <p>Lesson1: Basic Page structure of HTML</p>
    <h1>Welcome to HTML</h1>


What is the purpose of the `<!Doctype html>`?

- It serves as the comment section of HTML.

- It is the portal for saving files.

- It is the documentation of HTML.

- It defines the type of document.

- It does not have any purpose.


/// type=SS, answer=[2]

On line 2, what does the `<html>` tag indicate?

- It tells the browser how to structure a text document.

- The beginning of an HTML document.

- Specifies the content to display on the web page.

- The end of an HTML document.

- Contains information about the page. 


/// type=SS, answer=[4]

On line 10, what does the `</html>` tag indicate?

- Contains information about the page.

- Specifies the content to display on the web page.

- It tells the browser how to structure a text document.

- The end of an HTML document.

- The begining of an HTML document.


/// type=SS, answer=[2]

What type of tag is `<title>`?

- An ending tag.

- An opening tag.

- A beginning tag.

- A closing tag.

- A starting tag.


/// type=SS, answer=[3]

On line 7, what does the `<h1>` tag do?

- It specifies the content to display in the web page.

- It sets the title of the web page.

- It sets the heading of the document.

- It contains information about the page.

- It defines the document type.


/// type=SS, answer=[3]

What does `Line 8` of the code above represent?

- It represents the `text` element.

- It represents the `content` element.

- It represents the `paragraph` element.

- It represents the `thought` element. 

- It represents the `header` element.


/// type=SS, answer=[1]

On line 6, what does the `<body>` tag do?

- It specifies the content to display in the web page.

- It sets the title of the web page.

- It sets the heading of the document.

- It contains information about the page.

- It defines the document type.


/// type=SS, answer=[2]

Which of the following will information be seen on the browser tab?

- `<h1>Welcome to HTML<h1/>`

- `<title>HTML Basic Page Strucure</title>`

- `<p>Lesson: 1 Basic Page Structure of HTML</p>`

- `<!Doctype html>`

- No information will be seen in the browser tab.


/// type=SS, answer=[4]

What does `Line 7` of the code above represent?

- It represents the `title` element.

- It represents the `label` element.

- It represents the `paragraph` element.

- It represents the `header` element. 

- It represents the `identifier` element.


/// type=MS, answer=[2,4]

What tags are inside the `<body>` tag?

- `<h1></h1>`

- `<head></head>`

- `<title></title>`

- `<p></p>`

- `<html></html>`


/// type=MS, answer=[2,4,5]

Which statements correctly describe the output of the HTML code above?

- It does not show anything, just a blank page.

- It shows a small text `Lesson1: Basic Page structure of HTML`.

- The text is aligned at the center of the page.

- The title name in the browser tab is `HTML Page Structure`.

- It shows a larger and bolded text `Welcome to HTML`


/// type=SS, answer=[4]

What of the following appears the largest text in the web page?

- `<title>HTML Basic Page Structure</title>`

- `<h1>Welcome to HTML</h1>`

- `<p>Lesson1: Basic Page structure of HTML</p>`

- `<!Doctype html>`

- `<head></head>`


/// type=SS, answer=[3,4,5]

Which of the following are HTML elements?

- `<head>`

- `<!Doctype html>`

- `<h1>Welcome to HTML</h1>`

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

Which of the following is needed to construct a `HTML tag`?

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
    This text wil be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

type=SS, answer=[1]

Execute the program. What is the output?

-  This text wil be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>

- <h1>This text wil be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>
    
- <p>This text will be inside a paragraph.</p>
    <h1>This text wil be inside the heading</h1>

- <h1>This text wil be inside the heading</h1>

- <p>This text will be inside a paragraph.</p>


/// type=SS, answer=[2]

Why is the text `This text wil be inside the heading` not appear as a heading in the web page?

- The text `This text wil be inside the heading` should be inside the `<head>` tag.

- There is no `<h1>` open tag before text `This text wil be inside the heading` on line 7.

- There is no `<heading>` tag for the text `This text wil be inside the heading`.

- Missing `<body></body>` body tags in the HTML code.

- Missing `<headline>` tag in the HTML code.


/// type=CR, answer=[tests/BasicPageStructure/CorrectErrorTests.html]

Correct the HTML code so that it outputs the text `This text wil be inside the heading` as a heading in the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Practice</title>
    </head>
    <body>
    This text wil be inside the heading</h1>
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
    <h1>This text wil be inside the heading
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

type=SS, answer=[5]

Execute the program. What is the ouput?

- This text wil be inside the heading
    <p>This text will be inside a paragraph.</p>

- This text wil be inside the heading
    This text will be inside a paragraph.

-  <p>This text will be inside a paragraph.</p>
    <h1>This text wil be inside the heading
    
-  <h1>This text wil be inside the heading</h1>
    <p>This text will be inside a paragraph.</p>

-  <h1>This text wil be inside the heading
    <p>This text will be inside a paragraph.</p>


type=SS, answer=[5]

What makes the text `This text will be inside a paragraph` appear to be a header?

- There is no closing tag after `<body>` tag.

- The text `This text will be inside a paragraph` is inside the `<head>` tag.

- The text `This text will be inside a paragraph` is outside the `<body>` tag. 

- There is a bug inside the header tags.

- There is no `</h1>` closing tag after the text `This text will be inside the heading`


/// type=CR, answer=[tests/BasicPageStructure/CorrectErrorTests.html]

Correct the HTML code so that it outputs the text `This text will be inside the paragaph` appear not as a header.

```html
<!Doctype html>
<html>
    <head>
        <title>HTML Practice 2</title>
    </head>
    <body>
    <h1>This text wil be inside the heading
    <p>This text will be inside a paragraph.</p>
    </body>
</html>

```

:::

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/BasicPageStructure/CreateFirstHtmlDocumentTest.html]

Write an HTML document that outputs a heading(size 1): "Travel Goals".

Followed by a paragraph below the heading: "New York, Paris, Singapore and Japan." 

Run the HTML code to view the result.

```html

```



