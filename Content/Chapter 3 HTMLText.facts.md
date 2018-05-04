### Working with Text

When creating a web page , you add tags to give extra meaning and give users the appropriate structure for a page. 

1. Structural Markup and Semantic Markup  

    - `Structural Markup` are elements that you can use to describe both headings and paragraphs.

    - `Semantic Markup` provide information, such putting emphasis in a text or something that is written in quotation, the meaning of acronymns and so on. 

2. Bold, Itlaic

    - Enclosing texts inside the bold tag `<b></b>` makes the characters appear to be <b>bolded</b>.

    - Enclosing texts inside the italic tag `<i></i>` makes the characters appear to be <i>italic</i>.
    
    - The `<i>` element also represent a section of text that is expressed in a different way from its surrounding content. For example, foreign words, thoughts or other words that needs to be italicized.

    Code:
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <title>Working with Text</title>
        </head>
            <p> I am <b> AWESOME ! </b></p>
            <p>Awesome in Turkish is called <i>müthiş</i></p>
    </html>
    ```

    Output:

     <p> I am <b> Awesome ! </b></p>
    <p>Awesome in Turkish Language is called <i>müthiş</i></p>

3. Superscript and Subscript

    - The `<sup>` element contains characters that are superscript such as suffixes of dates or mathematical concepts.
    
    - The `<sub>` element contains characters that are subscript commonly used as foot notes or chemical formulas.

    Code:

    ```html

    On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm such that the formula e<sup>x</sup>dx = e<sup>x</sup> + C will be used.

    In science the compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>
    
    ```
    Output:

     On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm such that the formula e<sup>x</sup>dx = e<sup>x</sup> + C will be used.

    In science the lesson would be on compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

4. Empty Element
    
    - There are few elements in HTML that do not have any elements between the opening and closing tags, they are called as the `empty elements`

    - An `empty element` has only one tag. Before the closing angled bracket of an `empty element` there is a space and a forward slash character. `< />`

    - An example of this `empty element` is the `<br />` break tag and the  `<hr />` horizontal rule tag.

    Code: 

    ```html
     I am learning <br /> break tags of an empty element in HTML today!
    <hr />
    I am excited to find out more about some other features of HTML.
    <hr />

    ```
    Output:

     I am learning <br /> break tags of an empty element in HTML today!
      <hr />
    I am excited to find out more about some other features of HTML.
    <hr />

    - `<br />` break tag adds a line break inside the middle of the paragraph or shows new paragraph or heading on a new line.

    - `<hr />` horizontal rule tag lets you add a horizontal line between two paragraphs or sections.


   


     
     

   
