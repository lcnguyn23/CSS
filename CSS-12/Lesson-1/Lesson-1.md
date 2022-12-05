# CSS12

## Lesson 1 - Building your first web page

### HTML

#### Elements

```html
<a>
  <div>
    <p>
      <span> ...</span>
    </p>
  </div></a
>
```

#### Tags

```html
<a></a>
<div></div>
<p></p>
<span></span>
...
```

`<>`: opening tag
`</>`: closing tag

**Self-closing tags**:

```html
<br />
<img />
<meta />
<link />
...
```

#### Attributes

```html
<a href="www.example.com">Example</a>
```

- Attribute: `href="www.example.com"`

#### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Hello world</title>
  </head>
  <body>
    <h1>Hello word</h1>
    <p>This is a web page.</p>
  </body>
</html>
```

### CSS

#### Common selectors

##### Element selector:

```html
<p>...</p>
<div>...</div>
<div>...</div>
```

```css
p {
  ...;
}
div {
  ...;
}
```

##### Class selector:

```html
<div class="classExample">...</div>
<p class="classExample">...</p>
```

```css
.classExample {
  ...;
}
```

##### Id selector:

```html
<div id="idExample">...</div>
```

```css
#idExample {
  ...;
}
```

#### Poperties:

```css
p {
  color: ...;
  font-size: ...;
  ...;
}
```

#### Values:

```css
p {
  color: orange;
  font-size: 16px;
  ...;
}
```

#### Insert CSS to HTML file:

##### External CSS:

```html
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

##### Internal CSS:

```html
<head>
  <style>
    body {
      background-color: linen;
    }
    h1 {
      color: maroon;
      margin-left: 40px;
    }
  </style>
</head>
```

##### Inline CSS:

```html
<body>
  <h1 style="color:blue;text-align:center;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>
</body>
```

## First web page
