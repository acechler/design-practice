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

```css
html, body {
    margin: 0;
    padding: 0;
}

body {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(3, auto);
    place-items: center;
    background: lightblue;
    grid-gap: 2em;
}

.card {
    background: white;
}
span {
    height: 100px;
    display: block;
    width: 100%;
    background: #71A6B8;
}

p.date {
    text-align: center;
    font-size: .7em;
    text-transform: uppercase;
}
h3 {
    margin: 0;
}
p.desc {
    font-size: .9em;
}

/* 
   Use the following properties
   to fix the alignment and white
   space issues on the rulesets
   below this comment.
   
   margin, padding, text-align
   
*/

body {
    padding: 2em;
}
.content {
    padding: 1em;
}

p.date {
    text-align: left;
    margin: 0;
}

h3 {

}

p.desc {
    margin-bottom: 0;
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

### Compare and Contrast

- I put `text-align: center` in the body tag.
- The instructor placed `padding: 2em` inside the body. I was thinking about doing this but margin and padding have already be set towards the top of the file. I thought it would be redundent. 

- We both place `padding: 1em` inside the `.content` tag

- We both placed `margin: 0` inside the p.date tag. However he also put `text-align: left` in as well. Its funny because I disregarded a saying from another ux designer. When in doubt left align. 

- For `h3` tag I placed `margin: 0.5em` the instructor got rid of it entirely. 

- For `p.desc` I placed a `margin: 1em`. The instructor placed a `margin-bottom: 0;`


Some advice from the instructor
- Always try to balance the white space.