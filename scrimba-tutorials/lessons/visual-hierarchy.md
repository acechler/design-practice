# Visual Hierarchy

UI Design Fundamentals can be used to organize a visual hierarchy.
- What element is important?
- How should it catch the eye of the user?
- What styles can we add to achieve this?

Recap of Design Fundamentals
- White Space and Allignment
- Contrast
- Color
- Scale

These can be used to establish importance. You can use one or multiple fundamentals to achieve
a visual hierarchy.


```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');
html, body {
    margin: 0;
    padding: 0;
}

body {
    padding: 2em;
    background: #5801CB;
    color: white;
    font-family: 'Nunito';
}

h1 {
    font-size: 1.1em;
}

.form-container {
    padding: 2em;
    display: grid;
    grid-template-columns: 70% auto;
    grid-template-rows: repeat(3,auto);
    grid-template-areas:
        "label label"
        "submit button"
        "info info";
}

label {
    display: block;
    font-size: 1.1em;
    grid-area: label;
    margin-bottom: .8em;
}

input[type=text] {
    width: 90%;
    padding: .5em;
}
input[type=submit] {
    padding: .5em;
    font-size: .8em;
    background: none;
    border: 1px solid white;
    color: white;
    cursor: pointer;
}
p {
    grid-area: info;
}

/* Improvements */


h1 {
    font-size: 3em;
}

.form-container {
    background: #6900F3;
}

label {
    font-weight: bold;
    font-size: 1.2em;
}

input[type=submit] {
    font-size: 1em;
    background: #FFED8C;
    color: #5801CB;
    border: none;
    font-weight: bold;
}

p {
    color: #CAA2FF;
}

```


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header></header>
    <main>
      <h1>Join the mailing list!</h1>

      <div class="form-container">
        <label for="email">Email Address</label>
        <input type="text" id="email">
        <p>Don't worry, we won't ever share your email!</p>
        <input type="submit" value="Submit email">
      </div>

    </main>
    <footer></footer>
  </body>
</html>



```