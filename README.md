# css-flex-justify-content 1.0.6

Css module of single purpose classes for flex justify content

#### Stats

343 | 24 | 68
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-justify-content
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-flex-justify-content
```

ssh:
```
git clone git@github.com:tachyons-css/css-flex-justify-content.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-justify-content";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-flex-justify-content@1.0.6/css/css-flex-justify-content.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-justify-content">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FLEX JUSTIFY CONTENT
*/
.jc-fs { -webkit-box-pack: start; -ms-flex-pack: start; justify-content: flex-start; }
.jc-f3 { -webkit-box-pack: end; -ms-flex-pack: end; justify-content: flex-end; }
.jc-c { -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; }
.jc-sb { -webkit-box-pack: justify; -ms-flex-pack: justify; justify-content: space-between; }
.jc-sa { -ms-flex-pack: distribute; justify-content: space-around; }
.jc-i { -webkit-box-pack: inherit; -ms-flex-pack: inherit; justify-content: inherit; }
@media screen and (min-width: 48em) {
 .jc-fs-ns { -webkit-box-pack: start; -ms-flex-pack: start; justify-content: flex-start; }
 .jc-f3-ns { -webkit-box-pack: end; -ms-flex-pack: end; justify-content: flex-end; }
 .jc-c-ns { -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; }
 .jc-sb-ns { -webkit-box-pack: justify; -ms-flex-pack: justify; justify-content: space-between; }
 .jc-sa-ns { -ms-flex-pack: distribute; justify-content: space-around; }
 .jc-i-ns { -webkit-box-pack: inherit; -ms-flex-pack: inherit; justify-content: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .jc-fs-m { -webkit-box-pack: start; -ms-flex-pack: start; justify-content: flex-start; }
 .jc-f3-m { -webkit-box-pack: end; -ms-flex-pack: end; justify-content: flex-end; }
 .jc-c-m { -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; }
 .jc-sb-m { -webkit-box-pack: justify; -ms-flex-pack: justify; justify-content: space-between; }
 .jc-sa-m { -ms-flex-pack: distribute; justify-content: space-around; }
 .jc-i-m { -webkit-box-pack: inherit; -ms-flex-pack: inherit; justify-content: inherit; }
}
@media screen and (min-width: 64em) {
 .jc-fs-l { -webkit-box-pack: start; -ms-flex-pack: start; justify-content: flex-start; }
 .jc-f3-l { -webkit-box-pack: end; -ms-flex-pack: end; justify-content: flex-end; }
 .jc-c-l { -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; }
 .jc-sb-l { -webkit-box-pack: justify; -ms-flex-pack: justify; justify-content: space-between; }
 .jc-sa-l { -ms-flex-pack: distribute; justify-content: space-around; }
 .jc-i-l { -webkit-box-pack: inherit; -ms-flex-pack: inherit; justify-content: inherit; }
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

