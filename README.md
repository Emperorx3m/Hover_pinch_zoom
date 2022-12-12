# Hover_pinch_zoom

HoverPinchZoom is a Javascript library providing touch gestures for zooming and dragging on image elements on mobile And mouse gestures for deep zooming on devices that use mouse.

## Installation

- Use the [NPM package](https://www.npmjs.com/package/mouse_hover_pinch_zoom).
- Download and add to your project and Link directly.


## Usage

### Requirements
* No dependencies, built with vanilla JS.
* A modern browser (ECMA 5 support, http://caniuse.com/use-strict).

### Initialisation

### html

```html
<div id="parent_div_of_image" style="width:30vw; height: 70vh;">
    <img class="mob" src="mannq.png"/>
</div>
```

```Javascript
var el = document.querySelector('#parent_div_of_image');
init_zoom(el);

```

## Troubleshooting

- If you have issues with invisible images, make sure that the image isn't absolutely positioned.
  In some cases that will cause trouble.
- Make sure you set dimensions for the parent div of the image

## License

Licensed under the [MIT License](http://opensource.org/licenses/MIT).

## Github Page with demo

https://#
