### Facts for Using HTML Headings

1. HTML Headings
    
    HTML has six levels of headings: 

     - `<h1></h1>` tag is used for the main headings. 
     
     - The content for `<h1></h1>` tag appears to be the largest.

    - `<h2></h2>` tag is used for the subheadings.

    - Any further sections under subheadings are indicated by `<h3>, <h4>, <h5>, <h6>`.
    
    - The content for `<h6></h6>` tag appears to be the smallest. 

    Code: 
    ```html

    <h1> This is the main heading </h1>
    <h2> This is the 2nd level of subheading </h2>
    <h3> This is the 3rd level of subheading </h3>
    <h4> This is the 4th level of subheading </h4>
    <h5> This is the 5th level of subheading </h5>
    <h6> This si the 6th level of subheading </h6>

    ```

    Output: 

    <h1> This is the main heading </h1>
    <h2> This is the 2nd level of subheading </h2>
    <h3> This is the 3rd level of subheading </h3>
    <h4> This is the 4th level of subheading </h4>
    <h5> This is the 5th level of subheading </h5>
    <h6> This si the 6th level of subheading </h6>

    - Attributes can be used in the `heading` element.

     - Users can also adjust the size of the text in their browser and control the style and color using `CSS styles`. 
    

    Code:
    ```html

    <h1 style="font-family: courier; color: orange"> This is the main heading </h1>

    ```
    Output:

    <h1 style="font-family: courier; color: orange"> This is the main heading </h1>



2. HTML Paragraphs

    - The paragraph element is written using the `<p></p>` tag.

    - In the paragraph tag `<p></p>` it should not contain tables or other block of `elements`.

    Code:
    ```html
    <p>We are! We are! The youth of the nation! </p>

    ```
    - The paragraph tag `<p></p>` can contain `attributes`. 

    - Attributes in `<p></p>` paragraph tag are avaialble to use. Some attributes may include:  `align`, `style` `class`, `ID` and `title` .

    - Users can also adjust the size of the text in their browser and control the style and color using `CSS styles`

    Code
    ```html
    <h1 style="font-family: courier; color: orange"> This is the main heading </h1>

    <p style="text-align: center; font-family: courier; font-size: 16pt; color: pink">We are! We are! The youth of the nation! </p>

    ```
    Output:
    
    <h1 style="font-family: courier; color: orange"> This is the main heading </h1>

     <p style="text-align: center; font-family: courier; font-size: 16pt; color: pink">We are! We are! The youth of the nation! </p>

3. Bold and Italic

    - Enclosing texts inside the bold tag `<b></b>` makes the characters appear to be <b>bolded</b>.

    - Enclosing texts inside the italic tag `<i></i>` makes the characters appear to be <i>italic</i>.
    
    - The `<i>` element also represent a section of text that is expressed in a different way from its surrounding content. For example, foreign words, thoughts or other words that needs to be italicized.

    Code:
    ```html

    <h1 style="font-family: courier; color: orange"> This is the main heading </h1>

     <p style="text-align: center; font-family: courier; font-size: 16pt; color: pink">We are! We are! The <b>youth</b> of the <i>nation</i>! </p>

    ```
    Output:

     <h1 style="font-family: courier; color: orange"> This is the main heading </h1>

     <p style="text-align: center; font-family: courier; font-size: 16pt; color: pink">We are! We are! The <b>youth</b> of the <i>nation</i>! </p>

4. Superscript and Subscript

    - The `<sup>` element contains characters that are superscript such as suffixes of dates or mathematical concepts.
    
    - The `<sub>` element contains characters that are subscript commonly used as foot notes or chemical formulas.

    Code:
    ```html

    On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm such that the formula e<sup>x</sup>dx = e<sup>x</sup> + C will be used.

    In science the compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>
    
    ```
    Output:

     On the 16<sup>th</sup> of October the lesson for Math is Exponential Logarithm such that the formula e<sup>x</sup>dx = e<sup>x</sup> + C will be used.

    In science the compound element of Vinegar is C<sub>2</sub>H<sub>4</sub>O<sub>2</sub></p>

   
5. Empty Element
    
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

    - `<br />` break tag adds a line break inside the middle of the paragraph or show new paragraph or heading on a new line.

    - `<hr />` horizontal rule tag let you add a horizontal line between two paragraphs or sections.



   
    