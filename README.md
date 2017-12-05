# preset.css
CSS preset classes for interactive elements. These provide base component classes to build on. They include normalizations based on [normalize.css](https://github.com/necolas/normalize.css/blob/7.0.0/normalize.css) such as to not depend on element resets.

### Install via npm

```
npm install preset.css --save
```

### Import in SCSS

```scss
@import './node_modules/preset.css/preset';
```

### Import in Less

```less
@import (less) './node_modules/preset.css/preset.css';
```

## [Classes](preset.css)

- `.preset-color`
- `.preset-box`
- `.preset-input`
- `.preset-textarea`
- `.preset-label`
- `.preset-button`

## [Mixins](mixin.css)

```css
@include preset-color;
@include preset-box;
@include preset-input;
@include preset-textarea;
@include preset-label;
@include preset-button;
```
