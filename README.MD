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

## License

This project is licensed under the MIT License.

---

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
