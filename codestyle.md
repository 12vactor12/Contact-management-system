# Code Style Guide for Front-End Development

## Sources
This code style guide is based on:
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [jQuery Documentation](https://learn.jquery.com/)

---

## General Guidelines
1. **Consistent Naming Conventions**
   - Use `camelCase` for JavaScript variables and functions.
   - Use `kebab-case` for CSS class names.

2. **HTML Structure**
   - Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.) where applicable.
   - Properly indent nested elements with two spaces.

3. **CSS Guidelines**
   - Use Bootstrap's built-in classes as much as possible to maintain consistency and reduce custom CSS.
   - Keep custom styles in a separate CSS file.
   - Use comments to group related styles and explain complex styles.

4. **JavaScript Guidelines**
   - Use `let` and `const` instead of `var` for variable declarations.
   - Write functions using arrow syntax when appropriate.
   - Use jQuery methods for DOM manipulation instead of native JavaScript when applicable for better cross-browser compatibility.
   - Always wrap jQuery code in `$(document).ready(function() { ... });` to ensure the DOM is fully loaded before running scripts.

## Specific Guidelines

### Bootstrap
- Always include Bootstrap's CSS and JavaScript files from a CDN or your own server.
- Utilize Bootstrap grid system for responsive design:
  ```html
  <div class="container">
      <div class="row">
          <div class="col-md-6">...</div>
          <div class="col-md-6">...</div>
      </div>
  </div>
