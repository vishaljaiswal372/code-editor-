## Introduction

CODE_EDITOR is a lightweight browser-based code playground designed to help developers experiment with and prototype HTML, CSS, and JavaScript code in real time. By providing an integrated and responsive web interface, this project aims to simplify the process of designing web pages and testing code snippets without the need for server-side components. Whether you are a beginner learning web development or a seasoned developer prototyping ideas, CODE_EDITOR offers a streamlined environment supporting immediate feedback and collaboration.

---

## Requirements

- **Browser Support**  
  The editor is designed for modern web browsers. It requires a browser that supports:
  - Modern JavaScript (ES6) features
  - The Clipboard API for copying text
  - Iframes for isolated code execution

- **Environment**  
  Since the editor is purely client-side, no special server environment is needed. It runs locally by simply opening the `index.html` file.

- **Optional Tools**  
  For further development or customization, you may use any modern code editor or development environment that supports HTML, CSS, and JavaScript. Tools such as Git may be used for version control of the project files.

---

## Features

- **Multi-Language Code Editor**  
  The editor supports three languages—HTML, CSS, and JavaScript—and provides separate input areas for each.

- **Real-Time Preview**  
  The output of the combined code is rendered instantly in an iframe. This preview supports dynamic updates when the code is saved.

- **Copy to Clipboard**  
  Integrated Copy buttons for each code section enable users to quickly copy code snippets for reuse.

- **Responsive Design and Full View Toggle**  
  The output container can be expanded to a full view with a dedicated button, enhancing the preview experience.

- **Simple and Intuitive Interface**  
  The minimalist design of the interface makes it ideal for learning, prototyping, and experimenting with web code.

---

## Usage

- **Launching the Editor**  
  Open the `index.html` file in your favorite web browser to launch the code editor interface. The page loads three main code input areas for HTML, CSS, and JavaScript.

- **Editing Code**  
  In the visible interface, you will find three sections:
  - **HTML Editor:** Enter HTML code in the text area.
  - **CSS Editor:** Enter CSS code in the text area.
  - **JS Editor:** Enter JavaScript code in the text area.

- **Running Code**  
  After editing, click the **Save** button to render your code. When you click the Save button, the HTML content is injected into an iframe, the CSS is applied dynamically via a style tag inserted in the head, and the JavaScript is executed within the context of the output frame.

- **Previewing and Toggling Output**  
  The rendered output appears in a dedicated output container. To toggle the preview to a full view, click on the **Full** button. This action toggles a CSS class that expands the output container for an immersive preview experience.

- **Copying Code**  
  Each code editor section is equipped with a **Copy** button. Clicking the Copy button in any section copies the corresponding code (HTML, CSS, or JS) to the clipboard for ease of reuse.

---

## Configuration

- **File Structure**  
  The project is primarily organized with the following key files:
  - `index.html`: The main HTML file that sets up the structure of the editor interface and links to CSS and JavaScript resources.
  - `style.css`: The styling file that controls the look and feel of the editor, including layout, colors, and transitions.
  - `sript.js`: The JavaScript file that powers the functionality of the editor, handling events such as saving code, toggling the output view, and copying code to the clipboard.

- **Assets**  
  This project includes several image assets (e.g., icons for HTML, CSS, JS, Copy, Save, and Full view) that are referenced in the HTML file. Make sure these assets are located in the correct directory relative to the HTML file for proper display.

- **Customization**  
  To adjust the behavior or appearance of the editor:
  - Modify `style.css` for design changes.
  - Change or extend the logic in `sript.js` if you need additional functionality.
  - The file paths in the HTML file can be updated to suit different directory structures if necessary.

---
