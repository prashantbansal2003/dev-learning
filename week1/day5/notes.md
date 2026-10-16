- **Why is the aside inside main?**
  The `<aside>` is inside `<main>` because its content (related links about Git) is tangentially related to the primary content of the page (the article about learning Git).

- **Why is Related links an h2?**
  It is an `<h2>` because it serves as the heading for the `<aside>` section, establishing a proper document structure and acting as the accessible label via `aria-labelledby="related-heading"`.

- **Which element did you hesitate over, and why?**
  I hesitated over whether to place the `<aside>` inside or outside `<main>`. I chose to put it inside because the links directly support the primary subject matter of the main content area rather than being global site-wide sidebars.

- **which controls need fieldset/legend?**
  Controls that group related options together, such as radio buttons and checkboxes, need a `<fieldset>` and `<legend>` to provide accessible context for screen readers.

- **why a placeholder isn't a label?**
  A placeholder is not a label because it disappears once text is entered, lacks semantic permanence, and often fails contrast and accessibility standards.

- **why server-side validation is still needed?**
  Server-side validation is still needed because client-side validation can be easily bypassed, disabled, or manipulated by users, meaning security and data integrity must always be enforced on the server.
