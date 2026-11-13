## How to Run

1. Download or copy `index.html` and `style.css` into the same folder.
2. Open `index.html` in a web browser such as Chrome, Edge, Firefox, or Safari.

No installation or internet connection is needed for the layout, but the food images are loaded from external websites, so they need an internet connection to display.

## How the Menu Filter Works

Each category button links to a section on the same page, such as `#starters`. CSS uses the `:target` selector to show only the section matching the current address, and the `:has()` selector highlights the matching button. "All Items" shows every category.

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, media queries, `:target`, `:has()`)

## Known Limitations

- No search feature, since it requires JavaScript.
- No food detail popups, since they require JavaScript.
- Button highlighting requires a modern browser that supports `:has()`. In older browsers, all items still display.
- Food images are hotlinked from other websites and may stop loading if those sites block them.
- Sample prices, offers, and contact details are placeholders.

## Credits

Food images are from third-party websites. Replace them with your own images, or with images you have permission to use, before publishing.