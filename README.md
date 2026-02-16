# css-flex-justify-content

Functional CSS for flex-justify-content

## Filesize

| File | Size |
|------|------|
| `dist/flex-justify-content.css` | 1673 bytes |
| `dist/flex-justify-content.min.css` | 1335 bytes (226 Gzipped) |

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
| `.justify-content-start` | `justify-content: flex-start;` |
| `.justify-content-end` | `justify-content: flex-end;` |
| `.justify-content-center` | `justify-content: center;` |
| `.justify-content-between` | `justify-content: space-between;` |
| `.justify-content-around` | `justify-content: space-around;` |
| `.justify-content-inherit` | `justify-content: inherit;` |
| `.justify-content-start-s` | `justify-content: flex-start;` |
| `.justify-content-end-s` | `justify-content: flex-end;` |
| `.justify-content-center-s` | `justify-content: center;` |
| `.justify-content-between-s` | `justify-content: space-between;` |
| `.justify-content-around-s` | `justify-content: space-around;` |
| `.justify-content-inherit-s` | `justify-content: inherit;` |
| `.justify-content-start-m` | `justify-content: flex-start;` |
| `.justify-content-end-m` | `justify-content: flex-end;` |
| `.justify-content-center-m` | `justify-content: center;` |
| `.justify-content-between-m` | `justify-content: space-between;` |
| `.justify-content-around-m` | `justify-content: space-around;` |
| `.justify-content-inherit-m` | `justify-content: inherit;` |
| `.justify-content-start-l` | `justify-content: flex-start;` |
| `.justify-content-end-l` | `justify-content: flex-end;` |
| `.justify-content-center-l` | `justify-content: center;` |
| `.justify-content-between-l` | `justify-content: space-between;` |
| `.justify-content-around-l` | `justify-content: space-around;` |
| `.justify-content-inherit-l` | `justify-content: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.justify-content-start-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-justify-content.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-justify-content.css` — formatted
- `dist/flex-justify-content.min.css` — minified

## License

MIT
