# TechZip Blog Asset

Static assets for TechZip Blogspot articles.

## CSS

File:

- `techzip-article.css`

The CSS is scoped to `.tz-article`, so it should not override Blogger theme selectors such as `body`, `a`, `.post-title`, `.post-body`, or `.widget`.

## Blogger Usage

Add the stylesheet link inside the Blogger theme `<head>` section.

If GitHub Pages is enabled for this repository:

```html
<link href='https://binvincent29-netizen.github.io/techzip-blog-asset/techzip-article.css' rel='stylesheet'/>
```

Alternative CDN URL:

```html
<link href='https://cdn.jsdelivr.net/gh/binvincent29-netizen/techzip-blog-asset@main/techzip-article.css' rel='stylesheet'/>
```

Post body HTML should be wrapped with:

```html
<div class="tz-article">
  ...
</div>
```
