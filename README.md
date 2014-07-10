# CSS FLEX JUSTIFY CONTENT

  Mobile-first classes for css-flex-justify-content.
  Set the desired css-flex-justify-content on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-flex-justify-content
```
or download the css on github and include in your project.

## File Size


## The Code
```
.jc-fs {  justify-content: flex-start; }
.jc-f3 {  justify-content: flex-end; }
.jc-c {   justify-content: center; }
.jc-sb {  justify-content: space-between; }
.jc-sa {  justify-content: space-around; }
.jc-i {   justify-content: inherit; }

@include break(not-small) {
  .jc-fs-ns {  justify-content: flex-start; }
  .jc-f3-ns {  justify-content: flex-end; }
  .jc-c-ns {   justify-content: center; }
  .jc-sb-ns {  justify-content: space-between; }
  .jc-sa-ns {  justify-content: space-around; }
  .jc-i-ns {   justify-content: inherit; }
}

@include break(medium) {
  .jc-fs-m {  justify-content: flex-start; }
  .jc-f3-m {  justify-content: flex-end; }
  .jc-c-m {   justify-content: center; }
  .jc-sb-m {  justify-content: space-between; }
  .jc-sa-m {  justify-content: space-around; }
  .jc-i-m {   justify-content: inherit; }
}

@include break(large) {
  .jc-fs-l {  justify-content: flex-start; }
  .jc-f3-l {  justify-content: flex-end; }
  .jc-c-l {   justify-content: center; }
  .jc-sb-l {  justify-content: space-between; }
  .jc-sa-l {  justify-content: space-around; }
  .jc-i-l {   justify-content: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

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

