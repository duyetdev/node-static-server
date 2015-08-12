# Static HTML Server

Simple static web server.

### Install
```
npm install static-html-server -g
```

### Usage

```
static-html-server -p [port] -r [root folder] -f [fallback path if not found]
```

Arguments (all are optional):

* `p`: [`Number`] port number, default to 8000
* `r`: [`String`] root folder, default to working directory
* `f`: [`String`] fallback path when page not found, default to not falling back and send 404

For example
```
static-html-server -p 8899 -r ./ -f index.html
Server running at http://localhost:8899/ [root: ./, fallback: index.html]
```
# License

MIT License

Copyright (c) 2015 Van-Duyet Le

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
