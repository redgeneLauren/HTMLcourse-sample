### Facts for Working with Forms

An HTML document handles collected data from filled in forms and pieces out the collected data to a corresponding action using an HTML form element. The form structure in HTML is written using the `<form>` element.

The `<form>` element is used to collect data from a user input and its attributes sets to receive and take action to the inputted data. These `<form>` attributes are:

- `action` - It contains the URL or location value where it will send the collected data once it has been submitted. 

- `method` - It tells the browser how to send the collected data. The value of the `method` attribute is either to `get` or to `post`.

- `id` - It is a unique identifier to distinctly identify from other `<form>` elements.

These are the basic form control elements used inside the `<form>` element:

1. `<input>` - It is used to create different types of form controls from a user input. The form controls of `<input>` depends on the value written inside the `type` attribute . Attributes in the `<input>` element are:

- `name` - It sets the label of the form control. The attribute value is written in a text format.

- `value` - It sets the value of the form control. The attribute value is written in a text format.

- `type` - It sets the type of form control. The `type` attribute values are: 

    - `<input type="text">` - It is a textfield type of form control.

    - `<input type="radio">` - It is a radio button type of form control.

    - `<input type="submit">` - It is a submit button type of form control.

    - `<input type="password">` - It is an encrypted textfield type of form control.

2. `<fieldset>` - It groups related form controls base on the controls functionality.

3. `<legend>` - It puts a label on the `<fieldset>` element base on the form controls category.

The example code shows how forms appear in HTML.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Forms</title>
    </head>
    <body>
        <form action="" method="post" target="_blank">
            <fieldset>
                <legend>Personal Data</legend>
                FirstName:
                <input type="text" name="fname">
                LastName:
                <input type="text" anme="lname"><br /><br />
                Female:
                <input type="radio" value="Female">
                Male:
                <input type="radio" value="Male"><br /><br />
                <input type="submit" value="Submit Data">
            </fieldset>
        </form>
    </body>
</html>

```
Output:

<!DOCTYPE html>
<html>
    <head>
        <title>Working with Forms</title>
    </head>
    <body>
        <form action="" method="post" target="_blank">
            <fieldset>
                <legend>Personal Data</legend>
                FirstName:
                <input type="text" name="fname">
                LastName:
                <input type="text" anme="lname"><br /><br />
                Female:
                <input type="radio" value="Female">
                Male:
                <input type="radio" value="Male"><br /><br />
                <input type="submit" value="Submit Data">
            </fieldset>
        </form>
    </body>
</html>

