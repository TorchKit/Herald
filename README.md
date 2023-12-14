# Herald

This repo contains a single HTML page with some pre-built formatting and styling around an `<img>` tag. 
This `<img>` tag is then designed to receive a code screenshot from a utility like Polaroid or ShowCode.
The page can then be exported from the web browser as a complete image and shared on social media.

## Usage

1. Download the [index.html](index.html) file.
2. Open the HTML file and delete the `<footer>` tag (this removes any TorchKit branding).
3. Export a code screenshot using your app or site of choice e.g. [ShowCode](https://showcode.app).
4. Make sure the screenshot is in the same directory as the HTML file and that it is named `code.png`.
5. View the HTML file in your web browser, then open dev tools / web inspector.
6. Find the `<section>` tag, then right click on it and export / capture the node as a screenshot.
7. Post on social media or wherever you like :)

## Suggestions

1. Make sure that the exported screenshot is not rounded.
2. Make sure that the exported screenshot does not contain any padding, margin or spaces.
3. Make sure that the exported screenshot does not include any traffic lights or headers (unless you want them).

## License

The repository is open-sourced software licensed under the [MIT license](LICENSE.MD).
