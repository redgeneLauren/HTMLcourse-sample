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
        <table width="300" border="1">
            <thead>
                <caption>Student Records</caption>
                    <tr>
                        <th>FirstName</th>
                        <th>LastName</th>
                        <th colspan="3">Birthdate(m/d/yyyy)</th>
                    </tr>
            </thead>
        <table>
    <body>
</html>

```

/// type=SS, answer=[2]

Execute the program. What is its output?

- <table border="1"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><table>

- <table width="300" border="1"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><table>

- <table width="300"><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><table>

- <table width="300" border=""><thead><tr><th>FirstName</th><th>LastName</th><th colspan="3">Birthdate(m/d/yyyy)</th></tr></thead><table>

- <table width="300" border=""><thead><caption>Student Records</caption><tr><th>FirstName</th><th>LastName</th><th>Birthdate</th></tr></thead><table>


/// type=SS, answer=[2]

Which of the following elements define the `table row` of the HTML table?

- `<th>`

- `<tr>`

- `<body>`

- `<table>`

- `<caption>`


/// type=SS, answer=[3]

What is the `table caption` of the HTML table?

- LastName

- FirstName

- Student Records

- Birthdate(m/d/yyyy)

- There is no `table caption` set.


/// type=MS, answer=[1,2,4]

What table attributes are used in the HTML table?

- `width`

- `height`

- `border`

- `colspan`

- `rowspan`


/// type=SS, answer=[1]

What tag is used to create a row in the HTML table?

- `<tr>`

- `<td>`

- `<thead>`

- `<table>`

- `<caption>`


/// type=SS, answer=[5]

What is `colspan` inside the element `<th colspan="3">Birthdate(m/d/yyyy)</th>`?

- It is an attribute that sets the height of the table row.

- It is an attribute that sets the width of the table column.

- It is an attribute that sets the width size of the table border.

- It is a table attribute that sets the number of rows it extends to and merge it as one row.

- It is table atttribute that sets the number of columns it extends to and merge it as one column.


/// type=SS, answer=[3]

What is `border` inside the element `<table width="300" border="1">`?

- It is an attribute that sets the height of the table row.

- It is an attribute that sets the width of the table column.

- It is an attribute that sets the width size of the table border.

- It is a table attribute that sets the number of rows it extends to and merge it as one row.

- It is table atttribute that sets the number of columns it extends to and merge it as one column.


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
        
    </body>
</html>
```