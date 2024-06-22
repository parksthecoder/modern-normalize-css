# modern-normalize-css v1.0.3

![Normalize Logo](https://necolas.github.io/normalize.css/logo.svg)

A MODERN alternative to CSS resets - This is a fork inspired by the original normalize.css created by Nicolas Gallagher and Jonathan Neal over 8 years ago with some modernized changes to improve readability, compatibility with modern browsers, and to simplify the codebase.

[![license](https://img.shields.io/npm/l/normalize.css.svg)](https://github.com/necolas/normalize.css/blob/master/LICENSE.md)

### Manual

## NPM

```
npm install modern-normalize-css
```

## Yarn

```
yarn add modern-normalize-css
```

## Bun

```
bun add modern-normalize-css
```
Simply copy the `styles/normalize.css` file to your project and use it as you would the original normalize.css file in the root of the project.

## Usage

### Import in CSS

Add the following line to your main CSS file:

```css
@import "modern-normalize-css/styles/normalize.css";
```

### Import in JavaScript/TypeScript

Add the following line to your main JavaScript or TypeScript file:

```js
import "modern-normalize-css/styles/normalize.css";
```

## Download

GitHub: [https://github.com/parksthecoder/modern-normalize-css](https://github.com/parksthecoder/modern-normalize-css)

NPM: [https://www.npmjs.com/package/modern-normalize-css](https://www.npmjs.com/package/modern-normalize-css)

See (for older Original normalize.css version) [https://necolas.github.io/normalize.css/latest/normalize.css](https://necolas.github.io/normalize.css/latest/normalize.css)

## What does it do?

- Preserves useful defaults, unlike many CSS resets.
- Normalizes styles for a wide range of elements.
- Corrects bugs and common browser inconsistencies.
- Improves usability with subtle modifications.
- Explains what code does using detailed comments.

## Modern Browser support

- Chrome
- Edge
- Firefox ESR+
- Internet Explorer 10+
- Safari 8+
- Opera

## Extended details and known issues

### `pre`, `code`, `kbd`, `samp`

The `font-family: monospace, monospace` hack fixes the inheritance and scaling of `font-size` for preformatted text. The duplication of `monospace` is intentional. [Source](https://github.com/necolas/normalize.css/blob/master/normalize.css#L102).

### `sub`, `sup`

Normally, using `sub` or `sup` affects the line-box height of text in all browsers. [Source](https://github.com/necolas/normalize.css/blob/master/normalize.css#L146).

### `select`

By default, Chrome on OS X and Safari on OS X allow very limited styling of `select`, unless a `border` property is set. The default font weight on `optgroup` elements cannot safely be changed in Chrome on OSX and Safari on OS X.

### `[type="checkbox"]`

It is recommended that you do not style `checkbox` and `radio` inputs as Firefox's implementation does not respect `box-sizing`, `padding`, or `width`.

### `[type="number"]`

Certain font size values applied to number inputs cause the cursor style of the decrement button to change from default to text.

### `[type="search"]`

The search input is not fully stylable by default. In Chrome and Safari on OSX/iOS you can't control `font`, `padding`, `border`, or `background`. In Chrome and Safari on Windows you can't control `border` properly. It will apply `border-width` but will only show a border color (which cannot be controlled) for the outer 1px of that border. Applying `-webkit-appearance: textfield` addresses these issues without removing the benefits of search inputs (e.g. showing past searches).

### `button`, `[type="button"]`, `[type="reset"]`, `[type="submit"]`

Correct the inability to style clickable types in iOS and Safari. Remove the inner border and padding in Firefox.

### `fieldset`

Correct the padding in Firefox.

### `legend`

Correct the text wrapping in Edge and IE. Correct the color inheritance from `fieldset` elements in IE. Remove the padding so developers are not caught out when they zero out `fieldset` elements in all browsers.

### `progress`

Add the correct vertical alignment in Chrome, Firefox, and Opera.

### `textarea`

Remove the default vertical scrollbar in IE 10+.

### `details`, `summary`

Add the correct display in Edge, IE 10+, Firefox, and all browsers for `details` and `summary`.

### `template`, `[hidden]`

Add the correct display in IE 10+ for `template` and elements with the `hidden` attribute.

## Changes in this version

- **Updated Line-Height**: Changed from `1.5` to `1.375rem` for better readability.
- **Safe Area Insets**: Added support for safe area insets to accommodate devices with notches or rounded corners.
- **Font Definitions**: Updated root-level font definitions for a more modern and consistent look.
- **Consistent Line-Height**: Ensured consistent line-height across various elements.
- **Modern Browser Features**: Considered modern browser features and compatibility.
- **Detailed Comments**: Added detailed comments to explain the purpose of each rule.

### Comparison with Old Normalize.css (v8.0.1)

- **Line-Height**: Updated from `1.5` to `1.375rem` for improved readability.
- **Safe Area Insets**: Added padding for safe area insets to support modern devices.
- **Font Definitions**: Modernized font definitions for better consistency.
- **Consistent Line-Height**: Applied consistent line-height across all elements.
- **Modern Browser Features**: Enhanced support for modern browser features.
- **Detailed Comments**: Improved comments for better understanding and maintainability.