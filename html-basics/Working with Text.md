# Working with Text in HTML

## Key Concepts:

1. **Paragraphs:**
   - To create paragraphs, wrap text with the `<p>` tag.
   - Without `<p>`, text will be clumped together despite new lines in the code.

   `<p>This is a paragraph of text.</p>`

2.	Headings:
    - Headings range from <h1> to <h6>, with <h1> being the largest and most important, and <h6> the smallest.
    - Each level of heading signifies content hierarchy.
    ```
    <h1>Main Heading</h1>
    <h2>Subheading</h2>
    ```

3.	Bold and Important Text (Strong):
    - Use <strong> to bold text that holds semantic importance.

    `<p>This is <strong>important</strong> text.</p>`


4.	Italicized and Emphasized Text (Em):
    - Use <em> to italicize text, adding emphasis and semantic importance.

    `<p>This is <em>emphasized</em> text.</p>`


5.	Nesting Elements:
    - HTML elements can be nested, creating parent-child relationships. For example:
    ```
    <body>
    <p>This paragraph is a child of the body element.</p>
    </body>
    ```

6.	HTML Comments:
    - Use comments to add notes to your code, which won’t be displayed in the browser:
    `<!-- This is a comment -->`
