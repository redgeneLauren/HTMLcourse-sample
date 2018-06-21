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

Which of the following texts are the contents for the header in the HTML table?

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

- It contains the data per cell of the column of the HTML table.


/// type=MS, answer=[2,3]

Which of the following texts are the `table data` of HTML table?

- `Name`

- `Soda`

- `Beverage`

- `Category`

- `Quantity`


/// type=SS, answer=[1]

What tag is used to create `table data` in an HTML table?

- `<td>`

- `<tr>`

- `<caption>`

- `<table>`

- `<body>`


/// type=SS, answer=[2]

What data is on row 1 column 1 of the HTML table?

- `12`

- `Soda`

- `Item Name`

- `Category`

- `Beverage`


/// type=SS, answer=[5]

What data is on row 2 coloumn 2 of the HTML table?

- `12`

- `Soda`

- `Item Name`

- `Category`

- `Beverage`


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
            <tfooter>
                <tr>
                    <td>footer: 06-21-28</td>
                </tr>
            </tfooter>
        </table>
    </body>
</html> 

```









