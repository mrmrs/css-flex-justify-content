# css-flex-justify-content

Functional CSS for flex-justify-content

## Filesize

| File | Size |
|------|------|
| `dist/flex-justify-content.css` | 1265 bytes |
| `dist/flex-justify-content.min.css` | 927 bytes (213 Gzipped) |

## Install

```sh
npm install css-flex-justify-content
```

## Usage

### Import

```css
@import "css-flex-justify-content";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-justify-content/dist/flex-justify-content.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-justify-content/dist/flex-justify-content.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.jc-fs` | `justify-content: flex-start;` |
| `.jc-f3` | `justify-content: flex-end;` |
| `.jc-c` | `justify-content: center;` |
| `.jc-sb` | `justify-content: space-between;` |
| `.jc-sa` | `justify-content: space-around;` |
| `.jc-i` | `justify-content: inherit;` |
| `.jc-fs-s` | `justify-content: flex-start;` |
| `.jc-f3-s` | `justify-content: flex-end;` |
| `.jc-c-s` | `justify-content: center;` |
| `.jc-sb-s` | `justify-content: space-between;` |
| `.jc-sa-s` | `justify-content: space-around;` |
| `.jc-i-s` | `justify-content: inherit;` |
| `.jc-fs-m` | `justify-content: flex-start;` |
| `.jc-f3-m` | `justify-content: flex-end;` |
| `.jc-c-m` | `justify-content: center;` |
| `.jc-sb-m` | `justify-content: space-between;` |
| `.jc-sa-m` | `justify-content: space-around;` |
| `.jc-i-m` | `justify-content: inherit;` |
| `.jc-fs-l` | `justify-content: flex-start;` |
| `.jc-f3-l` | `justify-content: flex-end;` |
| `.jc-c-l` | `justify-content: center;` |
| `.jc-sb-l` | `justify-content: space-between;` |
| `.jc-sa-l` | `justify-content: space-around;` |
| `.jc-i-l` | `justify-content: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.jc-fs-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-justify-content.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-justify-content.css` — formatted
- `dist/flex-justify-content.min.css` — minified

## License

MIT
