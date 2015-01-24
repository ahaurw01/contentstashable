# contentstashable.js

Make local edits to `contenteditable` HTML elements and refresh the page without
losing your changes.

## How to use it

1. Author some HTML elements with the `contenteditable` attribute. Make sure
   they have `id`s.

    ```html
    <ul id="shopping-list" contenteditable>
      <li>red wine</li>
      <li>dark chocolate</li>
      <li>ice cream</li>
      <li>tissues</li>
    </ul>
    ```
2. Include `contentstashable.js` somewhere in the document.

    ```html
    <head>
      ...
      <script src="contentstashable.js"></script>
    </head>
    ```
3. Load the page and make some edits in the browser.
4. Refresh the page and see all your latest changes.

## Common sense reminders

* Local browser storage is used to save your edits.
* Don't give your buddy a link to your page and expect him to see your edits.
* Pay attention when you let third party libraries automatically append things
  to the DOM.

## License

(MIT License)

Copyright (c) 2015 Aaron Haurwitz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.