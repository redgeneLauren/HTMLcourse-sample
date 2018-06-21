### Facts for Using HTML Tables

`HTML table` is used to manage layouts of an HTML document. An `HTML table` represents information in a grid format and each block of the grid is referred to as a `cell`.
 
An `HTML table` is defined by the `<table>` element. The `<table>` element creates the `table`. The `table` contents are written in a tabluar form where it is written out row by row.

The basic components of an `HTML table` are the following:

- `table row` - It is defined by the element `<tr>`. The `<tr>`element creates the row of the table.

- `table heading` - It is defined by the element `<th>`. The `<th>` element creates the heading of a column.

- `table data` - It is defined by the element `<td>`. The `<td>` element creates the table data per cell of the column.

- `table caption` - It is defined by the element `<caption>`. The `<caption>` elements sets the table caption.

HTTML tables can manage the layout of the page using header section, body content and footer section. 

These are the table groupings by page section using `an HTML table`":

- `Group table heading` - It is defined by the element `<thead>`.

- `Group table body` - It is defined by the `<tbody>`.

- `Group table footer<tfooter>` - It is defined by the `<tfooter>`.

- The example code shows how HTML tables are structured with proper nesting.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Using HTML Tables</title>
    </head>
    <body>
        <table>
            <caption>Prelim Grades</caption>
            <tr>
                <th>First Name</th>
                <th>Last Name</th>
                <th>Subject</th>
                <th>Grade</th>
            </tr>
            <tr>
                <td>Zach</td>
                <td>Demsey</td>
                <td>Mathematics</td>
                <td>90</td>
            </tr>
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
            <caption>Prelim Grades</caption>
            <tr>
                <th>First Name</th>
                <th>Last Name</th>
                <th>Subject</th>
                <th>Grade</th>
            </tr>
            <tr>
                <td>Zach</td>
                <td>Demsey</td>
                <td>Mathematics</td>
                <td>90</td>
            </tr>
        </table>
    </body>
</html>