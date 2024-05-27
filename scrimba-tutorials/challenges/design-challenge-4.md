# Design Challenge 4

## My Code

```css
@import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');
html, body {
    margin: 0;
    padding: 0;
}

body {
    background: #309D67;
    padding: .4em;
    font-family: 'Nunito', san-serif;
}

.card {
    background: white;
    border-radius: 1em;
    padding: 2.3em;
    text-align: center;
}

svg {
    width: 5em;
}

h1 {
    font-size: 1em;
    font-weight: normal;
}

.card p {
    font-size: .85em;
    color: #474747;
}

a { 
    display: inline-block;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5em;
    font-size: .8em;
}

.obligation {
    text-align: center;
    color: white;
    font-weight: bold;
    margin-bottom: 0;
}

/*

    Your fixes below:
    
    Use the following properties and rulesets
    to improve the visual hierarchy of this
    design
    
*/

body {
    padding: 1em;
}

svg {
    width: 5em;
}

h1 {
    font-size: 2em;
    font-weight: bold;
}

.card p {
    font-size: 1em;
    line-height: 1.5em;
    color: black;
}

a {
    background: #309d6728;
    padding: 1em;
    margin-top: 1em;
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
     
      <div class="card">
            
        <svg viewBox="0 0 96 96">
            <g id="down-arrow" transform="translate(-418 -150)">
                <g id="Ellipse_2" data-name="Ellipse 2" transform="translate(418 150)" fill="none" stroke="#309d67" stroke-width="7">
                <circle cx="48" cy="48" r="48" stroke="none"/>
                <circle cx="48" cy="48" r="44.5" fill="none"/>
                </g>
                <g id="Group_1" data-name="Group 1">
                <path id="Path_2" data-name="Path 2" d="M554,8207.49v29.931" transform="translate(-88 -8033.361)" fill="none" stroke="#309d67" stroke-linecap="round" stroke-width="5"/>
                <path id="Path_3" data-name="Path 3" d="M541.8,8246.06l13.07,13.069,13.07-13.069" transform="translate(-89 -8042)" fill="none" stroke="#309d67" stroke-linecap="round" stroke-width="5"/>
                </g>
            </g>
        </svg>
        
        <h1>Pay your debts</h1>
        
        <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea</p>
        
        <a href="#">Find out how</a>
            
    </div>
    
    <p class="obligation">There's no obligation!</p>

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
    background: #309D67;
    padding: .4em;
    font-family: 'Nunito', san-serif;
}

.card {
    background: white;
    border-radius: 1em;
    padding: 2.3em;
    text-align: center;
}

svg {
    width: 5em;
}

h1 {
    font-size: 1em;
    font-weight: normal;
}

.card p {
    font-size: .85em;
    color: #474747;
}

a { 
    display: inline-block;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5em;
    font-size: .8em;
}

.obligation {
    text-align: center;
    color: white;
    font-weight: bold;
    margin-bottom: 0;
}

/*

    Your fixes below:
    
    Use the following properties and rulesets
    to improve the visual hierarchy of this
    design
    
*/

body {
    padding: 1.5em;
}

svg {
    width: 2.7em;
}

h1 {
    font-size: 1.2em;
    font-weight: bold;
}

.card p {
    line-height: 1.9em;
    color: auto;
}

a {
    background: #e9e9e9;
    padding: .7em 2em;
    margin-top: 1em;
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
     
      <div class="card">
            
        <svg viewBox="0 0 96 96">
            <g id="down-arrow" transform="translate(-418 -150)">
                <g id="Ellipse_2" data-name="Ellipse 2" transform="translate(418 150)" fill="none" stroke="#309d67" stroke-width="7">
                <circle cx="48" cy="48" r="48" stroke="none"/>
                <circle cx="48" cy="48" r="44.5" fill="none"/>
                </g>
                <g id="Group_1" data-name="Group 1">
                <path id="Path_2" data-name="Path 2" d="M554,8207.49v29.931" transform="translate(-88 -8033.361)" fill="none" stroke="#309d67" stroke-linecap="round" stroke-width="5"/>
                <path id="Path_3" data-name="Path 3" d="M541.8,8246.06l13.07,13.069,13.07-13.069" transform="translate(-89 -8042)" fill="none" stroke="#309d67" stroke-linecap="round" stroke-width="5"/>
                </g>
            </g>
        </svg>
        
        <h1>Pay your debts</h1>
        
        <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea</p>
        
        <a href="#">Find out how</a>
            
    </div>
    
    <p class="obligation">There's no obligation!</p>

    </main>
    <footer></footer>
  </body>
</html>

```
