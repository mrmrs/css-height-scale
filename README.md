# css-height-scale

Functional CSS for height-scale

## Filesize

| File | Size |
|------|------|
| `dist/height-scale.css` | 1425 bytes |
| `dist/height-scale.min.css` | 871 bytes (216 Gzipped) |

## Install

```sh
npm install css-height-scale
```

## Usage

### Import

```css
@import "css-height-scale";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-height-scale/dist/height-scale.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-height-scale/dist/height-scale.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ht1` | `height: 1rem;` |
| `.ht2` | `height: 2rem;` |
| `.ht3` | `height: 4rem;` |
| `.ht4` | `height: 8rem;` |
| `.ht5` | `height: 16rem;` |
| `.ht6` | `height: 32rem;` |
| `.ht7` | `height: 48rem;` |
| `.ht8` | `height: 64rem;` |
| `.ht9` | `height: 96rem;` |
| `.ht10` | `height: 128rem;` |
| `.ht1-s` | `height: 1rem;` |
| `.ht2-s` | `height: 2rem;` |
| `.ht3-s` | `height: 4rem;` |
| `.ht4-s` | `height: 8rem;` |
| `.ht5-s` | `height: 16rem;` |
| `.ht6-s` | `height: 32rem;` |
| `.ht7-s` | `height: 48rem;` |
| `.ht8-s` | `height: 64rem;` |
| `.ht9-s` | `height: 96rem;` |
| `.ht10-s` | `height: 128rem;` |
| `.ht1-m` | `height: 1rem;` |
| `.ht2-m` | `height: 2rem;` |
| `.ht3-m` | `height: 4rem;` |
| `.ht4-m` | `height: 8rem;` |
| `.ht5-m` | `height: 16rem;` |
| `.ht6-m` | `height: 32rem;` |
| `.ht7-m` | `height: 48rem;` |
| `.ht8-m` | `height: 64rem;` |
| `.ht9-m` | `height: 96rem;` |
| `.ht10-m` | `height: 128rem;` |
| `.ht1-l` | `height: 1rem;` |
| `.ht2-l` | `height: 2rem;` |
| `.ht3-l` | `height: 4rem;` |
| `.ht4-l` | `height: 8rem;` |
| `.ht5-l` | `height: 16rem;` |
| `.ht6-l` | `height: 32rem;` |
| `.ht7-l` | `height: 48rem;` |
| `.ht8-l` | `height: 64rem;` |
| `.ht9-l` | `height: 96rem;` |
| `.ht10-l` | `height: 128rem;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ht1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/height-scale.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/height-scale.css` — formatted
- `dist/height-scale.min.css` — minified

## License

MIT
