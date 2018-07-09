### Facts on Working with Layouts

Common structural blocks are needed in setting up the layout of a webpage using HTML. These sets of HTML elements are used to group a block of elements to have a structural layout. These elements are the following:

- `<header>` - The `<header>` element contains the introductory content of the page. It is where heading elements, search forms and logos are placed. The header section is mostly duplicated across webpages.

- `<nav>` - The `<nav>` element contains navigation links where it links to a different webpage or a different page of the same webpage.

- `<section>` - The `<section>` element is used to group contents of the page that varies in purpose or subject.

- `<article>` - The `<article>` element contains RSS content which are are blog posts, news headline, publishing data or author's name.

- `<aside>` - The `<aside>` element is used to indicate a part of the content which is related to the primary content. These are side details of the content, related links or author information. 

- `<footer>` - The `<footer>` element is used to indicate a footer part of a document, an article or a section. This is where copyright and authorship information are written.

The example code shows how structural element blocks are used in HTML:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Layouts</title>
    </head>
    <body>
        <header>
            <h1>Codestop</h1>
        </header>
         <nav>
            <ul>
                <li><a href="https://codestop.io/">Codestop Website</a></li>
                <li><a href="https://codestop.io/about-us">About</a></li>
                <li><a href="https://codestop.io/courses">Courses Offered</a></li>
                <li><a href="https://codestop.io/register/">Sign Up</a></li>
            </ul>
        </nav>
        <section>
            <h1>Learning by Coding</h1>
            <p>"The goal of CodeStop is to design programming courses that are affordable to young people in developing nations. Ultimately, we want young people to build the path to a sustainable career through technology."</p>
        <section>
         <aside>
            <p>"We designed our platform to make programming easy to learn, understand, and share." - codestop</p>
        </aside>
        <article>
        <p>"Codestop a platform for learning to program and code since 2017."</p>
        </article>
        <footer>
            <p>All Rights Reserved CodeStop © 2017</p>
            <ul>
                <li><a href="https://codestop.io/">Website</a></li>
                <li><a href="https://codestop.io/about-us">About</a></li>
            </ul>
        </footer>
    </body>
</html>

```

Output:
<!DOCTYPE html>
<html>
    <head>
        <title>Working with Layouts</title>
    </head>
    <body>
        <header>
            <h1>Codestop</h1>
        </header>
         <nav>
            <ul>
                <li><a href="https://codestop.io/">Codestop Website</a></li>
                <li><a href="https://codestop.io/about-us">About</a></li>
                <li><a href="https://codestop.io/courses">Courses Offered</a></li>
                <li><a href="https://codestop.io/register/">Sign Up</a></li>
            </ul>
        </nav>
        <section>
            <h1>Learning by Coding</h1>
            <p>"The goal of CodeStop is to design programming courses that are affordable to young people in developing nations. Ultimately, we want young people to build the path to a sustainable career through technology."</p>
        <section>
         <aside>
            <p>"We designed our platform to make programming easy to learn, understand, and share." - codestop</p>
        </aside>
        <article>
        <p>"Codestop a platform for learning to program and code since 2017."</p>
        </article>
        <footer>
            <p>All Rights Reserved CodeStop © 2017</p>
            <ul>
                <li><a href="https://codestop.io/">Website</a></li>
                <li><a href="https://codestop.io/about-us">About</a></li>
            </ul>
        </footer>
    </body>
</html>

