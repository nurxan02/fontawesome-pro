## FontAwesome Pro Webfonts

This project contains FontAwesome Pro webfonts and related CSS for easy integration into your web projects.

### Structure

- `index.html` — Example HTML file for usage.
- `css/fa.css` — Main CSS file referencing FontAwesome webfonts.
- `webfonts/` — Directory for downloaded font files.
- `webfont-links.txt` — List of direct download links for all required webfont files.

### How to Download All Webfonts

To download all webfont files listed in `webfont-links.txt`, open your terminal in this folder and run:

```sh
xargs -n 1 curl -O < webfont-links.txt
```

This will automatically download each font file into the current directory. Move the downloaded files into the `webfonts/` folder if needed.

### Usage

Include the CSS file in your HTML and ensure the `webfonts/` directory contains all the required font files.

---

For any issues or questions, please contact the maintainer.


