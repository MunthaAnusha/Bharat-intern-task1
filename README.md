

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>This is where you can write about yourself, your skills, experiences, and anything else you'd like visitors to know.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>Description of project 1.</p>
    </div>
    <div class="project">
      <h3>Project 2</h3>
      <p>Description of project 2.</p>
    </div>
    <!-- Add more project divs as needed -->
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>You can reach me at example@email.com</p>
  </section>

  <footer>
    <p>&copy; 2024 My Portfolio</p>
  </footer>
</body>
</html>
```

And the accompanying CSS (styles.css):

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

section {
  padding: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
```
