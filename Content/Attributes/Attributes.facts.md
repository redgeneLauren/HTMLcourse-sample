### Facts for Attributes

1. Attributes

    - In HTML, all HTML elements can contain `attributes` which defines the characteristics or property of an HTML `element`. 

    - Attributes are placed inside the opening tag `<>` of an HTML element. 

    - Attributes are made up of two parts: `name` and `value` which are seperated by an `=` equal sign.
 
    - The attribute `name` is the `property` to set and the attribute `value` is the `value of the property` to be set.

    - Attribute `value` should be placed inside double quotes `“ ”` . 

    - Attribute `name` and attribute `value` are written in lowercase. 

    - The code below shows how attributes are written in an HTML code.  

Code:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Lesson3: Attributes</title>
    </head>
    <body>
        <h1 title="lesson 3">HTML Attributes</h1>
        <p id="paragraph1"; style="color: red; font-family: courier">Paragraph with Attributes</p>
    </body>
</html> 

```

- The attribute `name` are `title`, `id` and `style`. 

- The attribute `value` are `Lesson 3` for `title`, `paragraph1` for `id` and `color: red`, `font-family: courier` for `style`.

- Different `attribute name` have different `values`. Most attribute `values` are `pre-defined` or follow a stipulated format.  

2. Core Attributes

    - There are common attributes that are used in most of the HTML elements. These common attributes comprise the `core attributes`.

    - The four core attributes in HTML are `class`, `title`, `id` and `style`. 

    - The `class` attribute assigns an HTML element for use with cascading style sheet. This attribute is commonly used in cascading style sheet (CSS), which will not be used in this lesson.

    - The code below shows other `core attributes` being used.

Code: 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Lesson3: Attributes</title>
    </head>
    <body>
        <h1 title="lesson 3">HTML Attributes</h1>
        <p id="paragraph1"; style="color: red; font-family: courier">Paragraph with Attributes</p>
    </body>
</html> 

```

Output:
<!DOCTYPE html>
<html>
    <head>
        <title>Lesson3: Attributes</title>
    </head>
    <body>
        <h1 title="lesson 3">HTML Attributes</h1>
        <p id="paragraph1"; style="color: red; font-family: courier">Paragraph with Attributes</p>
    </body>
</html> 

 - `id` - it is a unique identifier to name an HTML element. The value `paragraph1` inside the double quotes `" "` names the unique identifier name to the element `<p></p>`. 

- `title` - this is often used as a display tooltip when the cursor hovers over the element. When the cursor hovers over the text `HTML attributes` the value set inside the double quotes `" "` will appear in the display tooltip as `lesson 3`. 

- `style` - this is the attribute that allows cascading style sheet rules to be written inside an element. This attribute is refered to as an `inline style` in html.

Code:
```html
<p style="color: red; font-family: courier">Paragraph with Attributes</p>
```
- The `value` of the `style` attribute is written as a CSS property value pair: `style="property: value"`. Each property value are seperated by a `:` colon. 

- `"color: red; font-family: courier"` -  these are the `CSS property value pairs` from the `style` attribute. Each `pair` are seperated by a `;` semi-colon. 










