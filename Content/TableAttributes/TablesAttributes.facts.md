### Facts for Table Attributes

An `HTML table` contains attributes to improve the appearance of the table and to set a well defined layout for the readability of its table data. Some of these attributes are the following:

1. `border` - It is written inside the opening tag `<table>`. Its attribute name is `border` and its attribute value is set in pixels. It is used to put thickness to the border of a table. The attribute value `0` sets no border around the table.

2. `width` - It is written inside the opening tags `<table>`, `<th>`, `<td>` and `<tr>`. Its attribute name is `width` and its attribute value is set in either pixels or percentage. It is used to set the width of the element in the table.

3. `height` - It is written inside the opening tags `<table>`, `<th>`, `<td>` and `<tr>`. Its attribute name is `height` and its attribute value is set in either pixels or percentage. It is used to set the height of the element in the table.

4. `colspan` - It is written inside the `<th>` and `<td>` opening tags. It refers to the number of columns it extends to and merges the columns as one. 

5. `rowspan` - It is written inside the `<th>` and `<td>` opening tags. It refers to the number of rows it extends to and merges the rows as one.

6. `align` - It is written inside in all of the table element's opening tags. It is used to set the position of a table or a content in a table .

The example code shows how table attributes are used: 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Table Attributes</title>
    </head>
    <body>
        <table width="500px" border="1" align="center">
            <caption>Student Record</caption>
            <thead>
                <tr>
                    <th></th>
                    <th>Gender</th>
                    <th>Name</th>
                    <th>Age</th>
                    <th>Height in cm</th>
                    <th colspan="3">Date of Birth(m/d/yyyy)</th>
                </tr>
            </thead>
            <tbody align="center">
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
                <tr>
                    <td rowspan="2">Grade 12</td>
                    <td>Female</td>
                    <td>Georgopol</td>
                    <td>19</td>
                    <td>165</td>
                    <td>02/10/2001</td>
                </tr>
                <tr>
                    <td>Male</td>
                    <td>Severny</td>
                    <td>22</td>
                    <td>189</td>
                    <td>12/26/1999</td>
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
        <title>HTML Table Attributes</title>
    </head>
    <body>
        <table width="500px" border="1" align="center">
            <caption>Student Record</caption>
            <thead>
                <tr>
                    <th></th>
                    <th>Gender</th>
                    <th>Name</th>
                    <th>Age</th>
                    <th>Height in cm</th>
                    <th colspan="3">Date of Birth(m/d/yyyy)</th>
                </tr>
            </thead>
            <tbody align="center">
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
                <tr>
                    <td rowspan="2">Grade 12</td>
                    <td>Female</td>
                    <td>Georgopol</td>
                    <td>19</td>
                    <td>165</td>
                    <td>02/10/2001</td>
                </tr>
                  <tr>
                    <td>Male</td>
                    <td>Severny</td>
                    <td>22</td>
                    <td>189</td>
                    <td>12/26/1999</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>