# Styled Button

This project contains a simple styled button using HTML and CSS. The button is centered on the page and styled with a custom font, color scheme, and hover effect. It’s perfect for anyone looking to implement custom button designs on their website.

## Features

- **Custom Font**: The button uses a Google Font that can be customized.
- **Background Color**: The button has a bold black background.
- **Text Color**: The text color is light gray and changes to white on hover.
- **Gradient Border**: A beautiful gradient border surrounds the button.
- **Hover Effect**: When hovered, the button text color changes for added interactivity.

## Code Overview

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=FAMILY_NAME:wght@WEIGHT_OR_RANGE&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Button</title>
</head>
<body>
    <div class="container">
        <div class="button-border">
            <button type="button" class="button">
                My button
            </button>
        </div>
    </div>
</body>
</html>
```
 ### CSS Styles

```css

html, body {
    margin: 0;
    padding: 0;
}

:root {
    --font-family: 'Karla', sans-serif;
    --body-bg: #1E1F25;
    --btn-bg: #000;
    --btn-color: #cbcbcb;
    --btn-color-hover: #fff;
    --grad-color1: #eeaf61;
    --grad-color2: #fb9062;
    --grad-color3: #ee5d6c;
    --grad-color4: #ce4993;
    --grad-color5: #6a0d83;
}

body {
    background-color: var(--body-bg);
    font-family: var(--font-family);
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.button-border {
    padding: 5px;
    background: linear-gradient(to right, var(--grad-color1), var(--grad-color2), var(--grad-color3), var(--grad-color4), var(--grad-color5));
    border-radius: 8px;
}

.button {
    background-color: var(--btn-bg);
    color: var(--btn-color);
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
}

.button:hover {
    color: var(--btn-color-hover);
}
```
### How to Use
 Font Customization: Replace FAMILY_NAME and WEIGHT_OR_RANGE in the Google Fonts link to choose a different font family or font weight.
 Button Text: Edit the button text in the button tag to display any message you prefer.
 Colors: Adjust the color values in the :root variables to change the background, text, and gradient border colors.

### Future Improvements

- Add hover animations like button scaling or background transitions.
- Implement responsiveness for different screen sizes.
- Use JavaScript to trigger actions when the button is clicked.

Happy coding! 😄
Houda Belhad
Web Developer
