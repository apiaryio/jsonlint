JSON Lint
=========

A pure [JavaScript version](http://zaach.github.com/jsonlint/) of the service provided at [jsonlint.com](http://jsonlint.com).

## Module interface

I'm not sure why you wouldn't use the built in `JSON.parse` but you can use jsonlint from a CommonJS module:

    var jsonlint = require("jsonlint");

    jsonlint.parse('{"creative?": false}');

It returns the parsed object or throws an `Error`.

## Vim Plugins

* [Syntastic](http://www.vim.org/scripts/script.php?script_id=2736)
* [sourcebeautify](http://www.vim.org/scripts/script.php?script_id=4079)

## MIT License

Copyright (C) 2012 Zachary Carter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
