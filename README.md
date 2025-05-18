# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

index.html 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Blog</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="post.html">Blog Post</a></li>
        <li><a href="about.html">About</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Welcome to My Blog</h1>
    <article>
      <h2><a href="post.html">How to Learn JavaScript</a></h2>
      <p>This post shares tips for mastering JavaScript for web development.</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
HTML5 Semantic

body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

nav ul {
  list-style: none;
  display: flex;
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

article {
  padding: 20px;
}

@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
  }
}
style.css

body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

nav ul {
  list-style: none;
  display: flex;
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

article {
  padding: 20px;
}

@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
  }
}


Good luck and happy coding! 🚀💻
