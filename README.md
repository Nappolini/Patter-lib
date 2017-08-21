###  project 

Pattern Library 

I am building the site using OOCSS (Modules), Atomic CSS (clean code base) and SMACSs (file structure) and BEM (Naming convention). 

The site is built with includes so each component can be removed without affecting the remainder of the page.  Want to include a testimonail- Include it in the .html file add it to the pug files and scss files. 

This is going to be a modular system built ontop of prebuilt UI cards that can be added to the project to quickly prototype a layout. 

Each component has minimal styling and uses atomic css for general stytling this is prefixed with a. 

```css
.a-propertyName{ }
```
The leading principle is that this pattern library is not defined by a grid system. Add the css classes to your html markup and the UI element will comply with the grid, grid system or grid frame work that you are using. 
