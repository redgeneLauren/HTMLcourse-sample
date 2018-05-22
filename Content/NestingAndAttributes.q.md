# Nesting and Attributes

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


/// type=MS, answer=[2,4,5]

Which of the following elements are on level 3?

- `<head></head>`

- `<title>Sample Code Analysis 1</title>`

-  `<body></body>` 

- `<h1>Nesting</h1>`

- `<p>Proper Nesting Lesson</p>`


/// type=SS , answer=[2]

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

/// type=SS, answer=[]

Execute the program. What is its output?

- Nesting

- Nesting <p>Proper Nesting Lesson</p>

- <p>Proper Nesting Lesson</p>  Nesting 

- <p>Proper Nesting Lesson</p>
    
- <h1>Nesting</h1> <p>Proper Nesting Lesson</p>


/// type=MS, answer=[4,5]

Which of the following statements tell what is incorrect with the HTML code above?

- The text `Nesting` is not enclosed in any tags. 

- The element `<head></head>` is aligned incorrectly.

- The element `<body></body>` is aligned incorrectly.

- The `<title>Nesting</title>` element is aligned incorrectly.

- The `<p>Proper Nesting Lesson</p>` element is aligned incorrectly.

+++

+++

### Part 2: Knowledge Assessment

/// type=SS , answer=[5]

Which of the following statemebts best define nested elements?

- It reflects the logical structure. 

- An element should match other HTML elements.

- An HTML elements ends with another HTML element. 

- HTML elements and other HTML elements are connected as one. 

- HTML elements that are contained within other HTML elements.


/// type= MS, answer=[1,4,5]

Which of the following statements best explains the importance of nesting, indentation and alignment in writing an HTML code?

- It enhances the readability of the code.

- It can create lesser less chaos to the programmer.

- It can prevent harm to the editor in writing HTML code. 

- It may improve the rendering of the HTML code once executed.

- It will avoid affecting the visual appearance of the webpage.

