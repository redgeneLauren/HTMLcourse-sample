### Facts for Using HTML Tables

`HTML table` is used to manage layout of an HTML document. An `HTML table` represents information in a grid format and each block of the grid is referred to as a `cell`.
 
An `HTML table` is defined by the `<table>` element. The `<table>` element creates the `table`. The `table` contents are written in a tabluar form where it is written out row by row.

The basic components of an `HTML table` are the following:

- `table row` - It is defined by the element `<tr>`. The `<tr>`element creates the row of the table.

- `table header` - It is defined by the element `<th>`. The `<th>` element creates the header per column in the table.

- `table data` - It is defined by the element `<td>`. The `<td>` element contains the table data per cell of the column.

- `table caption` - It is defined by the element `<caption>`. The `<caption>` element sets the table caption.

`HTML table` can be group together in order to have a structured layout using header section, body content and footer section. 

The table groupings of `HTML table` are the following:

- Group table header - It is defined by the element `<thead>`. It is used to group header content in an  HTML table.

- Group table body - It is defined by the `<tbody>`. It is used to group the body content in an HTML table.

- Group table footer - It is defined by the `<tfooter>`. It is used to group footer content in an HTML table.

- The example code shows how `HTML table` is structured with proper observation of nesting.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <thead>
                <caption>Prelim Grades</caption>
                <tr>
                    <th>First Name</th>
                    <th>Last Name</th>
                    <th>Subject</th>
                    <th>Grade</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Zach</td>
                    <td>Demsey</td>
                    <td>Mathematics</td>
                    <td>90</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>

```
Output:

<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <thead>
                <caption>Prelim Grades</caption>
                <tr>
                    <th>First Name</th>
                    <th>Last Name</th>
                    <th>Subject</th>
                    <th>Grade</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Zach</td>
                    <td>Demsey</td>
                    <td>Mathematics</td>
                    <td>90</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
