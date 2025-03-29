# Dropdown Toggle

A simple and lightweight npm package to create dropdown toggles.

## Installation

```bash
npm install pls-dropdown
```

## Usage

### HTML

```html
<button id="button">Toggle Dropdown</button>
<ul id="list">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

### CSS

```css
.hidden {
  display: none; // Add this class
}
```

### JavaScript

```javascript
import dropdown from 'pls-dropdown';

dropdown('button', 'list'); // call it where needed
```

## Features

- **Lightweight:** Minimal dependencies and small bundle size.
- **Simple API:** Easy to integrate into any project.
- **Toggle Behavior:** Toggles the visibility of the dropdown content.

## Options

The `dropdown` constructor accepts two arguments.

```javascript
dropdown(toggleBtnId, contentId);
```

## License

ISC
