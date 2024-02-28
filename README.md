# Task

- Create a Contact List with 4 entries.
  - Use the data stored in App.jsx.
  - Use the images in the public folder.
- Use Google Fonts.

# Solution / Description:

---

## Preparation

- Project preparation:
  - Run `npm create vite@latest`.
    - Answer all questions for setup.
  - Install npm in the folder.
  - Initialize Git (`git init`). Check `.gitignore`.
  - Run `npm run dev`.

---

## General Description:

- `index.jsx` starts the application with a render call on component `<App />`.
- In `App.jsx`, there are subcomponents with their custom properties.
  - Each subcomponent calls a "helper function" to create HTML elements based on their properties.
- This job is done by the function "Contact" in "Contacts.jsx".
  - The function takes each "Contact" as a parameter and returns an object with HTML elements stored as strings.
- At the end, the `App` component stores an object with multiple objects inside, filled with strings representing each contact in HTML element syntax.

---

## File Description

- Starting point is `index.html`.

  - Header:
    - Link Google Fonts.
    - Link stylesheet.
  - Body:
    - Create a `div` as the root element.
    - Add a script source: `index.jsx`.

- `index.jsx`

  - Importing:
    - Import React & ReactDOM.
    - Import `App` (`App.jsx`).
  - Render `App` component:
    - `ReactDOM.render(<App />, document.getElementById("root"))`.

- `App.jsx`
  - Stores the custom properties and calls "Contacts" to create HTML elements using JSX syntax.
