# HTML Nesting 

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Sample Code Analysis 1</title>
    </head>
    <body>
        <h1>Nesting</h1>
        <p>Proper Nesting Lesson</p>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1>Nesting</h1>

- <p>Proper Nesting Lesson</p> <h1>Nesting</h1>

- <p>Proper Nesting Lesson</p>

- <h1>Nesting</h1> <p>Proper Nesting Lesson</p>
       
- <h1>Nesting <p>Proper Nesting Lesson</p>


/// type=SS, answer=[4]

On what level is the tag `<html>` in ?

- Level 4

- Level 2

- Level 3

- Level 1

- Level 6


/// type=SS, answer=[3]

On what level is the tag `</p>` in?

- Level 4

- Level 2

- Level 3

- Level 8

- Level 5


/// type=MS, answer=[3,4]

What level 2 elements are inside the `<htlml></html>`?

- `<title>Sample Code Analysis 1</title>`

- `<h1>Nesting</h1>`

- `<head><title>Sample Code Analysis 1</title></head>`

- `<body><h1>Nesting</h1> <p>Proper Nesting Lesson</p></body>`

- `<p>Proper Nesting Lesson</p>`


/// type=MS, answer=[1,2,5]

What level 3 elements are inside the `<html></html>` ?

- `<title>Sample Code Analysis 1</title>`

- `<h1>Nesting</h1>`

- `<head><title>Sample Code Analysis 1</title></head>`

- `<body><h1>Nesting</h1> <p>Proper Nesting Lesson</p></body>`

-  `<p>Proper Nesting Lesson</p>`


/// type=MS, answer=[2,4,5]

Which of the following elements are on level 3?

- `<head></head>`

- `<title>Sample Code Analysis 1</title>`

-  `<body></body>` 

- `<h1>Nesting</h1>`

- `<p>Proper Nesting Lesson</p>`


/// type=SS, answer=[2]

Which of the following is on the same level with the element `<head></head>`?

- `<title>Sample Code Analysis 1</title>`

- `<body></body>` 

- `<h1>Nesting</h1>`

- `<p>Proper Nesting Lesson</p>`

- `<html></html>`


/// type=SS, answer=[2]

On what level is the tag `</html>` in?

- Level 2

- Level 1

- Level 3

- Level 10

- Level 9

:::

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
    <title>Nesting</title>
    </head>
    <body>
    Nesting
    <p>Proper Nesting Lesson</p>
    </body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- Nesting

- Nesting <p>Proper Nesting Lesson</p>

- <p>Proper Nesting Lesson</p>  Nesting 

- <p>Proper Nesting Lesson</p>
    
- <h1>Nesting</h1> <p>Proper Nesting Lesson</p>


/// type=MS, answer=[1,4,5]

Which of the following statements tell what is incorrect with the HTML code above?

- The text `Nesting` is not enclosed in any tag. 

- The element `<head></head>` is nested incorrectly.

- The element `<body></body>` is nested incorrectly.

- The `<title>Nesting</title>` element is nested incorrectly.

- The `<p>Proper Nesting Lesson</p>` element is nested incorrectly.


/// type=MS, answer=[1,4]

What element should be indented to make the nesting of HTML code correct?

- `<title>Nesting</title>`

- `<head><title>Nesting</title></head>`

- `<body>Nesting<p>Proper Nesting Lesson</p></body>`

- `<p>Proper Nesting Lesson</p>`

- `<!DOCTYPE html>`


/// type=SS, answer=[3]

On what level is the element `<title>Nesting</title>` ?

- Level 1

- Level 2

- Level 3

- Level 4

- Level 5


/// type=SS, answer=[3]

On what level is the element `<p>Proper Nesting Lesson</p>`?

- Level 1

- Level 2

- Level 3

- Level 4

- Level 5


/// type=MS, answer=[1,4]

Which of the followng tags should the text `Nesting` from the code above be enclosed in?

- `<h1>`

- `<body>`

- `<content>`

- `<p>`

- `<heading>`

+++

+++

### Part 2: Knowledge Assessment

/// type=SS , answer=[4]

Which of the following statements best define what `nested elements` is?

- It reflects a logical structure. 

- An element matches other HTML elements.

- An HTML element ends with another HTML element. 

- HTML elements are contained within other HTML elements.

- HTML elements and other HTML elements are connected as one. 


/// type=MS, answer=[1,3,5]

Which of the following statements best explain the importance of nesting in writing an HTML code?

- It enhances the readability of the code.

- It can create less chaos to the programmer.

- It will improve in rendering the HTML code once executed.

- It can prevent problem to the editor in writing HTML code. 

- It avoids affecting the visual appearance of the webpage.


/// type=SS, answer=[3]

How can you differentiate between an element on level 1 and an element on level 2?

- All level 1 elements are indented. 

- Level 1 element are indented after the level 2 element.

- Level 2 element are indented after the level 1 element.

- Level 1 element are aligned to the center before the Level 2 element.

- Level 2 element are aligned to the center before the level 1 element. 


/// type=MS, answer=[2,3,4]

What is the importance of `indentation` in HTML nesting?

- It makes the HTML code looks nice.

- It is easy to see what tags are closed.

- It enhances the readability of the HTML code.

- It is easy to see where the code starts and ends. 

- It contributes to the great look to the HTML code. 


/// type=SS, answer=[3,4]

Which of the following statements is true about nesting an HTML code?

- Fusion of elements is essential to nesting.

- Nesting an HTML code will not render properly.

- Indentation should reflect a logical structure.

- Do not use unnecessary indentation and blank lines.

- Combination of different HTML elements is necessary to nesting. 


+++

+++

### Part 3: Finding and Fixing Errors

:::

/// type=REPL, readonly=true

```html
<!Doctype html>
<html>
    <head>
        <title>Finding and Fixing Errors 1</title>
    </head>
    <body>
        <h1>Heading of a text.<p>Paragraph of a text.</p></h1>
    </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- <h1>Heading of a text.</h1>

- <h1>Heading of a text.</h1> <p>Paragraph of a text.</p>

- <h1>Heading of a text.<p>Paragraph of a text.</p></h1>

- <p>Paragraph of a text.</p>

- <h1>Paragraph of a text.</h1>


/// type=SS, answer=[4]

Why is the text `Paragraph of a Text` appear as a heading?

- Missing `</header>` closing tag .

- Missing `<paragraph></paragraph>` tag.

- There is no closing tag `</p>` for paragraph.

- The element `<p>Paragraph of a text.</p>` is contained inside `<h1></h1>`.

- The element `<p>Paragraph of a text.</p>` is contained inside the `<head></head>`


/// type=SS, answer=[2]

Which of the following should the element `<p>Paragraph of a text.</p>` be contained in?

- `<head></head>`

- `<body></body>`

- `<h1></h1>`

- `<title></title>`

- `<header></header>`

:::

/// type=CR, answer=[tests/Nesting/CorrectErrorTests.html]

Correct the HTML code to make the text `Paragraph of a text.` not appear as a heading.

```html
<!Doctype html>
<html>
    <head>
        <title>Finding and Fixing Errors 1</title>
    </head>
    <body>
        <h1>Heading of text.<p>Paragraph of a text.</p></h1>
    </body>
</html>

```


:::

/// type=REPL, readonly=true

```html
<!Doctype html>
<html>
    <head>
        <title><body><h1>Heading of a text.</h1><p>Paragraph of a text.</p></body>Finding and Fixing Errors 1
        </title>
    </head>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its ouput?

- <h1>Heading of a text.</h1><p>Paragraph of a text.</p>Finding and Fixing Errors 1

- Finding and Fixing Errors 1

- <h1>Heading of a text.</h1><p>Paragraph of a text.</p>

- <title><body><h1>Heading of a text.</h1><p>Paragraph of a text.</p></body>Finding and Fixing Errors 1 </title>

- Paragraph of a text.


/// type=SS, answer=[2]

Why does the HTML code produces no output in the page?

- There is no `<paragraph>` tag.

- Missing closing tag `</body>`.

- There is no `<body>` tag written in the HTML code.

- There is no content written inside the `<body></body>` element.

- The element and contents of `<body></body>` are inside the `<title</title>` element. 


/// type=SS, answer=[2]

Which of the following should the element `<body><h1>Heading of a text.</h1><p>Paragraph of a text.</p></body` be placed?

- Below the closing tag `</title>`

- Below the closing tag `</head>`

- Beside the closing tag `</head>`

- Below the opening tag `<head>`

- Beside the opening tag `<head>`

:::


/// type=CR, answer=[tests/Nesting/CorrectErrorTests.html]

Correct the HTML code so that it produces an output on the page.

```html
<!Doctype html>
<html>
    <head>
        <title><body><h1>Heading of a text.</h1><p>Paragraph of a text.</p></body>Finding and Fixing Errors 1
        </title>
    </head>
</html>

```

+++

+++

### Part 4: Practice

Write an HTML document with a title: `Nesting Practice` using the element `<title></title>`. Then, output a paragraph of text: `“It’s not at all important to get it right the first time. It’s vitally important to get it right the last time.” - The Pragmatic Programmer - Andrew Hunt & David Thomas` using the element `<p></p>` and a heading of text: `From Programming Wisdom` using the element `<h1></h1>`. Observe proper HTML nesting. Execute the program to view the output. 

```html

```


