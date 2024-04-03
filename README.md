# Astronomy Website Project

This project is a simple website about galaxies, showcasing three famous galaxies: the Cigar Galaxy (M82), the Pinwheel Galaxy (M101), and the Sombrero Galaxy (M104). Each galaxy is accompanied by a brief description.

## HTML Structure

The HTML file (`index.html`) has the following structure:

- `<!DOCTYPE html>` declaration
- `<html>` element with `lang="en"`
- `<head>` section containing metadata such as charset and title
- External CSS stylesheet linked (`style.css`)
- `<body>` section containing the content of the website
    - Header (`#header`) with a background image and the website logo (`#logo`)
    - Container (`#container`) holding information about each galaxy
        - Rows (`div.row`) containing an image of the galaxy and its description (`div.rowT`)
            - Galaxy image (`#m82`, `#m101`, `#m104`)
            - Galaxy description (`h2` for the title and `p` for the description)

## CSS Styling

The CSS file (`style.css`) contains styling rules for various elements:

- Body background color set to black
- Header (`#header`) styled with a gray background, a background image, and padding for spacing
- Logo (`#logo`) centered horizontally with 10% width
- Heading (`h1`) styled with white color, centered text, and custom font
- Container (`#container`) positioned with margins and using a sans-serif font
- Galaxy images (`#m82`, `#m101`, `#m104`) floated to the left with specific dimensions, margins, and border radius
- Galaxy descriptions (`div.rowT`) styled with padding, background color, and justified text alignment

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion

This project provides a visually appealing way to learn about three notable galaxies, with concise descriptions and attractive styling.
