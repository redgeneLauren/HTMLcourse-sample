### Facts for Tables with Attributes

An `HTML table` can contain attributes to have a better look to the table. Some of these attributes are the following:

1. `border` - The `border` attribute is defined in the `<table>` opening tag. Its attribute name is `border` and its attribute value indicates the width of the border in pixels. The value `0` sets no border around the table.

2. `width` - The `width` attribute can be used in the opening tags `<table>`, `<th>` and `<td>`. Its attribute name is `width` and its attribute value are set in pixels or precentage. 

3. `colspan` - The `colspan` attribute can be used in the `<th>` and `<td>` opening tags. It refers to the number of columns it extends and merges the column as one. 

4. `rowspan` - The `rowspan` attribute can be used in the `<th>` and `<td>` opening tags. It refers to the number of rows it extends and merges the rows as one

The example code shows how table attributes are used in an HTML table:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Table Attributes</title>
    </head>
    <body>
        <table width="400" border="1">
        <caption>Student Record</caption>
            <tr border="1">
                <th></th>
                <th>Gender</th>
                <th>Name</th>
                <th>Age</th>
                <th>Height in cm</th>
            </tr>
            <tr>
                <td rowspan="2">Grade 11</td>
                <td>Female</td>
                <td>Jessica</td>
                <td>21</td>
                <td>162</td>
            </tr>
            <tr>
                <td>Male</td>
                <td>Joshua</td>
                <td>25</td>
                <td>198</td>
            </tr>
        </table>
    </body>
</html>

```

Output:

<!DOCTYPE html>
<html>
    <head>
        <title>HTML Table Attributes</title>
    </head>
    <body>
        <table width="400" border="1">
        <caption>Student Record</caption>
            <tr border="1">
                <th></th>
                <th>Gender</th>
                <th>Name</th>
                <th>Age</th>
                <th>Height in cm</th>
            </tr>
            <tr>
                <td rowspan="2">Grade 11</td>
                <td>Female</td>
                <td>Jessica</td>
                <td>21</td>
                <td>162</td>
            </tr>
            <tr>
                <td>Male</td>
                <td>Joshua</td>
                <td>25</td>
                <td>198</td>
            </tr>
        </table>
    </body>
</html>