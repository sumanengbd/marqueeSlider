# Marquee Slider jQuery Plugin

The Marquee Slider jQuery Plugin is a lightweight and customizable plugin for creating a marquee-style slider with the ability to repeat items. It smoothly adjusts the position of items based on the user's scroll behavior, creating an engaging scrolling effect.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Options](#options)
- [Example](#example)
- [License](#license)

## Installation

Include jQuery and the `marqueeSlider.js` script in your HTML file:

```html
<!-- jQuery -->
<script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>

<!-- Marquee Slider Plugin -->
<script src="path/to/marqueeSlider.js"></script>
```

## Usage

Apply the Marquee Slider plugin to the target elements:

```html
$('.marquee-slider').marqueeSlider([
  { sensitivity: 0.1, repeatItems: true },
  { sensitivity: 0.5, repeatItems: true },
]);
```
## Options

The plugin supports the following options:

sensitivity: Controls the speed of scrolling based on the user's scroll. Default is 0.1.
repeatItems: Determines whether the items in the slider should be repeated. Default is true.

## Example

```html
<div class="marquee-slider">
  <ul class="marquee-slider__list">
    <li class="marquee-slider__list--item">Item 1</li>
    <li class="marquee-slider__list--item">Item 2</li>
    <!-- Add more items as needed -->
  </ul>
</div>

<div class="marquee-slider">
  <ul class="marquee-slider__list">
    <li class="marquee-slider__list--item">Item 1</li>
    <li class="marquee-slider__list--item">Item 2</li>
    <!-- Add more items as needed -->
  </ul>
</div>

<script>
  $('.marquee-slider').marqueeSlider([
    { sensitivity: 0.1, repeatItems: true },
    { sensitivity: 0.5, repeatItems: true },
  ]);
</script>
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

```html
Replace `"path/to/marqueeSlider.js"` with the actual path to your plugin file, and make sure to include the correct jQuery version. Additionally, if there are specific license terms or usage instructions you want to convey, you can update the README accordingly.
```
