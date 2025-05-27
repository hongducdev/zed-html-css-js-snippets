# HTML + CSS + JS Snippets for Zed Editor

A collection of useful HTML, CSS, and JavaScript snippets to speed up your web development workflow in Zed Editor.

## Features

### HTML Snippets

#### Layout Components

| Prefix           | Description                                |
| ---------------- | ------------------------------------------ |
| `html-menu`      | Navigation menu structure                  |
| `html-dropdown`  | Dropdown menu with toggle                  |
| `html-modal`     | Modal dialog with header, body, and footer |
| `html-tab`       | Tabbed interface                           |
| `html-accordion` | Accordion component                        |
| `html-box-item`  | Box layout with image and content          |

#### Forms

| Prefix                | Description             |
| --------------------- | ----------------------- |
| `html-search`         | Search form with icon   |
| `html-subscribe-form` | Email subscription form |

#### Content Components

| Prefix               | Description              |
| -------------------- | ------------------------ |
| `html-linkwrap-img`  | Image wrapped in link    |
| `html-list-item`     | List item with icon      |
| `html-footer-column` | Footer column with links |

#### External Resources

| Prefix              | Description              |
| ------------------- | ------------------------ |
| `html-slick-css`    | Slick Carousel CSS       |
| `html-favicon`      | Favicon links            |
| `html-ionicons`     | Ionicons integration     |
| `html-slick-slider` | Slick Carousel scripts   |
| `html-fontawesome`  | Font Awesome integration |

### CSS Snippets

#### Layout & Positioning

| Prefix                                       | Description                |
| -------------------------------------------- | -------------------------- |
| `h-screen`, `w-screen`, `min-h-screen`       | Viewport dimensions        |
| `center-block`, `center-flex`, `center-grid` | Centering elements         |
| `flex-row`, `flex-column`                    | Flexbox directions         |
| `abs-center`, `fixed-full`                   | Absolute/Fixed positioning |

#### Box Shadows

| Prefix                         | Description           |
| ------------------------------ | --------------------- |
| `get-shadow1` to `get-shadow5` | Beautiful box shadows |

#### Text Styling

| Prefix                                 | Description                 |
| -------------------------------------- | --------------------------- |
| `text-truncate`                        | Text overflow with ellipsis |
| `text-gradient`                        | Gradient text effect        |
| `uppercase`, `lowercase`, `capitalize` | Text transforms             |
| `bold`, `italic`                       | Font styles                 |

#### Media Queries

| Prefix                      | Description           |
| --------------------------- | --------------------- |
| `@1279`, `@1023`, `@767`    | Max-width breakpoints |
| `@768`, `@1024`, `@1280`    | Min-width breakpoints |
| `@hover`                    | Hover media query     |
| `@light-mode`, `@dark-mode` | Color scheme queries  |

#### Utilities

| Prefix             | Description             |
| ------------------ | ----------------------- |
| `css-reset`        | CSS reset code          |
| `scrollbar-hidden` | Hide scrollbar          |
| `img-responsive`   | Responsive image styles |
| `modal-style`      | Modal styling           |
| `linear-gradient`  | CSS gradients           |

### JavaScript Snippets

#### Console Methods

| Prefix | Description     |
| ------ | --------------- |
| `ca`   | console.assert  |
| `cl`   | console.log     |
| `ce`   | console.error   |
| `cw`   | console.warn    |
| `ct`   | console.time    |
| `cte`  | console.timeEnd |
| `ctr`  | console.trace   |
| `cd`   | console.dir     |
| `ctb`  | console.table   |

#### Array Methods

| Type     | Prefix     | Description          |
| -------- | ---------- | -------------------- |
| Static   | `Af`       | Array.from           |
| Static   | `Aia`      | Array.isArray        |
| Static   | `Ao`       | Array.of             |
| Instance | `.map`     | Array map method     |
| Instance | `.filter`  | Array filter method  |
| Instance | `.reduce`  | Array reduce method  |
| Instance | `.forEach` | Array forEach method |
| Instance | `.find`    | Array find method    |
| Instance | `.some`    | Array some method    |
| Instance | `.every`   | Array every method   |

## Usage

1. Type the snippet prefix in your editor
2. Press Tab or Enter to expand the snippet
3. Use Tab to navigate between placeholders

## Examples

### HTML

```html
<!-- Type 'html-menu' to get: -->
<nav class="menu">
    <ul class="menu-list">
        <li class="menu-item"><a href="#" class="menu-link">Home</a></li>
        <li class="menu-item"><a href="#" class="menu-link">About</a></li>
        <li class="menu-item"><a href="#" class="menu-link">Services</a></li>
        <li class="menu-item"><a href="#" class="menu-link">Contact</a></li>
    </ul>
</nav>
```

### CSS

```css
/* Type 'center-flex' to get: */
display: flex;
justify-content: center;
align-items: center;

/* Type 'get-shadow1' to get: */
box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
```

### JavaScript

```javascript
// Type 'cl' to get:
console.log(${1:message});

// Type '.map' to get:
.map((${1:value}, ${2:index}, ${3:array}) => {
    ${0}
});
```

## Contributing

Feel free to contribute to this project by:

1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Pushing to the branch
5. Creating a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created by [hongducdev](https://github.com/hongducdev)
