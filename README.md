# css-flex-justify-content 0.0.7

Css module of single purpose classes for flex justify content

#### Stats

273 | 24 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-justify-content
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-justify-content
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-justify-content";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-justify-content">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX JUSTIFY CONTENT
*/
.jc-fs { justify-content: flex-start; }
.jc-f3 { justify-content: flex-end; }
.jc-c { justify-content: center; }
.jc-sb { justify-content: space-between; }
.jc-sa { justify-content: space-around; }
.jc-i { justify-content: inherit; }
@media screen and (min-width: 48em) {
 .jc-fs-ns { justify-content: flex-start; }
 .jc-f3-ns { justify-content: flex-end; }
 .jc-c-ns { justify-content: center; }
 .jc-sb-ns { justify-content: space-between; }
 .jc-sa-ns { justify-content: space-around; }
 .jc-i-ns { justify-content: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .jc-fs-m { justify-content: flex-start; }
 .jc-f3-m { justify-content: flex-end; }
 .jc-c-m { justify-content: center; }
 .jc-sb-m { justify-content: space-between; }
 .jc-sa-m { justify-content: space-around; }
 .jc-i-m { justify-content: inherit; }
}
@media screen and (min-width: 64em) {
 .jc-fs-l { justify-content: flex-start; }
 .jc-f3-l { justify-content: flex-end; }
 .jc-c-l { justify-content: center; }
 .jc-sb-l { justify-content: space-between; }
 .jc-sa-l { justify-content: space-around; }
 .jc-i-l { justify-content: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
