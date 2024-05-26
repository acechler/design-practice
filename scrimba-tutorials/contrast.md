# Contrast

This tutorial goes over the basics of contrast. It also explains how contrast plays a key role in accessability.

```css
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap');

html, body {
    margin: 0;
    padding: 0;
}
body {
    font-family: 'Montserrat';
}
.container {
    padding: 3em 2em;
}
header {
    position: relative;
    display: block;
    width: 100%;
}
header::after {
    content: "";
    position: absolute;
    z-index: -1;
    /* Remove #b0cee9 if you have an image. */
    background: url('asset1.jpg') #b0cee9;
    background-position: 0% 20%;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

h1 {
    margin: 0;
    font-size: 2.5em;
    color: #002A4E;
}
p {
    color: rgba(0,0,0,.3);
    margin-top: .5em;
    font-size: .9em;
    font-weight: bold;
}
a {
    background: #CCCCCC;
    padding: .8em;
    text-decoration: none;
    color: gray;
    font-weight: bold;
    font-size: .8em;
    border-radius: .4em;
    margin-top: 1.5em;
    display: inline-block;
    text-transform: uppercase;
}

/* Overwrites */

p{ color: #002A4E;}

a{ 
    background: #006BC6;
    color: white;
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
 
  <header>
    <div class="container">
      <h1>Take a vacation</h1>
      <p>Come and witness our amazing mountain views.</p>

      <a href="#">Explore now</a>

      
    </div>
  </header>
  
</body>
</html>

```