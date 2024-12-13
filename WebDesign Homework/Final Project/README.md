# Final Project Website

## Project Overview
This website was created as part of my Final Project. It includes the following elements:
- A user-friendly, multi-page layout.
- An external stylesheet for styling.
- Embedded media and images.
- Semantic and well-organized HTML structure.

## Techniques and Implementation
### Techniques Used
1. **External Stylesheet**
   - **Why**: To separate content from design and allow for consistent styling across pages.
   - **How**: Linked a `styles.css` file to all HTML pages.

2. **Custom Font**
   - **Why**: To enhance visual appeal and align with the website's theme.
   - **How**: Integrated Google Fonts for custom typography.

3. **Images**
   - **Why**: To add visual interest and support the website's content.
   - **How**: Used fair-use images and optimized them for web use.

4. **Embedded Media**
   - **Why**: To make the website more interactive and engaging.
   - **How**: Added a Google Map to the contact page.

5. **Semantic HTML**
   - **Why**: To improve accessibility and maintain a clean structure.
   - **How**: Used `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, and more appropriately.

6. **GitHub Integration**
   - **Why**: To track changes and host the project online.
   - **How**: Used GitHub Desktop to push updates and deployed the website using GitHub Pages.

---

### **2. Create Your Pages**
1. Inside the `FinalProject` folder, create the following files:
   - `index.html` (Home page)
   - `about.html` (About page)
   - `contact.html` (Contact page)
2. Structure each page with semantic HTML. For example:

**index.html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home | Final Project</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Welcome to My Website</h1>
    <p>This is the homepage of my Final Project.</p>
  </main>
  <footer>
    <p>&copy; 2024 Final Project. All rights reserved.</p>
  </footer>
</body>
</html>
