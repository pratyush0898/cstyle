# cstyle

**Cascading Styles**

`cstyle` is a CSS framework that's an Alternative of bootstrap, allowing you to enhance the styling of your web applications effortlessly.

## Installation

You can install `cstyle` via npm:

```bash
npm install cstyle
```

## Usage

### JavaScript

Once installed, you can import `cstyle` into your JavaScript file and start using the  Cstyles:

```javascript
// Import the CSS directly into your JavaScript
import 'cstyle';

// Start using the styles

function App() {
    return (
        <a href='#' class='but' /* Button */> Hello <a />
    )
}

```

*or*

### Import css
If theJavascript methord dosent work you can import `csX.css` file and start using the `csX.css` styles:
```javascript
import './node-module/cstyle/css/csX.css';
// or
import '/cstyle/css/csX.css';
```

### HTML

You can also include the `csX.css` file directly in your HTML file using a `<link>` tag:

```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/cstyle@1.8.6/css/csX.css">
```

Now you can use the `csX.css` styles in your project to create visually appealing and responsive designs.

**Javascript**
For some design Your cam import JavaScript using `<script>` tag:
```html
<script src="https://unpkg.com/cstyle@1.8.6/csX.min.js.map.css"></script>
```

## Features

- Simplified styling: Easily apply styles to your HTML elements using utility classes.
- Responsive design: Create responsive layouts with ease using built-in responsive utilities.
- Customization: Customize and extend the CSS with your own styles or override existing ones.

## License

This package is licensed under the Apache 2.0 License. See the [LICENSE](https://unpkg.com/cstyle@1.8.6/LICENSE) for details.

## Author

This package is maintained by [nvmPratyush](https://www.npmjs.com/~nvmpratyush).