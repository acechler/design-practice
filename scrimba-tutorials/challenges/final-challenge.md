# Final Challenge

This is the final challenge of the Scrimba UI Fundamentals Course

## My Code

```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');

html, body {
    margin: 0;
    padding: 0;
}

body {
    background: #014BCB;
    display: grid;
    grid-template-columns: 10% auto;
    height: 100vh;
    color: white;
    font-family: 'Nunito';
    grid-gap: .5em;
}

sidebar {
    background: #1d3154;
}
.content {
    background: #6C22FF;
    padding: .5em;
    width: 50%;
    margin-right: 2em;
    border-radius: .8em;
}

h1 {
    margin-left: 1em;
    font-size: 1em;
}

h3 {
    margin: 0;
    font-size: .9em;
    color: #FF69F5;
}

ul {
    list-style-type: none;
    padding: 0;
    margin-bottom: 0;
}

li {
    margin-bottom: .5em;
    font-size: .8em;
}
span {
    float: right;
}

/*  
    Your Fixes Below
    
    Please keep the same background color
    and the same sidebar background color.
    
*/

body {
    grid-gap: 1em;    /* Improve the white space */
}

h3 {
    margin: 0;
    font-size: 1.5em;
    color: #ff69f5;
}

.content {
    background: #6c22ffd5; /* Improve the color/contrast */
    padding: 1em;         /* Improve the white space */
}

h1 {
    margin-left: 0.1em;  /* Improve the alignment */
    font-size: 3em;   /* Improve the visual hierarchy */
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

    <sidebar></sidebar>
    <main>
     <h1>Dashboard</h1>

      <div class="content">
        <h3>Sales Report</h3>

        <ul>
          <li><strong>Earnings</strong><span>$1,032</span></li>
          <li><strong>Refunds</strong><span>$149</span></li>
          <li><strong>Chargebacks</strong><span>$40</span></li>
          <li><strong>Net Income</strong><span>$892</span></li>
        </ul>

      </div>

    </main>
    <footer></footer>
  </body>
</html>


```

## Instructors Code

```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');

html, body {
    margin: 0;
    padding: 0;
}

body {
    background: #014BCB;
    display: grid;
    grid-template-columns: 10% auto;
    height: 100vh;
    color: white;
    font-family: 'Nunito';
    grid-gap: .5em;
}

sidebar {
    background: #1d3154;
}
.content {
    background: #6C22FF;
    padding: .5em;
    width: 50%;
    margin-right: 2em;
    border-radius: .8em;
}

h1 {
    margin-left: 1em;
    font-size: 1em;
}

h3 {
    margin: 0;
    font-size: .9em;
    color: #FF69F5;
}

ul {
    list-style-type: none;
    padding: 0;
    margin-bottom: 0;
}

li {
    margin-bottom: .5em;
    font-size: .8em;
}
span {
    float: right;
}

/*  
    Your Fixes Below
    
    Please keep the same background color
    and the same sidebar background color.
    
*/

body {
    grid-gap: 2em;    /* Improve the white space */
}


.content {
    background: #0044B9; /* Improve the color/contrast */
    padding: 1.5em;         /* Improve the white space */
}

h1 {
    margin-left: 0em;  /* Improve the alignment */
    font-size: 2.3em;   /* Improve the visual hierarchy */
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

    <sidebar></sidebar>
    <main>
     <h1>Dashboard</h1>

      <div class="content">
        <h3>Sales Report</h3>

        <ul>
          <li><strong>Earnings</strong><span>$1,032</span></li>
          <li><strong>Refunds</strong><span>$149</span></li>
          <li><strong>Chargebacks</strong><span>$40</span></li>
          <li><strong>Net Income</strong><span>$892</span></li>
        </ul>

      </div>

    </main>
    <footer></footer>
  </body>
</html>


```