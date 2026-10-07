# CSS Theming Wiki
Use this page to make notes about how the CSS works with the "Zen Garden Theme" you chose.  _Example_:

### Scrolling page over fixed background ###

On the default theme of CSS Zen Garden [https://csszengarden.com] the page scrolls over a fixed background, creating a layered effect.  How does that work? Use background-attachment: fixed on the HTML container or the body element, like this: 

    body {
       margin: 0;
       padding: 0;
       background-image: url('path/to/your-image.jpg');
       background-repeat: no-repeat;
       background-position: center center;
       background-attachment: fixed;
       background-size: cover;
    }
