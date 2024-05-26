# Design Challenge 1

This is the resulting code from my exercise. I will post what the instructor did below it.

## My Solution
```css
html, body{
    margin: 0;
    padding: 0;
}
body{
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(3, auto);
    place-items: center;
    background: lightblue;
    grid-gap: 2em;
}

.card{
    background: white;
}
span{
    height: 100px;
    display: block;
    width: 100%;
    background: #71A6B8;
}

p.date{
    text-align: center;
    font-size: .7em;
    text-transform: uppercase;
}

h3{ margin: 0;}

p.desc{
    font-size: .9em;
}

/* 
   Use the following properties
   to fix the alignment and white
   space issues on the rulesets
   below this comment.
   
   margin, padding, text-align
   
*/

body{
    text-align: center;
}
.content{
    padding: 1em;
}
p.date{
    margin: 0;
}
h3{
    margin: .5em;
}
p.desc{
    margin: 1em;
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
  <div class="card">
    <span></span>
    <div class="content">
      <p class="date">July 12, 2024</p>
      <h3>Awesome Title</h3>
      <p class="desc">This is a lovely description for this particular card</p>
    </div>
  </div>
  <div class="card">
    <span></span>
    <div class="content">
      <p class="date">July 12, 2024</p>
      <h3>Awesome Title</h3>
      <p class="desc">This is a lovely description for this particular card</p>
    </div>
  </div>
  <div class="card">
    <span></span>
    <div class="content">
      <p class="date">July 12, 2024</p>
      <h3>Awesome Title</h3>
      <p class="desc">This is a lovely description for this particular card</p>
    </div>
  </div>
  
</body>
</html>

```

## Instructor Solution

