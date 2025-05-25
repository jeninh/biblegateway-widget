# biblegateway-widget

A simple, embeddable "Verse of the Day" (VOTD) widget using data from BibleGateway, with the ability to set your own background image.

## Features

- Fetches and displays the daily verse from BibleGateway's VOTD RSS feed.
- Lets you display the widget with a custom background image by passing a `bg` URL parameter.
- Responsive and mobile-friendly design.
- No backend required—static HTML + JS.

## Usage

You can use this widget as a standalone page or embed it in an iframe.

### Example

To show the widget with your own background image:

```
https://yourdomain.com/biblegateway-widget/index.html?bg=https://example.com/image.jpg
```

### Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/jeninh/biblegateway-widget.git
   cd biblegateway-widget
   ```

2. Open `index.html` in your browser, or deploy it as a static site.

## How it works

- The widget fetches the Verse of the Day from BibleGateway's RSS feed via a CORS proxy.
- The verse and reference are displayed over your chosen background image.
- Credits and copyright are displayed as required.

## Credits

- Verse of the Day content: [BibleGateway.com](https://www.biblegateway.com/usage/votd/)  
  The VOTD content is provided by BibleGateway.com and is subject to their [terms of use](https://www.biblegateway.com/legal/terms-of-use/). This widget is not affiliated with or endorsed by BibleGateway.
- RSS parsing: [rss2json.com](https://rss2json.com/) and [AllOrigins](https://allorigins.win/)

## License

The code in this repository is licensed under the MIT License. The Verse of the Day content is provided by BibleGateway.com and is subject to their terms of use.
