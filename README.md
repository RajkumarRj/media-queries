# media-queries

Hosted link:https://rajkumarrj.github.io/media-queries/

![Uploading image.png…]()


Certainly! Here's a description of the HTML and CSS code you provided:

### HTML Structure:

- `<!DOCTYPE html>`: This declaration defines the document type and version of HTML being used.

- `<html lang="en">`: The root HTML element that encloses all the content on the web page. The `lang` attribute is set to "en" to indicate that the page is in English.

- `<head>`: The head section of the HTML document where metadata and links to external resources are placed.

    - `<meta charset="UTF-8">`: Specifies the character encoding for the document as UTF-8, which supports a wide range of characters and symbols.

    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport configuration to control the page's width and initial zoom level on different devices.

    - `<title>Media Queries</title>`: Defines the title of the web page that appears in the browser's title bar or tab.

- `<style>`: The opening tag for the inline CSS style definitions.

    - `*`: Selects all elements and sets some common CSS properties to reset default margins and padding.

    - `.top`: Defines a CSS class named "top" that styles the top section of the webpage.

    - `.bottom`: Defines a CSS class named "bottom" that styles the bottom section of the webpage.

    - `img`: Styles all `img` elements, positioning them absolutely on the page with different sizes based on media queries.

    - `@media (max-width:600px)`: This media query applies styles when the viewport width is 600 pixels or less. It adjusts the size and position of the `img`,
    - the position of the `article`, and font sizes for smaller screens.

    - `@media (min-width:601px) and (max-width:992px)`: This media query applies styles when the viewport width is between 601 and 992 pixels, adjusting the size and position of the `img` and `article`.

    - `@media (min-width:993px)`: This media query applies styles when the viewport width is 993 pixels or more, adjusting the size and position of the `img`.

- `<body>`: The body section of the HTML document contains the visible content of the web page.

    - `<div class="top">`: A `div` element with a class of "top" that represents the top section of the webpage.

    - `<div class="bottom">`: A `div` element with a class of "bottom" that represents the bottom section of the webpage.

    - `<img src="coffee.webp" alt="coffee">`: An `img` element displaying an image of coffee with the "coffee.webp" as the image source.

    - `<article>`: An `article` element containing content about certified coffee courses.

        - `<h1>`: A heading displaying "Certified Coffee Courses."

        - `<p>`: Paragraphs of text with Lorem Ipsum content.

        - `<p class="link">`: A paragraph with a class of "link" that contains a link to Freepik.

        - `<button type="submit">`: A button with the text "Learn more."

This code creates a responsive webpage with different styles and layouts based on the screen width, thanks to the defined media queries in the CSS.
