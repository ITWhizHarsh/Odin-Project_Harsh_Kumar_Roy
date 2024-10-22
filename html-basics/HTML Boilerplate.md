# HTML Boilerplate

## Introduction
- Every HTML document has a basic structure (boilerplate) that is required to start any web development.

## Creating an HTML File
- Create a folder named `html-boilerplate` and a file named `index.html`.
- Use the `.html` extension to tell the system it’s an HTML file.
- Always name the homepage file `index.html`.

## DOCTYPE Declaration
- **Purpose**: Tells the browser to use HTML5.

`<!DOCTYPE html>`

## HTML Element

- Root element: Contains all other elements.
```
<html lang="en">
</html>
```
- lang Attribute: Defines the language of the document for accessibility.

## Head Element

- Purpose: Contains meta-information and resources (e.g., charset, title).
```
<head>
  <meta charset="UTF-8">
  <title>My First Webpage</title>
</head>
```
- <meta charset="utf-8">: Ensures proper display of special characters.
- <title>: Gives the page a title shown in the browser tab.

## Body Element

- Purpose: Contains all content visible to users.

<body>
  <h1>Hello World!</h1>
</body>

## Opening HTML in a Browser

- Use Google Chrome. Options include:
	1.	Drag and drop the HTML file into the browser.
	2.	Double-click the file.
	3.	Use the terminal to open the file in the browser (commands vary by OS).

## VSCode Shortcut

- Type ! and press Enter to auto-generate the boilerplate code.
- Includes an additional line for responsive design:

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`
