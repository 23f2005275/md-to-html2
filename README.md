# Markdown Content Viewer

This project provides a simple, single-page HTML application (`index.html`) designed to render Markdown content from an `input.md` file dynamically. It leverages the power of Tailwind CSS for responsive styling and Marked.js for efficient Markdown to HTML conversion.

## Features

- **Dynamic Markdown Rendering**: Automatically fetches and converts `input.md` into beautifully formatted HTML.
- **Responsive Design**: Built with Tailwind CSS, ensuring a consistent and pleasant viewing experience across various devices and screen sizes.
- **Single-File Application**: Easy to deploy and use; simply open `index.html` in your web browser.
- **Lightweight**: Uses CDN versions of Tailwind CSS and Marked.js, requiring no build steps or complex setup.

## Getting Started

To use this Markdown viewer:

1.  **Save the files**: Ensure `index.html`, `input.md`, and `LICENSE` are all saved in the same directory.
2.  **Open `index.html`**: Double-click `index.html` in your web browser.

The `input.md` content will be automatically loaded and displayed as HTML.

## Technologies Used

-   **HTML5**: The structure of the web page.
-   **Tailwind CSS**: For utility-first CSS styling and responsive design. (Used via CDN)
-   **Marked.js**: A fast Markdown parser and compiler, used for converting `input.md` to HTML. (Used via CDN)
-   **JavaScript (ES6+)**: For fetching the Markdown file and interacting with the DOM.

## Customization

You can easily customize the appearance by modifying the Tailwind CSS classes within `index.html` or by adjusting the custom `<style>` block. To change the content, simply edit the `input.md` file.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
