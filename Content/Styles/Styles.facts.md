### Facts for HTML Styles

1. Style 

    - `HTML styles` is one of the attributes used in HTML. The HTML style adds style to HTML elements.

    - In most HTML attributes, attributes appear as `name-value pairs` separated by an equal sign `=` and are written within the opening tag `<>` of an element, after the element's name.

    Code:
    ```html
    <p style="color: red">Paragraph with an attribute style</p>

    ```
    - The `attribute name` is `style` and the `attribute value` for style is `color: red`

    - The `style` attribute allows cascading style sheet `(CSS)` rules to be written inside an element and when `CSS` is written inside of an HTML tag using the style attribute, it's called an `inline style`. 

    - The `inline style` directly affects the tag they are written in. 

Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Styles</title>
    </head>
    <body>
        <p style="color: red; font-family: courier; text-align: center; text-size: 20px">Paragraph with an attribute style</p> 
    </body>
</html>

```
Output:
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Styles</title>
    </head>
    <body>
        <p style="color: red; background-color: white; font-family: courier; text-align: center; font-size: 20px">Paragraph with an attribute style</p> 
    </body>
</html>

- The `value` of the `style` attribute is written as a CSS property value pair: `property: value`. Each CSS `property value pair` are seperated by a `:` colon. 

- The CSS property value pairs from the style attribute are as follows:

    - `color: red` - The color property is used to define the text color.

    - `background-color: white` - The background color property is used to define background color for the HTML tag.

    - ` font-family: courier` - The font-family property specifies the font family of the HTML tag.

    - `font-size: 20px` - The font-size property is used to define the text size of the HTML tag.

    - `text-align: center` - The text-align property is used to define the horizontal text alignment of the HTML element.

- Each `pair` of the property values are seperated by a `;` semi-colon. 




     

   