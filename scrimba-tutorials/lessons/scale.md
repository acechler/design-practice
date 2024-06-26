# Scale

This shows an example on scaling elements properly.

```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');

html, body { 
    margin: 0;
    padding: 0;
    font-family: 'Nunito';
}

body {
    background: #EBF1F3;
    height: 100vh;
}

.container {
    padding: 2em;
}

/* Refer to Overwrites */
h1 { 
    font-size: 1.2em;
    margin: .3em 0;
}

p.subheading {
    margin-top: 0;
    margin-bottom: 2em;
}

/* Refer to Overwrites */
.color-container {
    display: grid;
    grid-template-columns: repeat(3, 150px);
    grid-gap: 1em;
}
.color {
    border: 1px solid #B8C8CE;
    padding: 1em 1em 0;
}
span {
    width: 40px;
    height: 40px;
    display: block;
    border-radius: 50%;
}

.color:nth-of-type(1) span {background: purple;}
.color:nth-of-type(2) span {background: goldenrod;}
.color:nth-of-type(3) span {background: magenta;}
.color:nth-of-type(4) span {background: blue;}
.color:nth-of-type(5) span {background: darkblue;}
.color:nth-of-type(6) span {background: lightseagreen;}

/* Refer to Overwrites */
p.code {
    font-size: .8em;
    margin-bottom: 0;
    margin-top: .8em;
}

p.desc {
    margin-bottom: 0;
    background: #DAE7EB;
    margin: 1em -1em 0;
    padding: 1em;
}

/* Overwrites */

.color-container {
    grid-template-columns: repeat(3, auto);
}

h1 {
    font-size: 2.2em;
}

p.code {
    font-size: 1.5em;
    font-weight: bold;
}

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
 

  <main>
    <div class="container">
      <h1>Our Colors</h1>
      <p class="subheading">Browse our extensive selection of colors.</p>

      <div class="color-container">
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
        <div class="color">
          <span></span>
          <p class="code">#FFCC00</p>
          <p class="desc">This is an excellent choice for those who love color.</p>
        </div>
      </div>


    </div>
  </main>

  
</body>
</html>

```