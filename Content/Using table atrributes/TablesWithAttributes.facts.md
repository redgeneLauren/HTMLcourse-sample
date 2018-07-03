### Facts for Tables Attributes

`HTML table` can contain attributes to have a better look to the table. Some of these attributes are the following:

1. `border` - The `border` attribute is written inside the opening tag `<table>`. Its attribute name is `border` and its attribute value is indicated by width of the border in pixels. To have no border around the table set the attribute value to `0`.

2. `width` - The `width` attribute can be written inside the opening tags `<table>`, `<th>` and `<td>`. Its attribute name is `width` and its attribute value is set in either pixels or percentage. 

3. `height` - The `height` attribute can be written inside the opening tags `<table>`, `<th>`, `<td>`. Its attribute name is `height` and its attribute value is set in either pixels or percentage.

4. `colspan` - The `colspan` attribute can be written inside the `<th>` and `<td>` opening tags. It refers to the number of columns it extends to and merges the columns as one. 

5. `rowspan` - The `rowspan` attribute can be written inside the `<th>` and `<td>` opening tags. It refers to the number of rows it extends to and merges the rows as one.

The example code shows how table attributes are used: 

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
                <th colspan="3">Date of Birth(m/d/yyyy)</th>
            </tr>
            <tr>
                <td rowspan="2">Grade 11</td>
                <td>Female</td>
                <td>Jessica</td>
                <td>21</td>
                <td>162</td>
                <td>11/10/2000</td>
            </tr>
            <tr>
                <td>Male</td>
                <td>Joshua</td>
                <td>25</td>
                <td>198</td>
                <td>02/26/1998</td>
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
                <th colspan="3">Date of Birth(m/d/yyyy)</th>
            </tr>
            <tr>
                <td rowspan="2">Grade 11</td>
                <td>Female</td>
                <td>Jessica</td>
                <td>21</td>
                <td>162</td>
                <td>11/10/2000</td>
            </tr>
            <tr>
                <td>Male</td>
                <td>Joshua</td>
                <td>25</td>
                <td>198</td>
                <td>02/26/1998</td>
            </tr>
        </table>
    </body>
</html>