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

-  `<p>Proper Nesting Lesson</p>`


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

/// type=SS, answer=[2]

Execute the program. What is its output?

- Nesting

- Nesting <p>Proper Nesting Lesson</p>

- <p>Proper Nesting Lesson</p>  Nesting 

- <p>Proper Nesting Lesson</p>
    
- <h1>Nesting</h1> <p>Proper Nesting Lesson</p>


/// type=MS, answer=[4,5]

Which of the following statements tell what is incorrect with the HTML code above?

- The text `Nesting` is not enclosed in any tag. 

- The element `<head></head>` is nested incorrectly.

- The element `<body></body>` is nested incorrectly.

- The `<title>Nesting</title>` element is nested incorrectly.

- The `<p>Proper Nesting Lesson</p>` element is nested incorrectly.


/// type=MS, answer=[1,4]

What element should be indented to make the HTML code nesting correct?

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

Which of the followng tags will the text `Nesting` from the code above can be enclosed in?

- `<h1>`

- `<body>`

- `<content>`

- `<p>`

- `<heading>`

+++

+++

### Part 2: Knowledge Assessment

/// type=SS , answer=[5]

Which of the following statements best define what nested elements is?

- It reflects the logical structure. 

- An element should match other HTML elements.

- An HTML elements ends with another HTML element. 

- HTML elements and other HTML elements are connected as one. 

- HTML elements are contained within other HTML elements.


/// type=MS, answer=[1,4,5]

Which of the following statements best explains the importance of nesting in writing an HTML code?

- It enhances the readability of the code.

- It can create less chaos to the programmer.

- It can prevent problem to the editor in writing HTML code. 

- It will improve rendering of the HTML code once executed.

- It will avoid affecting the visual appearance of the webpage.


/// type=MS, answer=[2.3]

How can you differentiate an element on level 1 and an element on level 2?

- All level 1 elements are indented. 

- Level 1 elements are indented from level 2 elements.

- Level 2 elements are indented from level 1 elements.

- Level 1 are aligned to the center before the Level 2 elements.

- Level 2 are aligned to the center before the level 1 elements. 


/// type=SS, answer=[]

What is indentation in HTML nesting?

-

- Only indent elements base on its indentation level. 

- An element should match the right `level`. 

- Nesting requires all elements to be indented to the right.

- An element should 

+++

+++

### Part 3: Finding and Fixing Errors

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
<head>
    <title>Finding and Fixing Errors</title>
</head>
<body>
      <p>Fixing Nesting Errors</p>  
</body>
</html>

```

/// type=SS, answer=[]

Execute the program. What is its output?

-

-

-

-

-

:::

/// type=CR, answer=[]


+++

+++

### Part 4: Practice



