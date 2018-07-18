# Table Attributes

+++

### Part 1: Sample Code Analysis

:::

type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Attributes</title>
    </head>
    <body>
        <table width="300px" border="1" align="center">
            <thead>
                <caption>Student Records</caption>
                    <tr>
                        <th>FirstName</th>
                        <th>LastName</th>
                        <th colspan="3">Birthdate(m/d/yyyy)</th>
                    </tr>
            </thead>
        </table>
    </body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- <body><table width="300" border="1" align="center"><thead><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead></table></body>

- <body><table width="300" border="1" align="center"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead></table></body>

- <body><table width="300" align="center"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead></table></body>

- <body><table border="1" align="center"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead></table></body>

- <body><table width="300" border="1"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead></table></body>


/// type=SS, answer=[2]

Which of the following elements define the `table row` of the HTML table?

- `<th>`

- `<tr>`

- `<body>`

- `<table>`

- `<caption>`


/// type=SS, answer=[4]

On line 8, what is `<thead>` inside the `HTML table`?

- It creates a new row in the HTML table.

- It sets the table caption of the HTML table.

- It is used to group body content in an HTML table.

- It is used to group header content in an HTML table.

- It contains the value of the table data per cell of the HTML table.


/// type=SS, answer=[1]

Which of the following elements define the `table header` of the HTML table?

- `<th>`

- `<tr>`

- `<body>`

- `<table>`

- `<caption>`


/// type=SS, answer=[3]

What is the `table caption` in the HTML table?

- LastName

- FirstName

- Student Records

- Birthdate(m/d/yyyy)

- There is no `table caption` set.


/// type=MS, answer=[1,3,4]

What of the following attributes are used in the HTML table?

- `width`

- `height`

- `border`

- `colspan`

- `rowspan`


/// type=MS, answer=[1,2,4]

What are the inner elements of the `<thead>` element?

- `<th>FirstName</th>`

- `<th>LastName</th>`

- `<title>Table Attributes</title>`

- `<caption>Student Records</caption>`

- `<table width="300px" border="1" align="center">`


/// type=SS, answer=[5]

What is `colspan` inside the `<th colspan="3">Birthdate(m/d/yyyy)</th>` element?

- It is an attribute that sets the height of the table row.

- It is an attribute that sets the width of the table border.

- It is an attribute that sets the width of the table column.

- It is a table attribute that sets the number of rows it extends to and merge it as one row.

- It is table atttribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[2]

What is `border` inside the `<table width="300" border="1" align="center">` element?

- It is an attribute that sets the width of the table column.

- It is an attribute that puts thickness to the border of a table.

- It is an attribute that sets the position of a table or a content in a table.

- It is an attribute that sets the number of rows it extends to and merge it as one row.

- It is an attribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[3]

What is `align` inside the `<table width="300" border="1" align="center">` element?

- It is an attribute that sets the height of the table row.

- It is an attribute that sets the width of the table column.

- It is an attribute that sets the position of a table or a content in a table.

- It is an attribute that sets the number of rows it extends to and merge it as one row.

- It is an attribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[2]

What is `300px` inside the `<table width="300px" border="1" align="center">` element?

- It is an attribute value that sets the width of a row.

- It is an attribute value that sets the width of the table.

- It is an attribute value that sets the height of the table.

- It is an attribute value that sets the number of columns to merge as one.

- It is an attribute value that specifies the border thickness of the table.


:::

:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Attributes</title>
    </head>
    <body>
        <table width="300px" border="1" align="center">
            <thead>
                <caption>Student Records</caption>
                    <tr colspan="2">
                        <th></th>
                        <th>FirstName</th>
                        <th>LastName</th>
                        <th colspan="3">Birthdate(m/d/yyyy)</th>
                    </tr>
            </thead>
            <tbody>
                <tr height="50px" align="center">
                    <td rowspan="2">Grade 12</td>
                    <td>Shroud</td>
                    <td>Rowdy</td>
                    <td>02-10-1900</td>
                </tr>
                <tr height="50px" align="center">
                    <td>Chadd</td>
                    <td>Disrespect</td>
                    <td>07-24-18</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- <body><table width="300px" border="1" align="center"><thead><caption>Student Records</caption><tr colspan="2"><th></th><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><tbody><tr><td rowspan="2">Grade 12</td><td>Shroud</td><td>Rowdy</td><td>02-10-1900</td></tr><tr><td>Chadd</td><td>Disrespect</td><td>07-24-18</td></tr></tbody></table></body

- <body><table width="300px" border="1" align="center"><thead><caption>Student Records</caption><tr colspan="2"><th></th><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><tbody><tr height="50px" align="center"><td>Grade 12</td><td>Shroud</td><td>Rowdy</td><td>02-10-1900</td></tr><tr height="50px" align="center"><td>Chadd</td><td>Disrespect</td><td>07-24-18</td></tr></tbody></table></body

- <body><table width="300px" border="1" align="center"><thead><caption>Student Records</caption><tr colspan="2"><th></th><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><tbody><tr><td rowspan="2">Grade 12</td><td>Shroud</td><td>Rowdy</td><td>02-10-1900</td></tr><tr height="50px" align="center"><td>Chadd</td><td>Disrespect</td><td>07-24-18</td></tr></tbody></table></body

- <body><table><thead><caption>Student Records</caption><tr colspan="2"><th></th><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><tbody><tr height="50px" align="center"><td rowspan="2">Grade 12</td><td>Shroud</td><td>Rowdy</td><td>02-10-1900</td></tr><tr height="50px" align="center"><td>Chadd</td><td>Disrespect</td><td>07-24-18</td></tr></tbody></table></body

- <body><table width="300px" border="1" align="center"><thead><caption>Student Records</caption><tr colspan="2"><th></th><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><tbody><tr height="50px" align="center"><td rowspan="2">Grade 12</td><td>Shroud</td><td>Rowdy</td><td>02-10-1900</td></tr><tr height="50px" align="center"><td>Chadd</td><td>Disrespect</td><td>07-24-18</td></tr></tbody></table></body>

/// type=MS, answer=[1,2]

What are the inner elements of the `<tbody>` element?

- `<td>Shroud</td>`

- `<td>Chadd</td>`

- `<th>FirstName</th>`

- `<caption>Student Records</caption>`

- `<th colspan="3">Birthdate(m/d/yyyy)</th>`


/// type=MS, answer=[1,2,3]

Which of the following values are the `table data` of the HTML table?

- `Rowdy`

- `Shroud`

- `07-24-28`

- `LastName`

- `FirstName`


/// type=SS, answer=[5]

What value is in row 3 of column 2 in the `HTML table`?

- `Chadd`

- `Rowdy`

- `Shroud`

- `07-24-18`

- `Disrespect`


/// type=SS, answer=[1]

What is `height` inside the `<tr height="50px" align="center">` element?

- It is an attribute that sets the height of the table row.

- It is an attribute that sets the width of the table column.

- It is an attribute that sets the position of a table or its table data.

- It is an attribute that sets the number of rows it extends to and merge it as one row.

- It is an attribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[5]

What is `center` inside the `<tr height="50px" align="center">` element?

- It is an attribute value that sets the width of a row.

- It is an attribute value that sets the height of a table row.

- It is an attribute value that specifies the border thickness of a row.

- It is an attribute value that sets the number of rows to merge as one.

- It is an attribute value that sets the position or alignment of the contents in the table row.


/// type=SS, answer=[4]

What is `rowspan` inside the `<td rowspan="2">Grade 12</td>` element?

- It is an attribute that sets the height of the table column.

- It is an attribute that sets the width of the table column.

- It is an attribute that sets the width size of the table column.

- It is a table attribute that sets the number of rows it extends to and merge it as one row.

- It is table atttribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[4]

On line 20, what is `2` inside the `<td rowspan="2">Grade 12</td>` element?

- It is an attribute value that sets the width of a table row.

- It is an attribute value that sets the width of a table column.

- It is an attribute value that sets the height of a table column.

- It is an attribute value that sets the number of rows to extend and merge.

- It is an attribute value that specifies the thickness of a border in a table row.


:::

+++

+++

### Part 2: Knowledge Assessment


/// type=SS, answer=[5]

Which of the following statements describes what HTML table attributes are?

- These attributes are set to create a framework to the HTML table.

- These attributes are set to create a distinct feature to the HTML table.

- These attributes are used to define a specific naming convention to the HTML table.

- These attribute are used to improve the text appearance of the contents of an HTML table.

- These attributes are used to improve the layout of the HTML table and enhance the readability of its table data.


/// type=SS, answer=[1]

Which of the following attributes is used to set the border thickness of an HTML table?

- `border="1"`

- `colspan="2"`

- `rowspan="2"`

- `height="50px"`

- `width="50px"`


/// type=SS, answer=[3]

Which of the following is used to set the positioning or alignment of an HTML table or table data?

- `pos="center"`

- `align="center"`

- `position="center"`

- `align="centerAlign"`

- `alignment="centerAlign"`


/// type=SS, answer=[2]

Which of the following is used to set the number of rows it extends and merges the rows as one?

- `colspan`

- `rowspan`

- `rowmerge`

- `rowextends`

- `rowextender`


/// type=MS, answer=[1,3]

Which of the following table elements can the `rowspan` attribute be written in?

- `<th>`

- `<tr>`

- `<td>`

- `<table>`

- `<thead>`


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
        <table border: "1">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Author</th>
                    <th>Number of copies available<th>
                </tr>
            </thead>
        </table>
    </body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- <body><table border: "1"><caption>Books for rent record</caption><thead><th>Genre</th><th>Author</th><th>Number of copies available<th></thead></table></body>

- <body><table border: "1"><caption>Books for rent record</caption><thead><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available<th></thead></table></body>

- <body><table border: "1"><thead><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available<th></thead></table></body>

- <body><table border: "1"><caption>Books for rent record</caption><thead><th>Book title</th><th>Author</th><th>Number of copies available<th></thead></table></body>

- <body><table border: "1"><caption>Books for rent record</caption><thead><th>Book title</th><th>Genre</th><th>Author</th></thead></table></body>


/// type=SS, answer=[5]

What makes the `border` attribute unable to set a border in the `<table border: "1">` element?

- The value `1` is enclosed in double quotes `""`.

- The attribute name is written first before the value. 

- The value `1` is not a valid value for the attribute `border`.

- The attribute `border: "1"` is written inside the `<table>` element.

- The attribute name `border` and its value `1` are separated with a colon `:`.

:::

/// type=CR, answer=[tests/TableAttributes/InvalidCharacterSeparatorTest.html]

Correct the HTML code to have a border around the table using the `<table>` element.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table border: "1">
            <caption>Books for rent record</caption>
            <thead>
                <th>Book title</th>
                <th>Genre</th>
                <th>Author</th>
                <th>Number of copies available<th>
            </thead>
        </table>
    </body>
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
        <table border="1">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Author</th>
                    <th>Number of copies available<th>
                </tr>
            </thead>
            <tbody>
                <tr align="50px">
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>Sidney Sheldon</td>
                    <td>4</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

/// type=SS, answer=[1]

Execute the program. What is its output?

-  <body><table border="1"><caption>Books for rent record</caption><thead><tr><th>Genre</th><th>Author</th><th>Number of copies available<th></tr></thead><tbody><tr align="50px"><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr></tbody></table></body>

- <body><table border="1"><thead><tr><th>Genre</th><th>Author</th><th>Number of copies available<th></tr></thead><tbody><tr align="50px"><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr></tbody></table></body>

- <body><table border="1"><caption>Books for rent record</caption><thead><tr><th>Genre</th><th>Number of copies available<th></tr></thead><tbody><tr align="50px"><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr></tbody></table></body>

- <body><table border="1"><caption>Books for rent record</caption><thead><tr><th>Genre</th><th>Author</th><th>Number of copies available<th></tr></thead><tbody><tr align="50px"><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td></tr></tbody></table></body>

- <body><table><caption>Books for rent record</caption><thead><tr><th>Genre</th><th>Author</th><th>Number of copies available<th></tr></thead><tbody><tr align="50px"><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr></tbody></table></body>


/// type=SS, answer=[3]

What makes the attribute `align` unable to set at the center of the table in the `<tr align="50px">` element?

- The attribute name is written first before the value.

- The element name is written first before the attribute.

- The value `50px` is not a valid value for the attribute `align`.

- The attribute `align="50px"` is written inside the `<tr>` element.

- The attribute name `align` and its value `50px` are separated with double qoutes `""`.

:::

/// type=CR, answer=[tests/TableAttributes/InvalidAttributeValueTest.html]

Correct the HTML code to have the element `<tr align="50px">` set at the center of the table.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table border="1">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Author</th>
                    <th>Number of copies available<th>
                </tr>
            </thead>
            <tbody>
                <tr align="50px">
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>Sidney Sheldon</td>
                    <td>4</td>
                </tr>
            </tbody>
        </table>
    </body>
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
        <table widthsize="500px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Author</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>Sidney Sheldon</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Witch and Wizard</td>
                    <td>Fiction, Fantasy</td>
                    <td>James Patterson</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <body><table widthsize="500px" align="center"><caption>Books for rent record</caption><thead><tr><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr><tr><td>Witch and Wizard</td><td>Fiction, Fantasy</td><td>James Patterson</td><td>2</td></tr></tbody></table></body>

- <body><table widthsize="500px"><caption>Books for rent record</caption><thead><tr><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr><tr><td>Witch and Wizard</td><td>Fiction, Fantasy</td><td>James Patterson</td><td>2</td></tr></tbody></table></body>

- <body><table widthsize="500px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr><tr><td>Witch and Wizard</td><td>Fiction, Fantasy</td><td>James Patterson</td><td>2</td></tr></tbody></table></body>

- <body><table widthsize="500px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Book title</th><th>Genre</th><th>Author</th><th>Number of copies available</th></tr></thead><tbody><tr><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr><tr><td>Witch and Wizard</td><td>Fiction, Fantasy</td><td>James Patterson</td><td>2</td></tr></tbody></table></body>

- <body><table widthsize="500px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>Sidney Sheldon</td><td>4</td></tr><tr><td>Witch and Wizard</td><td>Fiction, Fantasy</td><td>James Patterson</td><td>2</td></tr></tbody></table></body>


/// type=SS, answer=[3]

What makes the `<table widthsize="500px" border="1" align="center">` element unable to set the table width to `500px`?

- The value `500px` is enclosed in double quotes `""`.

- The attribute is written inside the `<table>` element.

- The attribute name `width` is miswritten as `widthsize`.

- The attribute name and value are separated with an equal `=`.

- The value `500px` is not a valid value for the attribute `widthsize`.


:::

/// type=CR, answer=[tests/TableAttributes/InvalidAttributeNameTest.html]

Correct the HTML code to set a width of `500px` in element `<table widthsize="500px" border="1" align="center">`.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table widthsize="500px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Author</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>Sidney Sheldon</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Witch and Wizard</td>
                    <td>Fiction, Fantasy</td>
                    <td>James Patterson</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
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
        <table width="600px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Author</th>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td colspan="2">Sidney Sheldon</td>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Nothing lasts forever</td>
                    <td>Fiction, Thriller</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <body><table width="600px" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td colspan="2">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table border="1"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td colspan="2">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td colspan="2">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody><tr><td colspan="2">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td colspan="2">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td></tr></tbody></table></body>


/// type=SS, answer=[5]

What makes the contents of the elements on lines 22-27 appear misaligned in the HTML table?

- There is no `</table>` closing tag.

- The `<td>` element is written inside the `<tr>` element.

- The `colspan` attribute is written inside the `<td>` element.

- The `align` attribute is written inside the `</table>` element.

- The attribute name used is `colspan` instead of `rowspan` to merge two rows in the table.


:::

/// type=CR, answer=[]

Correct the HTML code to have the `<td colspan="2">Sidney Sheldon</td>` element merge two rows in the table.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table width="600px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Author</th>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td colspan="2">Sidney Sheldon</td>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Nothing lasts forever</td>
                    <td>Fiction, Thriller</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
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
        <table width="600px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Author</th>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td rowspan="two">Sidney Sheldon</td>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Nothing lasts forever</td>
                    <td>Fiction, Thriller</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

/// type=SS, answer=[1]

Execute the program. What is its output?

- <body><table width="600px" border="1" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td rowspan="two">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td rowspan="two">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" align="center"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td rowspan="two">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" border="1"><caption>Books for rent record</caption><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td rowspan="two">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>

- <body><table width="600px" border="1" align="center"><thead><tr><th>Author</th><th>Book title</th><th>Genre</th><th>Number of copies available</th></tr></thead><tbody align="center"><tr><td rowspan="two">Sidney Sheldon</td><td>The dark side of midnight</td><td>Fiction, Thriller</td><td>4</td></tr><tr><td>Nothing lasts forever</td><td>Fiction, Thriller</td><td>2</td></tr></tbody></table></body>


/// type=SS, answer=[5]

Why are the contents appear misaligned in the second row of the HTML table?

- There is no `</tr>` closing tag.

- There is no `</table>` closing tag.

- The value `two` is enclosed in double qoutes `""`.

- The attribute `rowspan` is written inside the `<td>` element.

- The value `two` is not a valid value for the attribute `rowspan`.


:::

/// type=CR, answer=[tests/TableAttributes/InvalidAttributeValueTest.html]

Correct the html code to have the `<td rowspan="two">Sidney Sheldon</td>` element merge two rows in the table.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table width="600px" border="1" align="center">
            <caption>Books for rent record</caption>
            <thead>
                <tr>
                    <th>Author</th>
                    <th>Book title</th>
                    <th>Genre</th>
                    <th>Number of copies available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td rowspan="two">Sidney Sheldon</td>
                    <td>The dark side of midnight</td>
                    <td>Fiction, Thriller</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Nothing lasts forever</td>
                    <td>Fiction, Thriller</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/TableAttributes/CreateTableWithAttributesTest.html]

Write an HTML document to create an HTML table using the `<table>` element. Use the following elements in constructing the HTML table: `<caption>` for the table caption, `<th>` for the table header, `<tr>` for the table row, and `<td>` for the table data. Label the table caption as `Books for rent`. Add a new row for the table headers with values `Author`, `Book Title`, `Genre`, and `Number of copies available`. Create a new row for the table data with values `Sidney Sheldon`, `The dark side of midnight`, `Fiction, Thriller`, and `4`. Add another row for the table data with values `Sidney Sheldon`, `Nothing lasts forever`, `Fiction, Thriller`, and `2`. Merge the rows with the same author name using the `<rowspan>` element and merge the rows with the same `Genre` using the `<rowspan>`. Group all table headers using the `<thead>` element and group all table data using the `<tbody>` element. Set the table border with `1` as the value. Set the alignment of the HTML table and its table data inside the `<tbody>` at the center of the page. Observe proper nesting. Execute the program to view the output. The output should appear as:

<!DOCTYPE html>
<html>
	<head>
		<title>Table Attributes</title>
	</head>
    <body>
        <table border=`1` align=`center`>
            <caption>Books for Rent</caption>
            <thead>
                <tr>
                    <th>Author</th>
                    <th>Book Title</th>
                    <th>Genre</th>
                    <th>Number of Copies Available</th>
                </tr>
            </thead>
            <tbody align="center">
                <tr>
                    <td rowspan="2">Sidney Sheldon</td>
                    <td>The dark side of midnight</td>
                    <td rowspan="2">Fiction, Thriller</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>Nothing lasts forever</td>
                    <td>2</td>
                </tr>
            </tbody>
            </thead>
        </table>
    </body>
</html>

```html

```

+++
