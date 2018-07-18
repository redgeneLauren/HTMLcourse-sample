<!DOCTYPE html>
<html>
	<head>
		<title>Table Attributes</title>
	</head>
    <body>
        <table border=`1`, align=`center`>
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