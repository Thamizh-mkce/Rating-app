# Rating App

This project is an interactive emoji rating system that allows users to express their feedback using emojis and star ratings. The project is built using HTML, CSS, and JavaScript, and it utilizes Font Awesome icons for the emojis and stars.

## Project Structure

- `index.html`: The main HTML file that structures the rating system.
- `style.css`: The CSS file that styles the feedback container, emojis, and star ratings.
- `index.js`: The JavaScript file that handles the interactivity of the rating system.

## Files

### `index.html`

This is the main HTML file that contains the structure of the emoji rating system. It includes:

- A `div` container with the class `feedback-container`, which houses both the emoji and rating containers.
- A `div` with the class `emoji-container`, containing five Font Awesome icons representing different emotions (angry, frown, meh, smile, laugh).
- A `div` with the class `rating-container`, containing five Font Awesome star icons, where one star is initially active.
- Links to the Font Awesome CDN for icons and the `style.css` file for styling.
- A script tag that links to the `index.js` file for functionality.

### `style.css`

This file contains the styling rules for the emoji rating system, including layout, colors, spacing, and hover effects.

### `index.js`

This file contains the JavaScript logic that handles the interaction with the rating system. It includes:

- Event listeners to detect user clicks on the stars.
- Logic to update the active star rating based on user input.
- Additional functionality for updating the emoji display according to the selected star rating.

## Usage

1. Clone or download this repository.
2. Open the `index.html` file in your web browser to view and interact with the emoji rating system.

## Customization

You can customize the appearance and functionality of the rating system by editing the `style.css` and `index.js` files. You can change the emojis, add more icons, or modify the rating scale as needed.

## Dependencies

- [Font Awesome](https://fontawesome.com) for the emoji and star icons. The project links to the Font Awesome CDN, so no local installation is required.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
