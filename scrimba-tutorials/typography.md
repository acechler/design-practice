# Typography

This lesson shows the importance of typography on a website. This can be used add visual aspect to important text to look at on the site.

```css
@import url('https://fonts.googleapis.com/css?family=Amatic+SC|Montserrat:400,700|Seymour+One&display=swap');

html, body {
    margin: 0;
    padding: 0;
}

.container{
    width: 95%;
    margin: 0 auto;
}

h1, p{
    font-size: 1em;
}
h1{
    margin: 2em 0 -.2em;
    font-family:'Seymour One', san-serif;
}
section{
    display: grid;
    grid-template-columns: repeat(3, auto);
    grid-gap: 1em;
    margin-top: 2em;
}
.card{
    background-color: #eeeeee;
    padding: 1.7em;
}

blockquote{
    margin: 0;
}

span {
    width: 70px;
    height: 70px;
    display: block;
    background: gray;
    border-radius: 50%;
    margin: 0 auto;
}
cite {
    font-style: normal;
    font-family: 'Amatic SC', cursive;
    font-size: 1.4em;
}

/* Overwrites */

h1, p, blockquote, cite {
    font-family: 'Montserrat';
}

h1 {
    font-size: 2em;
}

blockquote p {
    line-height: 1.5em;
}

cite {
    font-size: 0.7em;
    font-weight: bold;
    color: #373737;
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
          <h1>Our Testimonials</h1>
          <p class="subheading">See what our customers have to say about us.</p>
          <section>
            <div class="card">
              <span></span>
              <blockquote cite="http://someurlx0x.com">
                <p>I think this service is absolutely fantastic.</p>
                <cite>John Doe</cite>
              </blockquote>
            </div>
            <div class="card">
              <span></span>
              <blockquote cite="http://someurlx0x.com">
                <p>I think this service is absolutely fantastic.</p>
                <cite>John Doe</cite>
              </blockquote>
            </div>
            <div class="card">
              <span></span>
              <blockquote cite="http://someurlx0x.com">
                <p>I think this service is absolutely fantastic.</p>
                <cite>John Doe</cite>
              </blockquote>
            </div>
          </section>
        </div>
    </main>
  </body>
</html>


```


