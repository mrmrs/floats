# FLOATS

  Mobile-first float classes.
  Set the desired float on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install floats.css --save-dev
```
or download the css on github and include in your project.

```
.fl { float: left;  display: inline; }
.fr { float: right; display: inline; }
.fn { float: none; }

@media screen and (min-width: 48em) {
  .fl-ns { float: left;  display: inline; }
  .fr-ns { float: right; display: inline; }
  .fn-ns { float: none; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fl-m { float: left;  display: inline; }
  .fr-m { float: right; display: inline; }
  .fn-m { float: none; }
}

@media screen and (min-width: 64em)  {
  .fl-l { float: left;  display: inline; }
  .fr-l { float: right; display: inline; }
  .fn-l { float: none; }
}
```
# License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

