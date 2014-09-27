angular-rpi
===========

AngularJS Reading Position Indicator

Based on http://css-tricks.com/reading-position-indicator

### Usage:

Simply add:

````
<!-- CSS -->
<link rel="stylesheet" href="dist/css/angular-rpi.min.css" />

<!-- JS -->
<script type="text/javascript" src="dist/js/angular-rpi.min.js"></script>
```

to your HTML, and then use it as a directive:


```
<rpi></rpi>
```

### Modify and build

You can change default styles for the progress bar by editing `angular-rpi.scss`,
or override it in your own styles.

To build just type:
`npm install` & after `gulp`

It will create CSS from SCSS file, and minify JS & CSS files.

### Contribution

Feel free to commit your code here :)

### License

The MIT License (MIT)

Copyright (c) 2014 Maciej Rzepinski

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
