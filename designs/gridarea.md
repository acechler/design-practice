# Grid Area Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Document</title>
  </head>
  <body>
    <header>Header</header>
    <main>
      <div class="container">
        <div class="sidebar">
          <h3>Side Message</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Neque quae
            doloribus, possimus veniam ratione iste molestiae. Dolorem aliquam
            voluptatem itaque! Assumenda rerum ipsum animi, ducimus omnis
            reiciendis. Debitis, porro aspernatur.
          </p>
        </div>
        <div class="content">
          <h3>hello</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis
            illo omnis quod voluptates, laborum rerum deserunt eligendi animi
            commodi quam ex voluptatum laboriosam sequi nobis molestiae placeat,
            aspernatur sit ratione!
          </p>
        </div>
        <div class="answers">
          <h3>Answers</h3>
        </div>
      </div>
    </main>
    <footer>Footer</footer>
  </body>
</html>

```


```css

.container {
    display: grid;
    grid-template-areas:
        'sidebar content content'
        'answers answers answers';
    gap: 10px;
}

.sidebar {
    grid-area: sidebar;
    background-color: #ffa08c;
    padding: 20px;
    text-align: center;
    border: 1px solid #000;
}
.content {
    grid-area: content;
    background-color: #8cff8c;
    padding: 20px;
    text-align: center;
    border: 1px solid #000;
}
.answers{
    grid-area: answers;
    background-color: azure;
    padding: 20px;
    text-align: center;
    border: 1px solid #000;
}

```