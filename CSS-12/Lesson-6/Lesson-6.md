# CSS12

## Lesson 6 - Working with Typography

### Adding color to text

```css
div {
  color: #fff;
}
```

### Font properties

#### Font family

```css
body {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
```

Nếu font `Segoe UI` không khả dụng hoặc chưa cài đặt trên thiết bị thì sẽ dùng font tiếp theo trong danh sách.

#### Font size

```css
body {
  font-size: 16px;
}
```

#### Font style

```css
span {
  font-style: italic;
}
```

#### Font variant

```css
span {
  font-variant: small-caps;
}
```

#### Font weight

```css
span {
  font-weight: bold;
}
```

#### Line weight

```css
body {
  line-height: 24px;
}
```

#### Shorthand font properties

```css
body {
  font: italic small-caps bold 14px/22px "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
```

### Text properties

#### Text align

```css
p {
  text-align: center;
}
```

#### Text decoration

```css
p {
  text-decoration: underline;
}
```

#### Text indent

```css
p {
  text-indent: 24px;
}
```

#### Text shadow

```css
p {
  text-shadow: 3px 6px 2px rgba(0, 0, 0, 0.3);
  /*text-shadow: horizontal shadow - vertical shadow - blur radius - color */
}
```

#### Text transform

```css
p {
  text-transform: uppercase;
}
```

#### Letter spacing

```css
p {
  letter-spacing: -0.5em;
}
```

#### Word spacing

```css
p {
  word-spacing: 0.2em;
}
```

### Using web-safe font

Font chữ đã được cài đặt trên các máy tính, tablet, điện thoại, ...

`Arial` `Garamond` `Lucida Sans, Lucida Grande, Lucida` `Tahoma` `Trebuchet` `Courier New, Courier` `Georgia` `Palatino Linotype` `Times New Roman, Times` `Verdana`

### Embedding web fonts

```css
@font-face {
  font-family: "Lobster";
  src: local("Lobster"), url("lobster.woff") format("woff");
}
body {
  font-family: "Lobster", "Comic Sans", cursive;
}
```
