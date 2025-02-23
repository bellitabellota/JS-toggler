To install the npm package:
```
npm install https://github.com/bellitabellota/JS-toggler
```

To use this toggler:

- Import the Toggler into your javascript file or if using Webpack require it in the webpack.config.js file.

- Instantiate the Toggler class with 3 parameters.
  - First parameter is the DOM element that gets triggered via click,
  - the second is a DOM element whose CSS class  should get toggled,
  - the third parameter is the CSS class that shall be toggled.

Example:
```
const mainMenuDropdown = new Toggler(navToggler, navItems, "hidden");
```
