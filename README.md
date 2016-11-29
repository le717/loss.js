# loss.js #
> A JavaScript library for adding loss to any page

## API ##
* `loss.canvas(width=400, height=400)`: Return a <canvas> of specified size of loss.
* `loss.console()`: Print loss to the browser console.
* `loss.html()`: Return a loss string suitable for use in HTML.
* `loss.image()`: Return a PNG image of specified size of loss.
* `loss.string()`: Return a loss string.

## Usage ##
Do note lots of ES6/ES2015 features have been used, so unless you transpile,
a fairly modern browser is required.

1. ```html
<script src="loss.js"></script>
```

2. ```js
// Also available via window.loss
loss.string();  // loss
```

## License ##
[MIT](LICENSE)

2016 Caleb Ely
