# Task

- Create a a Contact List with 4 entrys.
  - Use the data stored in App.jsx
  - use the images in the public folder
- use google fonts

# Solution / Description:

---

## Preperation

- Project preperation
  - npm create vite@latest
    - answer all questions 4 Setup
  - install npm in the folder
  - git init !Check gitignore!
  - npm run dev

---

## General Description:

- index.jsx starts the Application with a Render Call on Component "<App />"
- In App.jsx are the Subcomponents with its custom Propertys
  - Each Subcomponent calls a "???" to create html elements based on there propertys.
- This job is done by the function "Contact" in "Contacts.jsx"
  - the fuction takes each "Contact" as Parameter and returns a Object with html elemets stored as Strings.
- at the end The Component App stores a Object with mutiple objects inside filled with strings representing each contact in html elemt sytax

---

## File description

- Starting point is "index.html"

  - header:
    - link google fonts
    - link stylesheet
  - body:
    - create a div as root element
    - add a script src index.jsx

- index.jsx

  - Importing
    - import React & ReactDOM
    - import App (App.jsx)
  - Render App component
    - ReactDOM.render(App, in the "root")

- App.jsx
  -
