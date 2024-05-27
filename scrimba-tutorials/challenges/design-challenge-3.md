# Design Challenge 3

## My Code

```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');

:root {
    --darkest-blue: #1C2022;
    --gray-red: #9D9D9D;
    --dark-blue: #2B3337;
    --hot-pink: #FF01FF;
    --light-white: white;
}

html, body {
    margin: 0;
    padding: 0;
}

body {
    background: rgba(0,0,0,.8);
    color: white;
    font-family: 'Nunito';
}

.container {
    margin-top: 3em;
    border-left: .7em  solid gray;
    padding: 0 3em;
}
h1 {
    margin: 0;
}
p {
    color: #9D9D9D;
    margin: .5em 0 2em;
}

label {
    display: block;
    font-weight: bold;
    margin-bottom: .7em;
}
input[type=text], textarea {
    margin-bottom: 1.5em;
    display: block;
    padding: .5em;
    width: 80%;
    background: gray;
    border: none;
    border-bottom: 1px solid lightgray;
    outline: 0;
    color: black;
}
input[type=text]:focus, textarea:focus {
    border-bottom: 1px solid white;
}

input[type=submit] {
    background: gray;
    border: none;
    color: white;
    font-weight: bold;
    padding: .8em 2em;
    border-radius: 2em;
    font-size: .8em;
}

.colors {
    position: absolute;
    bottom: 0;
    right: 0;
    padding: .5em;
}
.colors div {
    width: 2em;
    height: 2em;
    background: gray;
    border-radius: 50%;
    margin-bottom: .4em;
    margin-right: .3em;
    float: left;
    text-align: center;
    display: grid;
    place-content: center;
    border: 2px solid rgba(0,0,0,.3);
}
.colors div:nth-child(1) {
    background-color: #1C2022;
}
.colors div:nth-child(2) {
    background-color: #9D9D9D;
}
.colors div:nth-child(3) {
    background-color: #2B3337;
}
.colors div:nth-child(4) {
    background-color: #FF01FF;
}
.colors div:nth-child(5) {
    background-color: white;
    color: black;
}


/*
    Your fixes below!
    
    Use these colors codes: 
    (1) #1C2022
    (2) #9D9D9D
    (3) #2B3337
    (4) #FF01FF
    (5) white


:root {
    --darkest-blue: #1C2022;
    --gray-red: #9D9D9D;
    --dark-blue: #2B3337;
    --hot-pink: #FF01FF;
    --light-white: white;
}

*/

body {
    background: var(--dark-blue);

}

.container {
    border-left: .7em  solid var(--hot-pink);
    background: var(--darkest-blue);
}

p {
    color: var(--light-white);
}

input[type=text], textarea {
    background: var(--dark-blue);
    border-bottom: var(--hot-pink);
    
}

input[type=text]:focus, textarea:focus {
    border-bottom: var(--hot-pink);
}

input[type=submit] {
    background: var(--hot-pink);
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
      <div class="container">
        <h1>Contact us Today</h1>
        <p>We usually respond within 24 hours. If we don't, you get a free month on us. </p>

        <form action="">
          <label for="name">Your name</label>
          <input type="text" id="name">

          <label for="name">Your name</label>
          <textarea id="name"></textarea>

          <input type="submit" value="Send message">
        </form>
      </div>
      <div class="colors">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
      </div>
    </main>
    <footer></footer>
  </body>
</html>

```

## Instructors Code

### First Solution
```css
body {
    background: #1C2022;
}

.container {
    border-left: .7em  solid #FF01FF;
}

p {
    color: #9D9D9D;
}

input[type=text], textarea {
    background: #2B3337;
    border-bottom: 1px solid #506671;
    color: #9D9D9D;
}

input[type=text]:focus, textarea:focus {
    border-bottom: 1px solid #FF01FF;
}

input[type=submit] {
    background: #FF01FF;
}

```
### Second Solution
```css

```

### Third Solution
```css

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
      <div class="container">
        <h1>Contact us Today</h1>
        <p>We usually respond within 24 hours. If we don't, you get a free month on us. </p>

        <form action="">
          <label for="name">Your name</label>
          <input type="text" id="name">

          <label for="name">Your name</label>
          <textarea id="name"></textarea>

          <input type="submit" value="Send message">
        </form>
      </div>
      <div class="colors">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
      </div>
    </main>
    <footer></footer>
  </body>
</html>

```