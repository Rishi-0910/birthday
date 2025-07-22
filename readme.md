# Happy Birthday Animation

This project displays a festive "Happy Birthday" animation using HTML5 Canvas and JavaScript. Each letter animates with fireworks and balloons, creating a celebratory effect.

## Features

- Animated fireworks for each letter
- Balloons that float up after the fireworks
- Customizable message (edit the message in the JavaScript)
- Responsive to window resizing

## Getting Started

1. **Clone or Download** this repository to your local machine.
2. **Open `index.html`** in your web browser.

## Customization

To change the birthday message, edit the `opts.strings` array in [`script.js`](script.js):

```js
// script.js
opts = {
  // change the text in here //
  strings: ["HAPPY", "BIRTHDAY!", "to You", "[NAME]"],
  // ...other options...
}
```

## Project Structure

- [`index.html`](index.html): Main HTML file.
- [`style.css`](style.css): Styles for the canvas and page.
- [`script.js`](script.js): Animation logic and configuration.

## Requirements

- Modern web browser with JavaScript enabled.

## License

This project is for personal and