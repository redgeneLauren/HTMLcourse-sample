# HTML Styles

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Styles</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1>
        <h3 id="h_2" title="author" style="text-align: center"> by HENRY DAVID THOREAU</h3> 
        <p id="p_1" style="font-family: courier; font-size: 20px; text-align: center">My life has been the poem I would have writ</p>
        <p id="p_2" style="font-family: courier; font-size: 20px; text-align: center; background-color: red">But I could not both live and utter it.</p>
    <body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <h1 style="color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1><h3 style="center"> by HENRY DAVID THOREAU</h3><p style="font-family: courier">My life has been the poem I would have writ</p><p style="font-family: courier; background-color: red">But I could not both live and utter it.</p>

- <h1 style="text-align: center"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1><h3 style="text-align: center"> by HENRY DAVID THOREAU</h3><p style="font-family: courier; text-align: center">My life has been the poem I would have writ</p><p style="font-family: courier; text-align: center; background-color: red">But I could not both live and utter it.</p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1><h3 id="h_2" title="author" style="text-align: center"> by HENRY DAVID THOREAU</h3> <p id="p_1"style="font-family: courier; font-size: 20px; text-align: center">My life has been the poem I would have writ</p><p id="p_2" style="font-family: courier; font-size: 20px; text-align: center; background-color: red">But I could not both live and utter it.</p>

- <h1 style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1><h3 style="text-align: center"> by HENRY DAVID THOREAU</h3> <p style="font-family: courier; text-align: center">My life has been the poem I would have writ</p><p style="font-family: courier; text-align: center">But I could not both live and utter it.</p>

- <h1 style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1><h3 style="text-align: center"> by HENRY DAVID THOREAU</h3> <p style="font-family: courier; text-align: center">My life has been the poem I would have writ</p><p style="font-family: courier; text-align: center; background-color: blue">But I could not both live and utter it.</p>


/// type=SS, answer=[2]

What type of tag is `<title>`?

- An ending tag.

- An opening tag.

- A beginning tag.

- A closing tag.

- A starting tag.


/// type=SS, answer=[5]

On line 8, what does the HTML element `<h3 id="h_2" title="author" style="text-align: center"> by HENRY DAVID THOREAU</h3> ` represent?

- The text element.

- The content element.

- The paragraph element.

- The thought element.

- The subheading element.


/// type=SS, answer=[4]

Which of the following text will be on the browser tab?

- “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”

- But I could not both live and utter it.

- by HENRY DAVID

- HTML Style

- My life has been the poem I would have writ


/// type=MS, answer=[1,2,4,5]

Which of the following elements are inside the `<body>` tag?

- `<h1 style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1>`
        
- `<h3 style="text-align: center"> by HENRY DAVID THOREAU</h3>`

- `<title>HTML Styles</title>`
        
- `<p style="font-family: courier; text-align: center">My life has been the poem I would have writ</p>`
        
- `<p style="font-family: courier; text-align: center; background-color: red">But I could not both live and utter it.</p>`


/// type=SS, answer=[3]

Which of the following element is an inner element of the `<head>` element?

- `<h1 style="text-align: center; color: green"> “MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT”</h1>`
        
- `<h3 style="text-align: center"> by HENRY DAVID THOREAU</h3>`

- `<title>HTML Styles</title>`
        
- `<p style="font-family: courier; text-align: center">My life has been the poem I would have writ</p>`
        
- `<p style="font-family: courier; text-align: center; background-color: red">But I could not both live and utter it.</p>`


/// type=SS, answer=[5]

On line 8, what `css property value pair` is used in the HTML element?

- `color: red`

- `background-color: white`

- `font-size: 20px`

- `font-family: courier`

- `text-align: center`


/// type=SS, answer=[4]

What is `"font-family: courier; font-size: 20px; text-align: center"` inside the element `<p id="p_1" style="font-family: courier; font-size: 20px; text-align: center">My life has been the poem I would have writ</p>` ?

- It is the style attribute.

- It is the paragraph value tool. 

- It is an element label for paragraph.

- It is css property value of the style attribute.

- It is the description for the paragraph element.


/// type=SS, answer=[2]

On line 9, what is `font-size` in the style attribute?

- It is a css value.

- It is a css property.

- It is an element label for paragraph.

- It is property value of the style attribute.

- It is the description for the paragraph element.


/// type=SS, answer=[1]

On line 9, what is `20px` in the style attribute?

- It is a css value.

- It is a css property.

- It is the paragraph value tool. 

- It is property value of the style attribute.

- It is the description for the paragraph element.


/// type=MS, answer=[2,4]

On line 10, what attributes are used in the HTML element?

- title 

- id

- class

- style

- label


/// type=SS, answer=[3]

On line 9, the `css property pair values` of the attribute `style` are seperated by what character?

- A period `.` .

- A comma `,` .

- A semicolon `;` .

- A colon `:` .

- A plus `+` .


/// type=SS, answer=[4]

On line 7, the `color` property and the `green` value in `style` attribute are separated by what character?

- A period `.` .

- A comma `,` .

- A semicolon `;` .

- A colon `:` .

- A plus `+` .


/// type=MS, answer=[3,4,5]

On line 10, what `css property value pairs` are used in the `style` attribute?

- color: orange

- align: center

- font-family: courier

- text-align: center

- background-color: red


/// type=SS, answer=[3]

On line 7, which of the following attribute sets the text alignment and font color of the HTML element?

- styles

- label

- style

- title

- id


:::

+++

+++

### Part 2: Knowledge Assessment

/// type=SS, answer=[3]

How are HTML attributes written?

- `label-property`

- `class-name`

- `name-value`

- `property-value`

- `name-type`

- `property-type`


/// type=SS, answer=[5]

What is a style attribute?

- It is used as a display tool tip.

- It provides a way in classifying similar elements.

- It provides a unique identifier to name an HTML element.

- It indicates the browser with the style direction of the element.

- It allows cascading style sheet rules to be written in an HTML element.


/// type=SS, answer=[5]

What is an `inline style`?

- It uses an external CSS file.

- It defines a style for different types of elements. 

- It is used to define a style for a single HTML page.

- It uses the `<style>` element in the `<head>` section.

- It uses CSS rules written in the HTML attribute `style`.


/// type=SS, answer=[3]

How are `values` of the `style` attribute written?

- `type: value`

- `type: property`

- `property: value`

- `property: type`

- `value: type`


/// type=SS, answer=[5]

Which of the following `css property value` defines the horizontal text alignment of the HTML element?

- `color: `

- `background-color: `

- `font-family: `

- `font-size: `

- `text-align: `


/// type=SS, answer=[1]

Which of the following `css property value` defines the color property of the `style` attribute?

- `color: `

- `text-color: `

- `font-color: `

- `set-color: `

- `content-color: `


/// type=SS, answer=[3]

Which of the following `css property value` defines the font property of the `style` attribute?

- `font-type:`

- `font:`

- `font-family`

- `font-property`

- `font-style`

- `fontstyle`


/// type=MS, answer=[2,4]

Which of the following are `css property value` of the `style` attribute?

- `font-color`

- `background-color`

- `text-size`

- `text-align`

- `text-family`


/// type=SS, answer=[2]

What character seperates each type of `css property value pair`?

- A colon `:`

- A semicolon `;`

- An asterisk `*`

- An exclamation `!`

- A period `.`


/// type=SS, answer=[1]

What character seperates the `property name` and `value` of the `style` attribute?

- A colon `:`

- A semicolon `;`

- An asterisk `*`

- An exclamation `!`

- A period `.`

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
        <h1 styles="text-align:center">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1 styles="text-align:center">I'm tired being a zero vector</h1><h2>Author: Eileen Tupas</h2><p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

-  <h1>I'm tired being a zero vector</h1><h2>Author: Eileen Tupas</h2><p>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

-  <h1 style="text-align:center">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 styles="text-align:center">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 styles="text-align:center">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>


/// type=SS, answer=[3]

What makes the main heading `Im tired being a vector` unable to set at the center of the page?

- There is no opening tag for `<styles>`

- There is no closing tag for `</styles>`. 

- The attribute name `styles` is incorrect.

- The property value for `styles` attribute is incorrect.

- The property value should be separated by a semicolon `;`.

:::

/// type=CR, answer=[tests/Styles/IncorrectAttributeNameTest.html]

Correct the HTML code to make the main heading `Im tired being a vector` be displayed at the center of the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 styles="text-align:center">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2>Author: Eileen Tupas</h2><p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2>
      
- <h1 style="text-align: center">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>


/// type=SS, answer=[3]

What makes `property value pairs` of the `style` attribute unable to make any changes to the content of the element `<p style=text-align: center; font-family: courier>`?

- The element name is incorrect. 

- The element to use should be `<style></style>`

- The property value pairs are not enclosed in double quotes `""`.

- The property value and element name should be separated by a colon `:`.

- There is no opening tag `<style>` declared for the property value pairs.

:::

/// type=CR, answer=[tests/Styles/ErrorInPropertyValueDeclarationTest.html]

Correct the HTML code to have the `property value pairs` of the `style attribute` be used in the element `<p style=text-align: center; font-family: courier>`.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style=text-align: center; font-family: courier>i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center; font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

-  <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

-  <h1 style="background-color: red">I'm tired being a zero vector</h1><h2>Author: Eileen Tupas</h2><p style="text-align: center; font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

-  <h1 style="text-align: center">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-align: center; font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="text-align: center; font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

-  <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="text-align: center">Author: Eileen Tupas</h2><p style="font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>


/// type=SS, answer=[2]

What makes the `value` of style property `text-size` unable to set 40px as font size in the element `<p style="text-align: center; font-family: courier; text-size: 40px">`?

- The property value `40px` should be enclosed in double quotes `""`

- The property name `text-size` of the `style` attribute is incorrect. 

- The property name `text-size`and value `40px` should be seperated by an equal sign `=`.

- The property name `text-size`and value `40px` should be seperated by an semicolon  `;`.

- There should be no space between the property name `text-size` and value `40px`.

:::

/// type=CR, answer=[tests/Styles/IncorrectPropertyNameTest.html]

Correct the HTML code to output the element `<p style="text-align: center; font-family: courier; text-size: 40px">` in 40px font size. 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center; font-family: courier; text-size: 40px">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center; font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```
/// type=SS, answer=[5]

Execute the program. What is its output?

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><p style="text-align: center; font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2><p style="font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center">I'm tired being a zero vector</h1><h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2><p style="text-align: center; font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>

- <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1><h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2><p style="text-align: center; font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>


/// type=SS, answer=[1]

What makes the style property value `font-color` unable to set the font color to blue in the element `<h2 style="font-color: blue; text-align: center">`?

- The property name `font-color` is incorrect.

- There should be no semicolon `;` after the value `blue`.

- The property value `blue` is an incorrect font-color value.

- The property name `font-color` should not be separated by a dash `-`.

- The property value pair `font-color: blue` should be separated by an equal sign `=`.

:::

/// type=CR, answer=[tests/Styles/IncorrectProperNameColorTest.html]

Correct the HTML code to output the element `<p style="text-align: center; font-family: courier; text-size: 40px">` in blue font color. 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <h1 style="text-align: center; background-color: red">I'm tired being a zero vector</h1>
        <h2 style="font-color: blue; text-align: center">Author: Eileen Tupas</h2>
        <p style="text-align: center; font-family: courier">i'm tired of being a zero vector with no direction,no dimensionand no magnitude; what i need is another element- but that would be a contradiction of my definition</p>
    </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/Styles/CreateInlineStylePracticeTest.html]

Write an HTML document with a title `Inline Style practice` using the tag `<title>`. Then, add a main heading with the text: `Programming Wisdon` using the tag `<h1>` with the following characteristics:  `background-color grey` and `text alignment center`. Next, add a subheading with the text: `@codewisdom` using the tag `<h3>` with the following characteristics: `text alignment center` and `font color red`. Lastly, output a paragraph with the text: `"Read other people's code and 'steal' the good parts. Even if you try to do things exactly like someone else, you'll fail, but in doing so create something that's truly your own." – Peter Cooper (invoking Roman Mars)` with the following characteristics: `font-family courier`, `font size 20px`, `font color green`,and  `text alignment center`. Observe proper HTML nesting. Execute the program to view the result.

```html

```