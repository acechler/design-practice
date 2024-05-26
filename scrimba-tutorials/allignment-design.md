# Allignment Design

This example shows the importance of allignment. You can change the oppacity inside the `.container` to see a vertical line that shoes a visualization.


```css
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap');

html, body{
    margin: 0;
    padding: 0;
    font-family: 'Montserrat';
    height: 100vh;
}

body{
    background: #444E5C;
    display: grid;
    border-left: 17px solid rgba(0,0,0,.2);
}

.container{
    width: 80%;
    margin: 0 auto;
}

a{
    color: white;
    text-decoration: none;
}

a.logo{
    display: block;
    padding-top: 1em;
    font-weight: bold;
    text-transform: uppercase;
    font-size: .8em;
}

h1 {
    margin: 2em 0 1em .5em;
    color: white;
}

p{
    color: #B3CEF2;
    line-height: 1.4em;
    font-size: .9em;
}

a.cta{
    display: inline-block;
    background: #5099FF;
    padding: .8em 1.7em;
    font-weight: bold;
    border-radius: 2em;
    transform: translateX(50%);
    margin-top: 1.5em;
}


/* Show Column */

/* If you change the oppacity from 0 to 1, you will see a column line on the left of the page. */
.container {
    border-left: 1px solid rgba(255, 255, 255, 1);
}


/* Improvements */

h1 { margin-left: 0; }
a.cta {transform:none; }
a.logo { text-align: left; }
```


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <a href="#" class="logo">SomeCompany</a>
    <h1>Identifying Strong Alignment</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quaerat explicabo tempore expedita odio, aut ab eaque error, ipsa quod perspiciatis, perferendis ducimus assumenda et. Ratione quod consequuntur animi sed quas?</p>
    <a href="#" class="cta">Get Aligned</a>
  </div>
</body>
</html>

```