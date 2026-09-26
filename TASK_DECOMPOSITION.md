# Exercise 1 — Semantic DOM Architecture & A11y Contract

## WBS task T-01

**Task:** Build the page's semantic landmark tree in `index.html`.

### Contract

- Use native `header`, `nav`, `main`, `section`, `article`, and `footer` elements where they describe the content.
- Use zero `<div>` elements.
- Provide exactly one `h1`; keep section headings at `h2`.
- Place a visible-on-focus skip link before the site header and point it to `#main-content`.
- Ensure every navigation target exists in the document.
- Keep this milestone limited to HTML; do not combine it with CSS or JavaScript.

### Acceptance checks

1. `index.html` contains one `h1` and no `div` elements.
2. The accessibility tree exposes banner, navigation, main, and content-info landmarks.
3. Activating “Skip to main content” reaches the main landmark.
4. Navigation links reach About, Projects, and Contact.

### Atomic commit

```text
feat(html): semantic landmark tree
```
