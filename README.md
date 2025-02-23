To use this toggler:

- Import the Toggler into your file
- Instantiate the Toggler class with 3 parameters.
  - First parameter is the DOM element that gets triggered via click,
  - the second is a DOM element whose CSS class  should get toggled,
  - the third parameter is the CSS class that shall be toggled.

Example:
```
const mainMenuDropdown = new Toggler(navToggler, navItems, "hidden");
```
