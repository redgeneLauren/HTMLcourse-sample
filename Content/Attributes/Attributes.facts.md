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
        <h1 title="Lesson 3">HTML Attributes</h1>
        <p id="paragraph1"; style="color: red; font-family: courier">Paragraph with Attributes</p>
    </body>
</html> 

```

- The attribute `name` are `title`, `id` and `style`. 

- The attribute `value` are `Lesson 3`, `paragraph1` and `color: red`.

- Different `attribute name` have different `values`.
    
- Most attribute `values` are `pre-defined` or follow a stipulated format.  

2. Core Attributes

    - There are common attributes that are used in most of the HTML elements. These common attributes comprise the `core attributes`.

    - There are four core attributes in HTML the `class`, `title`, `id` and `style`. 

    - The `class` attribute associates an element to a stylesheet. This attribute is commonly used in cascading style sheet (CSS), which will not be used in this lesson.

    - The code below shows other `core attributes` being used.

Code: 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Lesson3: Attributes</title>
    </head>
    <body>
        <h1 title="Lesson 3">HTML Attributes</h1>
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
        <h1 title="Lesson 3">HTML Attributes</h1>
        <p id="paragraph1"; style="color: red; font-family: courier">Paragraph with Attributes</p>
    </body>
</html> 

 - `id` - it is a unique identifier to identify an HTML element. The value `paragraph1` inside the double quotes `" "` labels the unique identifier to the element `<p>`. 

- `title` - this is often used as a display tooltip when the cursor hovers around the element. When the cursor hovers over the text `HTML attributes` the value set inside the double quotes `" "` will appear in the display tooltip as `Lesson 3`. 

- `style` - this is the attribute that allows cascading style sheet rules to be written inside the element. The attribute value `color:red` and `font-family: courier` are a few CCS rules that can be used in the `style` attribute.








