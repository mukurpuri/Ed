# Ed


### Approach to Accessibility:
1. #### Navigation and Focus:
Keyboard Navigation: The page is navigable using only the keyboard. All interactive elements such as links, form fields, and buttons are reachable and operable using the Tab key and other keyboard shortcuts.
Focus States: We have ensured that focus states are clearly visible (e.g., underline links, highlight form fields).

2. #### ARIA Roles and Properties:
ARIA Roles: Used aria-labelledby on the form to describe its purpose.
ARIA-live Regions: Added aria-live="assertive" to the error message container to announce validation errors dynamically.

3. #### Alt Text:
All images used have meaningful alt attributes.

4. #### Color Contrast:
Text and background colors have sufficient contrast ratios. For the header and footer, a contrast ratio of at least 4.5:1 against the background color has been maintained. The buttons also have a text color with a contrast for maximum visibility.

5. #### Skip Navigation Links:
Added a skip link section at the top of the page, which gets visible only when focused through tab navigation. Clicking on skip links will then help jumpt to main section.

6. #### Form Validation:
Used HTML5 validation with required attributes on input fields.
The aria-live region will dynamically announce form errors if validation fails.

