# Website Optimization Project


Portfolio Optimizations:

1. Resize pizzeria.jpg using <a href="https://www.npmjs.com/package/gulp-image-resize">gulp-image-resize</a>.
2. Optimize images using <a href="https://www.npmjs.com/package/gulp-imagemin">gulp-imagemin</a> (ImageMagick).
3. Remove print.css from CRP by adding media="print".
4. Inline style.css to index.html using <a href="https://www.npmjs.com/package/gulp-inline-source">gulp-inline-source</a>.
5. Remove scripts from CRP by adding them to the bottom of index.html and running them async.
6. Inline perfmatters.js using <a href="https://www.npmjs.com/package/gulp-inline-source">gulp-inline-source</a>.
7. Minify HTML/CSS/JS in index.html using <a href="https://github.com/jonschlinkert/gulp-htmlmin">gulp-htmlmin</a> (remove comments and whitespace).
8. Replace 'Open Sans' font with sans serif.

Pizzeria Optimizations:

1. Replace querySelectAll with more specific selectors like getElemetById and getElementByClassName. (https://github.com/jquery/standards/issues/4)
2. Cache/calculate randomPizzaContainer, dx, newwidth, pizzasDiv, items and part of phase outside of loops.
3. Render just 20 pizzas on screen instead of 200 (only 20 are visible at any time).
4. Calculate loop lengths only once (minor improvement).