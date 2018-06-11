### Facts for Attributes

1. Attributes

    - In HTML, all HTML elements can contain `attributes` which defines the characteristics or property of an HTML `element`. 

    - HTML attributes appear as `name-value pairs` separated by an equal sign `=` and are written within the opening tag `<>` of an element, after the element's name.

    Code:

    ```html
    <p title="Tooltip">This is a paragraph </p>
    ```

    - The `title` is the `attribute name` of the `<p></p>` element. `"This is a tooltip"` is the `value` assigned to the `title attribute`.

    - The attribute `name` is the `property` to set and the attribute `value` is the `value of the property` to be set.

    - Attribute `value` are usually placed inside double quotes `“ ”` or single quotes `''`. However, not all attributes require quotation marks. 

    - The example code below shows how attributes are written in an HTML code.  

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

- The `attribute name` are `title`, `id` and `style`. 

- The `attribute value` are `lesson 3` for `title`, `paragraph1` for `id` and `color: red`, `font-family: courier` for `style`.

- Different `attribute name` have different `values`. Most attribute `values` are `pre-defined` or follow a stipulated format.  

2. Common Attributes

    There are common attributes that are used in most of the HTML elements. These common attributes are:

    - `id` - it provides a document-wide unique identifier to name or label an HTML element.
        
    - `class` - provides a way of classifying similar elements.
        
    - `style` -  a non-attributal code presentational properties to a particular element. This is the attribute that allows cascading style sheet rules to be written inside an element. This attribute is refered to as an `inline style`.

    - `title` - it is used to attach subtextual explanation to an element. This is often used as a display tooltip when the cursor hovers over the text.