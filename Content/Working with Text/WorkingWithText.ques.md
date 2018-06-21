# Working with Text

+++

### Part 1: Sample Code Analysis

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <p>On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>
    </body> 
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- On the 16th of October the lesson for Math is Exponential Logarithm such that the formula exdx = ex+ C will be used.

- <p>On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C2H4O2</p>

- <p>On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm such that the formula exdx = e<sup>x</sup> + C will be used.</p>

- <p>On the 16th of October the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

- <p>On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>


/// type=SS, answer=[4]

On line 2, what does the `<html>` tag indicate?

- The end of an HTML document.

- The information about the page. 

- The structure of a text document.

- The beginning of an HTML document.

- The content to display on the web page.


/// type=SS, answer=[5]

What does the HTML element `<p>On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>` represent?

- The `text` element.

- The `content` element.

- The `thought` element. 

- The `header` element.

- The `paragraph` element.


/// type=MS, answer=[2,3]

Which HTML formatting elements are used in the `<p>` element?

- `<p>`

- `<sup>`

- `<sub>`

- `<body>`

- `<smaller>`


/// type=SS, answer=[2]

On line 7, what is `<sup></sup>` in the `<p>` element?

- It is an element that defines a subscript text. 

- It is an element that defines a superscript text.

- It is an element that defines an inserted text or added text. 

- It is an element that defines the deleted text or removed text.

- It is an element that defines smaller text which makes characters appear to smaller.


/// type=SS, answer=[1]

On line 7, what is `<sub></sub>` in the `<p>` element?

- It is an element that defines subscript text. 

- It is an element that defines superscript text.

- It is an element that defines inserted text or added text. 

- It is an element that defines the deleted text or removed text.

- It is an element that defines smaller text which makes characters appear to smaller.


:::

/// type=REPL, readonly=true

```html
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <p>On the 16<sup>th</sup> of <del>October</del> <ins>November</ins> the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>
    </body> 
</html>

```
:::

/// type=SS, answer=[2]

Execute the program. What is its output?

- <p>On the 16<sup>th</sup> of <del>October</del> <ins>November</ins> the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C2H<sub>4</sub>O2</p>

- <p>On the 16<sup>th</sup> of <del>October</del> <ins>November</ins> the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

- <p>On the 16<sup>th</sup> of <ins>November</ins> the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

- <p>On the 16<sup>th</sup> of the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

- <p>On the 16th of <del>October</del> <ins>November</ins> the lesson for Math is Exponential Logarithm and in Science the lesson on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>


/// type=MS, answer=[2,3,4,5]

Which HTML formatting elements are used in the `<p>` element?

- `<p>`

- `<sup>`

- `<sub>`

- `<del>`

- `<ins>`


/// type=SS, answer=[4]

What is `<del></del>` in the `<p>` element?

- It is an element that defines the important text.

- It is an element that defines the emphasized text.

- it is an element that defines the inserted or added text.

- It is an element that defines the deleted or removed text. 

- It is an element that defines the marked or highlighted text.


/// type=SS, answer=[3]

What is `<ins></ins>` in the `<p>` element?

- It is an element that defines the important text.

- It is an element that defines the emphasized text.

- it is an element that defines the inserted or added text.

- It is an element that defines the deleted or removed text. 

- It is an element that defines the marked or highlighted text.

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>
        <p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p>
    <body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- <h1 id="h_1" title="PoemTitle">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center">by HENRY DAVID THOREAU</p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1"><i>by HENRY DAVID THOREAU</i></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>


/// type=SS, answer=[4]

On line 7, what does the `<h1>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It contains information about the page.

- It sets the largest and important heading.

- It specifies the content to display in the web page.


/// type=MS, answer=[1,2,4]

On lines 7 and 8, what attributes are used in the elements?

- `id`

- `style`

- `class`

- `title`

- `styles`


/// type=SS, answer=[3]

On line 7, what CSS `property: value` pair is used in the HTML element?

- `color: green`

- `font-size: 20px`

- `text-align: center`

- `font-family: Courier`

- `background-color: white`


/// type=SS, answer=[2]

What is `text-align` of the `style` attribute in the element `<h1>`?

- It is a css value.

- It is a css property.

- It is an element label for paragraph.

- It is property value of the style attribute.

- It is the description for the paragraph element.


/// type=SS, answer=[1]

What is `center` of the `style` attribute in the element `<h1>`?

- It is a css value.

- It is a css property.

- It is the paragraph value tool. 

- It is property value of the style attribute.

- It is the description for the paragraph element.


/// type=SS, answer=[1]

On line 8, which HTML formatting element is used in the `<p>` element?

- `<i></i>`

- `<em></em>`

- `<mark></mark>`

- `<strong></strong>`

- `<subscript></subscript>`


/// type=SS, answer=[1]

What is `<i></i>` in the `<p>` element?

- It is an element that defines the italic text. 

- It is an element that defines the important text.

- It is an element that defines the emphasized text.

- it is an element that defines the inserted or added text.

- It is an element that defines the marked or highlighted text.


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>
        <p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br />
        <p id="p_2" title="content2" style="text-align: center; color: green">My life has been the poem I would have writ
    <body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br /><p id="p_2" title="content">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br /><p id="p_2" title="content" style="text-align: center">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><p id="p_2" title="content" style="text-align: center; color: green"">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_2" title="content" style="text-align: center">My life has been the poem I would have writ


/// type=MS, anwer=[3,5]

On line 9, what attributes are used in the `<p>` element?

- `id="h_1"`

- `class id="p_2"`

- `title="content2"`

- `styles="text-align: center; color: green"`

- `style="text-align: center; color: green"`


/// type=SS, answer=[2]

On line 8, which HTML formatting element is used?

- `<br />`

- `<em></em>`

- `<i></i>`

- `<mark></mark>`

- `<strong></strong>`


/// type=SS, answer=[1]

On line 8, what empty element is used?

- `<br />`

- `<em></em>`

- `<i></i>`

- `<mark></mark>`

- `<strong></strong>`


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>
        <p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br />
        <p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ
    <body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- <h1 id="h_1" title="PoemTitle">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ


/// type=MS, answer=[2,4]

On line 8, which HTML formatting elements are used?

- `<br />`

- `<em></em>`

- `<i></i>`

- `<mark></mark>`

- `<strong></strong>`


/// type=SS, answer=[3]

What is `<mark></mark>` in the element `<p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br />`

- It is an element that renders a smaller font. 

- It is an element that defines an inserted text or added text.

- It is an element that defines the marked or highlighted text.

- It is an empty element that defines a line break in a paragraph.

- It is an empty element that draws horizontal line between text to separate content. 


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>
        <p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br />
        <p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ
    <body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green">My life has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</i></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><i>by HENRY DAVID THOREAU</i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ


/// type=SS, answer=[3]

On line 9, which HTML formatting element is used?

- `<br />`

- `<em></em>`

- `<b></b>`

- `<strong></strong>`

- `<subscript></subscript>`


/// type=SS, answer=[3]

What is `<b></b>` in the paragraph `<b>My life</b> has been the poem I would have writ`?

- It is an element defines an emphasized text.

- It is an element that defines an inserted text.

- It is an element that makes characters appear bolded.

- It is an element that makes characters appear to be highlighted. 

- It is an element that adds a semantic strong importance to the text. 


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1>
        <p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br />
        <p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ
    <body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark>by HENRY DAVID THOREAU</strong></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br /><p id="p_2" title="content"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center">by HENRY DAVID THOREAU</p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br />


/// type=MS, answer=[2,4,5]

On line 8, which HTML formatting elements are used?

- `<b>`

- `<i>`

- `<em>`

- `<mark>`

- `<strong>`


/// type=SS, answer=[5]

What is `<strong></strong>` in the element `<p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p>`?

- It is an element defines an emphasized text.

- It is an element that defines an inserted text.

- It is an element that makes characters appear bolded.

- It is an element that makes characters appear to be highlighted. 

- It is an element that adds a semantic strong importance to the text. 


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Text</title>
    </head>
    <body>
        <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><hr />
        <p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br />
        <p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ
        <p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But <small>I could not</small> <em>both live and utter it.</em></p>
    <body>
    <body>
</html>

```

/// type=SS, answer=[1]

Execute the program.  What is its output?

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><hr /><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ<p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But <small>I could not</small> <em>both live and utter it.</em></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ<p id="p_2">But I could not <em>both live and utter it.</em></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><mark><i>by HENRY DAVID THOREAU</mark></i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ<p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But I could not <em>both live and utter it.</em></p>

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark><i>by HENRY DAVID THOREAU</strong></mark></i></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ

- <h1 id="h_1" title="PoemTitle" style="text-align: center">MY LIFE HAS BEEN THE POEM I WOULD HAVE WRIT</h1><p id="p_1" title="content1" style="text-align: center"><strong><mark>by HENRY DAVID THOREAU</strong></mark></p><br /><p id="p_2" title="content" style="text-align: center; color: green"><b>My life</b> has been the poem I would have writ<p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But I could not <em>both live and utter it.</em></p>


/// type=MS, answer=[2,5]

On line 10, which HTML formatting element are used?

- `<i>`

- `<em>`

- `<b>`

- `<mark>`

- `<small>`


/// type=SS, answer=[1]

What is `<em></em>` in the element `p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But <small>I could not</small> <em>both live and utter it.</em></p>`

- It is an element defines an emphasized text.

- It is an element that defines an inserted text.

- It is an element that makes characters appear bolded.

- It is an element that makes characters appear to be highlighted. 

- It is an element that adds a semantic strong importance to the text. 


/// type=SS, answer=[5]

What is `<small></small>` in the element `p id="p_2" style="font-family: Courier; font-size: 20px; text-align: center">But <small>I could not</small> <em>both live and utter it.</em></p>`

- It is an element that defines subscript text. 

- It is an element that defines superscript text.

- It is an element that defines inserted text or added text. 

- It is an element that defines the deleted text or removed text.

- It is an element that defines smaller text which makes characters appear to smaller.


/// type=SS, answer=[3]

On line 7, what empty element is used?

- `<em>`

- `<br />`

- `<hr />`

- `<mark>`

- `<strong>`


:::

+++

+++

### Part 2: Knowledge Assessment

/// type=SS, answer=[5]

Which of the following statement best describe HTML formatting elements?

- These are empty elements that uses one tag.

- These elements are used to display images on the web page.

- These are elements that requires to be indented in an HTML code.

- These elements define as a title or subtitle to display on the page.

- These are inline elements that are used to format the appearance of an element. 


/// type=MS, answer=[1,2,5]

Which elements are HTML formatting elements?

- `<b>`

- `<i>`

- `<hr />`

- `<br />`

- `<strong>`


/// type=SS, answer=[4]

Which HTML formatting element defines an important text?

- `<i>`

- `<b>`

- `<em>`

- `<strong>`

- `<mark>`


/// type=SS, answer=[5]

Which HTML formatting element defines mark or highlighted text?

- `<i>`

- `<em>`

- `<sup>`

- `<hr />`

- `<mark>`


/// type=SS, answer=[5]

Which statement defines the HTML formatting element `<sub>`?

- It is an element that defines an italic text.

- It is an element that defines marked or highlighted text.

- It is an element that adds a semantic strong importance to the text. 

- It is an element that make characters appear half a character above the normal line.

- It is an element that make characters appear half a character below the normal line.


/// type=SS, answer=[4]

Which statement defines the HTML formatting elemen `<sup>`

- It is an element that defines an italic text.

- It is an element that defines marked or highlighted text.

- It is an element that adds a semantic strong importance to the text. 

- It is an element that make characters appear half a character above the normal line.

- It is an element that make characters appear half a character below the normal line.


/// type=SS, answer=[5]

Which of the following HTML formatting element defines a semantic strong importance to the text?

- `<b>`

- `<i>`

- `<em>`

- `<sub>`

- `<strong>`


/// type=SS, answer=[1]

Which of the following make characters appear to be deleted with a thin horizontal through the text?

- `<del>`

- `<rem>`

- `<delete>`

- `<remove>`

- `<erase>`


/// type=SS, answer=[4]

Which of the following make characters appear to be smaller than the other characters?

- `<s>`

- `<min>`

- `<shrink>`
 
- `<small>`

- `<minimize>`


/// type=SS, answer=[2]

Which of the following make characters appear to have an inserted text with a think horizontal line below the text.

- `<add>`

- `<ins>`

- `<insert>`

- `<inserted>`

- `<additional>`

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
        <p>On the 16<sup>th of <del>October</del> <ins>November</ins>
    <body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <p>On the 16<sup>th of <del>October</del> November

- <p>On the 16<sup>th of October<ins>November</ins>

- <p>On the 16th of <del>October</del> <ins>November</ins>

- <p>On the 16<sup>th of <del>October</del> <ins>November</ins>

-  On the 16th of October November


/// type=SS, answer=[5]

What makes the text `of October November` in the element ` <p>On the 16<sup>th of <del>October</del> <ins>November</ins>` appear to be superscript?

- The element name `sup` should be written as `superscript`.

- The element `<sup>` should be declared after the characters `th` on the text `16th`.

- There should be an opening tag `<sup>` after the characters `th` on the text `16th`

- There is no forward slash character `/` after the characters `th` on the text `16th`.

- There is no closing tag for the element `</sup>` after the characters `th` on the text `16th`.


:::

/// type=CR, answer=[tests/WorkingWithText/NoClosingTagTest.html]

Correct the HTML code to have the text `of October November` not appear as superscript.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <p>On the 16<sup>th of <del>October</del> <ins>November</ins>
    <body>
</html>

```

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
	<p>Working with Text using <mark>Formatting Elements<mark> in HTML<p>
    <body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <p>Working with Text using in HTML<p>

- <p><mark>Working with Text using <mark>Formatting Elements<mark> in HTML<p>

- <p>Working with Text using Formatting Elements in HTML<p>

- <p>Working with Text using <mark>Formatting Elements<mark> in HTML<p>

- <p>Working with <mark>Text using Formatting Elements in HTML<p>


/// type=SS, answer=[2]

What makes the text `in HTML` appear highlighted in the element `<p>Working with Text using <mark>Formatting Elements<mark> in HTML<p>`

- The tag `<mark>` after the text `Elements` should be written as `<mark />`.

- The tag `<mark>` after the text `Elements` should be written as `</mark>`. 

- The tag `<mark>` after the text `Elements` should be written as `<\mark>`.

- The tag `<mark>` after the text `Elements` should be written as `<mark \>`.

- The tag `<mark>` after the text `Elements` should be written as `<!mark>`.

:::

/// type=CR, answer=[tests/WorkingWithText/NoClosingTagInTheElementTest.html]

Correct the HTML code to have the text `Formatting Elements` the only text to be marked or highlighted.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
	<p>Working with Text using <mark>Formatting Elements<mark> in HTML<p>
    <body>
</html>

``` 

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/WorkingWithText/CreateHTMLFormattingElementsDocumentTest.html]

Write an HTML document with the title: `Working with Text` using the element `<title>`. Then, add a heading with the text `Programming Wisdom` using the `<h1>` element. Next, add a paragraph with the text `"It is far better to improve the effectiveness of testing first than to improve the efficiency of poor testing. Automating chaos just gives faster chaos."` using the `<p>` element. In the first paragraph add formatting elements to the following: `emphasize` on the text `improve the effectiveness`, bold the text `first`, give strong importance to the text `poor testing` and italize the text `automatic chaos`. Lastly, add a second paragraph with the text `- Mark Fewster` using the `<p>` element . In the second paragraph add formatting element `small` to the text: - Mark Fewster. Observe proper nesting. Execute the program to view the output.

```html

```