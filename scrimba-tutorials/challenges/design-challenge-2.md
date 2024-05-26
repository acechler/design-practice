# Design Challenge 2

This is the code from Design Challenge 2

## My Code

```css
html, body{
    margin: 0;
    padding: 0;
}

body {
    background: #212527;
    color: #9FB289;
}

.container {
    display: grid;
    width: 100%;
    margin: 2em auto 0;
}

.card {
    background: #337590;
    display: grid;
    grid-template-columns: 1fr 5fr;
    align-items: center;
    border-radius: 1em;
    margin-bottom: 2em
}

p, h3 {
    margin: 0;
}
h3 {
    margin-left: 1em;
    margin-top: .5em;
}
span {
    width: 5em;
    height: 5em;
    background: #75A2B8;
    border-radius: 50%;
}

/* 

   Your fixes below:
   
   My solution included using the following properties:  
   width, background, padding, margin,
   text-transform, font-size, letter-spacing & color
   
*/

.container {
    padding: 1em;
}

.card {
    grid-template-columns: .1fr auto;
    padding: 1em;
}

p.date {
    padding-top: 0.25em;
}

h3 {
    padding-left: 0.25em;
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
    <main>
      <div class="container">
        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">December 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>

        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">Decemeber 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>

        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">Decemeber 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>
      </div>
    </main>
  </body>
</html>

```

## Instructors Code

```css
html, body {
    margin: 0;
    padding: 0;
}
body {
    background: #212527;
    color: #9FB2B9;
}

.container {
    display: grid;
    width: 100%;
    margin: 2em auto 0;
}
.card {
    background: #337590;
    display: grid;
    grid-template-columns: 1fr 5fr;
    align-items: center;
    border-radius: 1em;
    margin-bottom: 2em;
}
p, h3 {
    margin: 0;
}
h3 {
    margin-left: 1em;
    margin-top: .5em
}
span {
    width: 5em;
    height: 5em;
    background: #75A2B8;
    border-radius: 50%;
}

/* 

   Your fixes below:
   
   My solution included using the following properties:  
   width, background, padding, margin,
   text-transform, font-size, letter-spacing & color
   
*/

.container {
    width: 90%;
}

.card {
    background: #2C3031;
    padding: 1.5em;
}

p.date {
    text-transform: uppercase;
    font-size: .75em;
    letter-spacing: .1em;
    color: #7A8587;
    margin-bottom: .4em;
}

h3 {
    margin: 0 0 .3em;
    color: #B6EAFF;
    font-size: 1.8em;
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
    <main>
      <div class="container">
        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">December 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>

        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">Decemeber 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>

        <div class="card">
          <span></span>
          <div class="content">
            <p class="date">Decemeber 18 2023</p>
            <h3>November Rain</h3>
            <p class="desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
              velit architecto corporis magni nisi optio delectus blanditiis
              culpa, eum quo veritatis ex non similique! Quasi minima soluta
              sequi porro? Tempora.
            </p>
          </div>
        </div>
      </div>
    </main>
  </body>
</html>


```