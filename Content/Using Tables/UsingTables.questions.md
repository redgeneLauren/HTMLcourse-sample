# Using Tables

+++

### Part 1: Sample Code Analysis

:::

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <caption>Grocery Items</caption>
            <tr>
                <th>Item Name</th>
                <th>Category</th>
                <th>Brand</th>
                <th>Quantity</th>
            </tr>
        </table>
    </body>   
</html>  

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th></tr></table>

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Brand</th><th>Quantity</th></tr></table>

- <table><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></table>

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></table>

- <caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr>


/// type=SS, answer=[5]

On line 6, what does the `<body>` tag do?

- It defines the document type.

- It sets the title of the web page.

- It sets the heading of the document.

- It contains information about the page.

- It defines the document's body to display on the web page.


/// type=SS, answer=[4]

Which of the following text will be on the browser tab?

- `Category`

- `Item Name`

- `Grocery Items`

- `Using HTML Tables`

- No text will be seen on the browser tab.


/// type=MS, answer=[1,2,3]

Which of the following elements are inside the `<body>` tag?

- `<th>Item Name</th>`

- `<th>Category</th>`

- `<title>Using HTML Tables</title>`

- `<caption>Preliminary Grades</caption>`

- `<head><title>Using HTML Tables</title></head>`


/// type=MS, answer=[2,3,4]

What are the inner elements of the `<tr>` element?

- `<table></table>`

- `<th>Brand</th>`

- `<th>Category</th>`

- `<th>Item Name</th>`

- `<caption>Grocery Items</caption>`


/// type=MS, answer=[1,5]

What are the inner elements of the `<table>` element?

- `<tr></tr>`

- `<th>Brand</th>`

- `<th>Category</th>`

- `<th>Item Name</th>`

- `<caption>Preliminary Grades</caption>`


/// type=SS, answer=[1]

On line 8, what is `<caption>` inside the `<table>` element?

- It is an element of the HTML table that sets the table caption.

- It is an element of the HTML table that creates the row of the table.

- It is an element of the HTML table that creates the header per column in the table.

- It is an element of the HTML table that is used to group header content in an  HTML table.

- It is an element of the HTML table that is used to group the body content in an HTML table.


/// type=SS, answer=[1]

Which of the following elements define the `table heading` of the HTML table?

- `<th>`

- `<tr>`

- `<head>`

- `<table>`

- `<caption>`


/// type=SS, answer=[2]

Which of the followng elements define the `table row` of the HTML table?

- `<th>`

- `<tr>`

- `<body>`

- `<table>`

- `<caption>`


/// type=MS, answer=[3,4,5]

Which of the following texts are the contents for the `table header` in the HTML table?

- `Name`

- `Item`

- `Brand`

- `Category`

- `Quantity`


/// type=SS, answer=[4]

What is the `table caption` of the HTML table?

- `Grocery`

- `Quantity`

- `Item Name`

- `Grocery Items`

- `Using HTML Tables`


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <caption>Grocery Items</caption>
            <tr>
                <th>Item Name</th>
                <th>Category</th>
                <th>Brand</th>
                <th>Quantity</th>
            </tr>
            <tr>
                <td>Soda</td>
                <td>Beverage</td>
                <td>Mountain Dew</td>
                <td>12</td>
            </tr>  
        </table>
    </body>   
</html>    

```

/// type=SS, answer=[5]

Execute the program. What is its output?

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Quantity</th></tr><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></table>

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr><tr><td>Soda</td><td>Beverage</td><td>Dew</td><td>12</td></tr></table>

- <table><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></table>

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td></tr></table>

- <table><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></table>


/// type=SS, answer=[1]

On line 15, what is `<tr>` inside the `<table>` element?

- It creates the row of the HTML table.

- It sets the table caption of the HTML table.

- It creates the header per column in the HTML table

- It is used to group footer content in an HTML table.

- It contains the table data per cell of the column of the HTML table.


/// type=MS, answer=[2,3]

Which of the following texts are the `table data` of HTML table?

- `Name`

- `Soda`

- `Beverage`

- `Category`

- `Quantity`


/// type=SS, answer=[1]

What tag is used to create `table data` in an `HTML table`?

- `<td>`

- `<tr>`

- `<caption>`

- `<table>`

- `<body>`


/// type=SS, answer=[2]

What `table data` is in row 1 of column 1 in the `HTML table`?

- `12`

- `Soda`

- `Category`

- `Quantity`

- `Item Name`

 
/// type=SS, answer=[5]

What `table data` is in row 2 of coloumn 2 in the `HTML table`?

- `12`

- `Soda`

- `Item Name`

- `Category`

- `Beverage`


/// type=SS, answer= [5]

Which data is under the header `Brand`?

- `12`

- `Soda`

- `Beverage`

- `Item Name`

- `Mountain Dew`


/// type=SS, answer=[2]

How many rows are there in the `HTML table`?

- 1

- 2

- 3

- 4

- 8


/// type=SS, answer=[4]

How many column are there in the `HTML table`?

- 1

- 2

- 3

- 4

- 8


/// type=SS, answer=[4]

How many `table data` are there in the HTML table?

- 1

- 2

- 3

- 4

- 8


/// type=SS, answer=[3]

What `table header` is the data `12` contained in?
- `Brand`

- `Category`

- `Quantity`

- `Item Name`

- `Grocery Item`


:::

/// type=REPL, readonly=true

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <thead>
                <caption>Grocery Items</caption>
                <tr>
                    <th>Item Name</th>
                    <th>Category</th>
                    <th>Brand</th>
                    <th>Quantity</th>s
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Soda</td>
                    <td>Beverage</td>
                    <td>Mountain Dew</td>
                    <td>12</td>
                </tr>
            </tbody>
        </table>
    </body>
</html> 

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <table><thead><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></thead><tbody><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td></tr></tbody></table>

- <table><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></thead><tbody><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></tbody></table>

- <table><thead><caption>Grocery Items</caption><tr><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></thead><tbody><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></tbody></table>

- <table><thead><caption>Grocery Items</caption><th>Item Name</th><th>Category</th><th>Brand</th><th>Quantity</th></thead><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></table>

- <table><thead><caption>Grocery Items</caption><tr><th> Name</th><th>Category</th><th>Brand</th><th>Quantity</th></tr></thead><tbody><tr><td>Soda</td><td>Beverage</td><td>Mountain Dew</td><td>12</td></tr></tbody></table>


/// type=SS, answer=[4]

On line 8, what is `<thead>` inside the `HTML table`?

- It creates a new row to the HTML table.

- It sets the table caption of the HTML table.

- It is used to group body content in an HTML table.

- It is used to group header content in an  HTML table.

- It contains the table data per cell of the column of the HTML table.


/// type=SS, answer=[5]

Which of the following element groups the body content of an `HTML table`?

- `<th>`

- `<tr>`

- `<td>`

- `<thead>`

- `<tbody>`


/// type=MS, answer=[1,3,5]

Which elements are the inner elements of `<tbody>` element?

- `<td>Soda</td>`

- `<th>Category</th>`

- `<td>Beverage</td>`

- `<th>Item Name</th>`

- `<td>Mountain Dew</td>`
                

/// type=MS, answer=[2,3]

Which elements are the inner elements of `<thead>` element?

- `<td>Soda</td>`

- `<th>Category</th>`

- `<td>Beverage</td>`

- `<th>Item Name</th>`

- `<td>Mountain Dew</td>`


//// type=SS, answer=[3]

Which of the following groups the header content of an `HTML table`?

- `<h>`

- `<th>`

- `<thead>`

- `<theader>`

- `<tablheader>`


/// type=SS, answer=[1,2,5]

What are the `table data` in the `<tbody>` element?

- `12`

- `Soda`

- `Brand`

- `Beverage`

- `Mountain Dew`


/// type=SS, answer=[3,5]

Which of the following are the `table headers` in the `<thead>` element?

- `12`

- `Soda`

- `Brand`

- `Beverage`

- `Quantity`


:::

+++

+++

### Part 2: Knowledge Assessment

/// type=SS, answer=[5]

Which statement best describe an `HTML table`?

- It defines the characteristics of an HTML element. 

- It is written on the same line with other elements.

- It can be used to construct more complex structure.

- It uses inline elements to format the appearance of an element. 

- It is used to manage layout of an HTML document and is displayed in a tabluar form. 


/// type=SS, answer=[5]

What is `table data` in an HTML table?

- It creates a row to the HTML table.

- It sets the table caption of the HTML table. 

- It creates the table header of the HTML table

- It is used to group footer content in an HTML table.

- It contains the table data per column cell of the HTML table.


/// type=MS, answer=[1,2,3,5]

What are the components to construct an HTML table?

- `<`

- `>`

- `/`

- `HTML table`

- `table`


/// type=SS, answer=[2]

Which of the following show how `table data` are written in an `HTML table`?

- `<tr>`

- `<td>`

- `<data>`

- `<tabledata>`

- `<datatable>`


/// type=SS, answer=[4]

What is a `<tbody>` element?

- It creates the table header of the HTML table.

- It is used to group footer content in an HTML table.

- It is used to group header content in an  HTML table.

- It is used to group the body content in an HTML table.

- It contains the table data per column cell of the HTML table.


/// type=SS, answer=[2]

What is `<tfooter>` element?

- It creates the table header of the HTML table.

- It is used to group footer content in an HTML table.

- It is used to group header content in an  HTML table.

- It is used to group the body content in an HTML table.

- It contains the table data per column cell of the HTML table.


/// type=SS, answer=[2]

Which of the following is used to create a `table row` in an `HTML table`? `

- `<td>`

- `<tr>`

- `<row>`

- `<tablerow>`

- `<rowtable>`


/// type=SS, answer=[2]

Which of the following is used to create a `table caption` in an `HTML table`?

- `<c>`

- `<caption>`

- `<tcaption>`

- `<title>`

- `<titletable>`


/// type=SS, answer=[3]

Which of the following show how `table header` are written in an `HTML table`?

- `<h1>`

- `<ht>`

- `<th>`

- `<header>`

- `<theading>`


/// type=SS, answer=[3]

Which of the following show how `table row` are written in an `HTML table`?

- `<r>`

- `<rt>`

- `<tr>`

- `<row>`

- `<trow>`


:::

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
        <table>
            <tr>
                <td>Loren</td>
                <td>Shroud</td>
                <td>24</td>
            </tr>
            <tr>
                <th>FirstName</th>
                <th>LastName</th>
                <th>Age</th>
            </tr>
        </table>
    </body>
</html>

```

/// type=SS, answer=[4]

Execute the program. What is its output?

- <table><tr><td>Loren</td><td>Shroud</td></tr><tr><th>FirstName</th><th>LastName</th><th>Age</th></tr></table>

- <table><tr><td>Shroud</td><td>24</td></tr><tr><th>FirstName</th><th>LastName</th><th>Age</th></tr></table>

- <table><tr><td>Loren</td><td>Shroud</td><td>24</td></tr><tr><th>FirstName</th><th>LastName</th></tr></table>

- <table><tr><td>Loren</td><td>Shroud</td><td>24</td></tr><tr><th>FirstName</th><th>LastName</th><th>Age</th></tr></table>

- <table><tr><td>Loren</td><td>Shroud</td><td>24</td></tr><tr><th>FirstName</th><th>LastName</th></tr></table>


/// type=SS, answer=[5]

What makes the `table header` appear on the second row not on the first row of the table?

- There is no closing tag for `</tr>`.

- There is no closing tag for `</table>`.

- There is no table row number declared in the table.

- There is no element `<tableheader>`  declared in the table.

- The elements `<td>` is written first before the elements `<th>`.  


:::


/// type=CR, answer=[tests/UsingTables/TableHeaderWrongRowTest.html]

Correct the HTML code to have the `table header` appear on the first row of the table.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table>
            <tr>
                <td>Loren</td>
                <td>Shroud</td>
                <td>24</td>
            </tr>
            <tr>
                <th>FirstName</th>
                <th>LastName</th>
                <th>Age</th>
            </tr>
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
        <table>
            <tr>
                <th>FirstName</th>
                <th>LastName</th>
                <th>Age</th>
                <td>Loren</td>
                <td>Shroud</td>
                <td>24</td>
            </tr>
        </table>
    </body>
</html>

```

/// type=SS, answer=[3]

Execute the program. What is its output?

- <table><tr><th>FirstName</th><th>LastName</th><td>Loren</td><td>Shroud</td><td>24</td></tr></table>

- <table><tr><th>FirstName</th><th>LastName</th><th>Age</th><td>Loren</td><td>Shroud</td></tr></table>

- <table><tr><th>FirstName</th><th>LastName</th><th>Age</th><td>Loren</td><td>Shroud</td><td>24</td></tr></table>

- <table><tr><th>FirstName</th><th>Age</th><td>Loren</td><td>Shroud</td><td>24</td></tr></table>

- <table><tr><th>LastName</th><th>Age</th><td>Loren</td><td>Shroud</td><td>24</td></tr></table>


/// type=SS, answer=[5]

What makes the `table data` be on the same row with the `table header`?

- There is no closing tag for `</table>`.

- There is no closing tag `</tr>` for the table row.

- There is no table row number declared in the table.

- The elements `<td>` is written first before the elements `<th>`.  

- The elements `<td>` are contained on the same `<tr>` tag with the `<tr>` elements.


:::


/// type=CR, answer=[tests/UsingTables/TableDataOnDiffTableRowTest.html]

Correct the HTML code to have the elements `<td>` appear on the second row of the table.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Finding and Fixing Errors</title>
    </head>
    <body>
        <table>
            <tr>
                <th>FirstName</th>
                <th>LastName</th>
                <th>Age</th>
                <td>Loren</td>
                <td>Shroud</td>
                <td>24</td>
            </tr>
        </table>
    </body>
</html>

```

+++

+++

### Part 4: Practice

/// type=CR, answer=[tests/UsingTables/CreateTablesTest.html]

Write an HTML document with the title `Using HTML Tables` using the `<title>` element. Then, create a table with `table headers` with the following labels: `Flight Number`, `Date of Departure`, `Time of Departure`,  `Date of Arrival`, `Time of Arrival`. Next, add `table data` corresponding to each `table header` with the following details: `F0880`, `June27,2018`, `19:00:00`, `June 28,2018`, `01:00:00`. Observe proper HTML nesting. Execute the program to view the output.

```html

```