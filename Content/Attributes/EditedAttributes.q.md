# Attributes

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3">Attributes</h1>
            <p id="p_1" style="color: blue">Welcome to HTML</p>
            <p id="p_2" style="color: orange">Basic learning with HTML attributes</p>
        </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="color: orange; font-family: courier">Basic learning with HTML attributes</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue; text-align: center">Welcome to HTML</p><p id="p_2" style="color: orange">Basic learning with HTML attributes</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="text-align: center; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="font-family: courier">Basic learning with HTML attributes</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue">Welcome to HTML</p><p id="p_2" style="color: orange">Basic learning with HTML attributes</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="color: orange; font-family: courier">Basic learning with HTML attributes</p>


/// type=SS, answer=[1]

What is `title="lesson 3"` inside the `<h1 title="lesson 3">Attributes</h1>` element?

- It is the title attribute.

- It is an element label.

- It is the heading tool. 

- It is the feature for the heading element.

- It is the description for the heading element.


/// type=SS, answer=[2]

What is `"color: orange; font-family: courier"` inside the element ` <p id="p_2" style="color: orange; font-family: courier">Basic learning with HTML attributes</p>` ?

- It is the style attribute.

- It is the paragraph value tool. 

- It is an element label for paragraph.

- It is property value of the style attribute.

- It is the description for the paragraph element.


/// type=SS, answer=[5]

What is `id="p_1"` inside the element ` <p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>` ?

- It is the set paragraph tool. 

- It is an element label for paragraph.

- It is the description tool for the paragraph element.

- It is the feature to set for the paragraph element.

- It is the id attribute to give a unique identity to the element.


/// type=SS, answer=[1]

What attribute is used on line 7?

- title

- id

- class

- style

- label


/// type=SS, answer=[3]

On line 7, what value is assigned to the attribute `title`?

- p_1

- p_2

- lesson 3

- color: orange

- font-family: courier


/// type=MS, answer=[2,4]

On line 8 and line 9, what attributes are used on the elements?

- title 

- id

- class

- style

- label


/// type=SS, answer=[3]

On line 9, the css property pair values of the attribute `style` are seperated by what character?

- A period `.` .

- A comma `,` .

- A semi colon`;` . 

- A colon `:` . 

- A plus `+` .


/// type=SS, answer=[4]

On line 8, the color property value in `style` attribute are separated by what character?

- A period `.` .

- A comma `,` .

- A semi colon`;` . 

- A colon `:` . 

- A plus `+` .


/// type=MS, answer=[1,3,4]

On line 8, what css property value pairs are used in the `style` attribute?

- color: blue

- align: center

- font-family: comic sans

- text-align: center

- font: comic sans


/// type=MS, answer=[1,3]

On line 9, what css property value pairs are used in the `style` attribute?

- `color: orange`

- `align: center`

- `font-family: courier`

- `text-align: center`

- `font: comic sans`


/// type=SS, answer=[1]

What display tool tip label will be displayed when the mouse cursor hovers over the text `Attributes`?

- The text `lesson 3`.

- The name `attribute`.

- Some text of HTML.

- The `label` of the attribute.

- Nothing will be displayed. 


/// type=SS, answer=[3]

Which of the following attribute initializes the font style , text alignment and font color on line 8?

- styles

- label

- style

- title

- id


/// type=SS, answer=[4]

Which of the following attribute sets the display tool tip label `Lesson 3` on line 7?

- inline style

- label

- style

- title

- id

:::

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style="font-size: 30px">Attributes</h1>
            <p id="p_2" style="color: orange; font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>
        </body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its ouput?

-<h1 title="lesson 3" style="font-size: 30px; text-align: center">Attributes</h1><p id="p_2" style="color: orange; font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>

- <h1 title="lesson 3" style="font-size: 30px">Attributes</h1><p id="p_2" style="color: orange; font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>

- <h1 title="lesson 3" style="font-size: 30px; text-align: center">Attributes</h1><p id="p_2" style="color: orange; font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>

- <h1 title="lesson 3" style="font-size: 30px; text-align: center">Attributes</h1><p id="p_2" style="font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>

- <h1 title="lesson 3" style="font-size: 30px; color: orange;">Attributes</h1><p id="p_2" style=" font-family: courier; font-size: 20px">Basic learning with HTML attributes</p>


/// type=SS, answer=[1,4]

What attributes are used on line 7?

- title 

- id

- class

- style

- label


/// type=MS, answer=[1,3,4]

On line 8, what css property value pairs are used in the `style` attribute?

- color: orange  

- font: courier

- font-size: 20px

- font-family: courier

- size: 20px

:::

+++

+++

### Part 2: Knowledge Assessment

/// type=SS, answer=[3]

Which statement best describe HTML attributes?

- Attributes are HTML elements. 

- Attributes draws HTML elements for modification.

- Attributes defines the characteristics of an HTML element. 

- Attributes tells the web browser how to structure it to display.

- Attributes are HTML elements that are contained within other HTML elements.


/// type=MS, answer=[2,3,5]

What are the different parts of an attribute?

- label

- name

- value

- property

- =


/// type=SS, answer=[4]

What are core attributes in HTML?

- These are the center of all attributes in HTML.

- Core attributes are the internalization attributes. 

- The behavior of an attribute that an HTML carries it.

- These are common attributes that are used in most HTML elements.

- Core attributes are the value of the property of an HTML element.


/// type=MS, answer=[1,3,4,5]

What are the different core attributes in HTML?

- class

- label

- type

- title

- id


/// type=SS, answer=[2]

What is an `id` attribute?

- This is often used as a display tool tip. 

- It is a unique identifier to name an HTML element.

- It assigns an HTML element for use with cascading style sheet.

- This attribute indicates the browser with the direction of the element.

- It is an attribute that allows cascading style sheet rules to be written in an HTML element. 


/// type=SS, answer=[5]

What is a `style` attribute?

- This is often used as a display tool tip. 

- It is a unique identifier to name an HTML element.

- It assigns an HTML element for use with cascading style sheet.

- This attribute indicates the browser with the direction of the element.

- It is an attribute that allows cascading style sheet rules to be written in an HTML element. 


/// type=SS, answer=[1]

What is a `title` attribute?

- This is often used as a display tool tip. 

- It is a unique identifier to name an HTML element.

- It assigns an HTML element for use with cascading style sheet.

- This attribute indicates the browser with the direction of the element.

- It is an attribute that allows cascading style sheet rules to be written in an HTML element. 


/// type=SS, answer=[3]

What is a `class` attribute?

- This is often used as a display tool tip. 

- It is a unique identifier to name an HTML element.

- It assigns an HTML element for use with cascading style sheet.

- This attribute indicates the browser with the direction of the element.

- It is an attribute that allows cascading style sheet rules to be written in an HTML element. 


/// type=SS, answer=[3]

Which of the following character should the attribute value be enclosed in?

- `&` ampersand

- `/` forward slash

- `" "` double quotes

- `?` question mark

- `*` asterisk


/// type=SS, answer=[4]

Where should an attribute be placed in an HTML element?

- Beside the closing tag `</>`.

- After the closing tag `</>`.

- After the opening tag `<>`.

- Inside the opening tag `<>`.

- Inside the closing tag `</>`.

+++

+++

### Part 3: Finding and Fixing Errors

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3">Attributes</h1>
            <p id="p_1" style="color: blue text-align: center font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>

- </h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: red;text-align: center;font-family: comic sans">Welcome to HTML</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue;font-family: comic sans">Welcome to HTML</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue text-align: center font-family: comic sans">Welcome to HTML</p>


/// type=SS, answer=[5]

Why is the attribute `style="color: blue text-align: center font-family: comic sans"` not applied to the text `Welcome to HTML`?

- The attribute name is incorrect.

- There is no css property value set on style.

- CSS property values should not be written inside the style attribute. 

- Each pair of the css property values should be seperated by a comma `,`.

- Each pair of the css property values should be seperated by a semi-colon `;`.

:::


/// type=CR, answer=[tests/Attributes/CorrectErrorTests1.html]

Correct the HTML code so that it outputs the text `Welcome to HTML` applying the `style` attribute.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3">Attributes</h1>
            <p id="p_1" style="color: blue text-align: center font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style="text-align: center">Attributes</h1>
            <id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>
            <p id="p_2" style="color: green">Learn how to use attributes/p>
        </body>
</html>

```
/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1 title="lesson 3">Attributes</h1><id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="color: green">Learn how to use attributes</p>

- <h1 title="lesson 3" style="text-align: center">Attributes</h1><id="p_1" style="color: blue; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="color: green">SLearn how to use attributes</p>

- <h1 title="lesson 3" style="text-align: center">Attributes</h1><id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>

- <h1 title="lesson 3" style="text-align: center">Attributes</h1><id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p><p id="p_2" style="color: green">Learn how to use attributes</p>

- <h1 title="lesson 3" style="text-align: center">Attributes</h1><id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p><p id="p_2">Learn how to use attributes</p>


/// type=MS, answer=[1,2]

Which of the following text should be aligned at the center of the page?

- The text `Attributes`.

- The text `Welcome to HTML`.

- The text `HTML attributes`.

- The text `Learn how to use attributes`.

- No text are set to align at the center.


/// type=SS, answer=[2]

What makes the text `Welcome to HTML` not aligned at the center of the page?

- There is no css property value `text-align: center`.

- The element lacks the opening element name `<p>`.

- Missing property value inside the `style attribute`.

- Missing colon character in the css property value for text-align.

- Missing semi-colon character between pairs of css property value.


/// type=SS, answer=[3]

What makes the text `Learn how to use attributes` of the element `<p id="p_2" style="color: green">Learn how to use attributes/p>` aligned at the center of the page?

- It lacks the opening tag for `<text-align>`

- It lacks the closing tag for `</text-align>`

- The element on line 8 lacks the opening element name `<p>`.

- The element on line 8 lacks the closing tag of style `</style>`.

- The element on line 8 lacks the closing tag of `</center>`

:::


/// type=CR, answer=[tests/Attributes/CorrectErrorTests2.html]

Correct the code above to output the text `Welcome to HTML` at the center of the page and the text `Learn how to use attributes` not aligned at the center of the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style="text-align: center">Attributes</h1>
            <id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>
            <p id="p_2" style="color: green">Learn how to use attributes/p>
        </body>
</html>

```


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style=text-align: right>Attributes</h1>
            <p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

-  <h1 title="lesson 3" style=text-align: right>Attributes</h1><p id="p_1" style="text-align: center; font-family: comic sans">Welcome to HTML</p>

-  <h1 title="lesson 3" style=text-align: right>Attributes</h1>

-  <p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>

-  <h1 title="lesson 3" style=text-align: right>Attributes</h1><p id="p_1" style="color: blue; font-family: comic sans">Welcome to HTML</p>

-  <h1 title="lesson 3" style=text-align: right>Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>


/// type=SS, answer=[5]

What makes the text `Attributes` of the element `<h1 title="lesson 3" style=text-align: right>Attributes</h1>` not appear on the right side of the page?

- It lacks the closing tag for `</text-align>`

- The element lacks the closing tag of style `</style>`.

- The css property values should be seperated by a semi-colon `;`

- CSS property values should not be written inside the style attribute. 

- The property value of `style` should be enclosed in double quotes `""`.

:::


/// type=CR, answer=[tests/Attributes/CorrectErrorTests3.html]

Correct the HTML code that outputs the heading text `Attributes` appear at the right side of the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style=text-align: right>Attributes</h1>
            <p id="p_1" style="color: blue; text-align: center; font-family: comic sans">Welcome to HTML</p>
        </body>
</html>

```


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style="text-align: right">Attributes</h1>
            <p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>
        </body>
</html>

```
/// type=SS, answer=[1]

Execute the program. What is its output?

-  <h1 title="lesson 3" style="text-align: right">Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>

- <h1 title="lesson 3">Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>

- <h1 title="lesson 3" style="text-align: right">Attributes</h1><p id="p_1" style="text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>

- <h1 style="text-align: right">Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>

- <h1 title="lesson 3" style="text-align: right">Attributes</h1><p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>


/// type=SS, answer=[5]

What makes the element `<p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p> ` not set the text `Welcome to HTML` to 20px in size?

- It lacks the closing tag for `</font-size>`

- The element lacks the closing tag of style `</style>`.

- The style attribute lacks the declaration of text size. 

- The css property values should be seperated by a semi-colon `;`

- The font-size property should be inside the enlosed double quotes `""` 

:::


/// type=CR, answer=[test/Attributes/CorrectErrorTests4.html]

Correct the HTML code to output the text `Welcome to HTML` in the right font size.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Attributes</title>
    </head>
        <body>
            <h1 title="lesson 3" style="text-align: right">Attributes</h1>
            <p id="p_1" style="color: blue; text-align: center; font-family: comic sans;" font-size: 20px>Welcome to HTML</p>
        </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/Attributes/CreateDocumentTest.html]

Write an HTML document with a title `Attributes Practice` using the element `<title></title>` with an attribute that sets the display tool tip label as `lesson 3`.  Then, output a heading text `Code Wisdom From Programming Wisdom` using the `<h1></h1>` element with attributes that sets the heading text at the center, font-size 30px, font-color green and font-family courier. Next, output a paragraph text `You might not think that programmers are artists, but programming is an extremely creative profession. It's logic-based creativity.” - John Romero`  with attributes that sets the paragraph text at the center, font-size 20px and font-family courier. Execute the program to view the result. 

```html

```