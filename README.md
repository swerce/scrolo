
# Scrolo - SmoothScroll Library

Scrolo is a lightweight JavaScript library for creating smooth scrolling effects on web pages. It allows users to navigate through sections of a page smoothly, with configurable speed, smoothness, and other options.

## Features

- Smooth scrolling effect with customizable speed and smoothness.
- Scroll to top button that appears when scrolling down.
- Highlights active section in the navigation menu.
- Easy to use and integrate into your web projects.

## Demo

Check out the [demo page](https://your-domain.com/demo) to see Scrolo in action.

## Usage

1. Include the Scrolo library in your HTML file:

   ```html
   <script src="[https://cdn.jsdelivr.net/gh/your-username/scrolo@main/scrolo.js](https://cdn.jsdelivr.net/gh/swerce/scrolo@main/scrolo.js)"></script>
   ```

2. Initialize Scrolo by creating a new instance with your desired options:

   ```javascript
   var smoothScroll = new SmoothScroll(document, {
     speed: 120,
     smoothness: 10,
     offset: 0,
     duration: 800,
     scrollToTopButtonId: "scrollToTopButton",
     sectionSelector: "section",
     navLinkSelector: ".nav-link",
   });
   ```

3. Customize the options according to your needs:

   - `speed`: The scroll speed in pixels per wheel tick (default: 120).
   - `smoothness`: The smoothness factor for the scrolling animation (default: 10).
   - `offset`: The offset value to adjust the scroll position (default: 0).
   - `duration`: The duration of the scroll animation in milliseconds (default: 800).
   - `scrollToTopButtonId`: The ID of the scroll to top button element (default: "scrollToTopButton").
   - `sectionSelector`: The CSS selector for the sections of your page (default: "section").
   - `navLinkSelector`: The CSS selector for the navigation links (default: ".nav-link").

4. Customize the HTML structure of your page to match the required elements:

   - Add the ID `scrollToTopButton` to your scroll to top button element.
   - Use the `sectionSelector` CSS selector for the sections on your page.
   - Use the `navLinkSelector` CSS selector for the navigation links.


## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

© [swerce]
