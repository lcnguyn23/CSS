# CSS12

## Lesson 3 - Getting to know CSS

### CSS Specificity

- Inline styles:

```html
<h1 style="color: red"></h1>
```

- Id:

```css
  #example
```

- Class, pseudo-class, attribute selector:

```css
.example: hover [href];
```

- Element, pseudo-element:

```css
h1: before;
```

### Calculate specificity

![](https://i.postimg.cc/SN0D3TSQ/Screenshot-2022-12-07-161928.png)

> ```css
>   !important
>   Khi sử dụng sẽ không bị các quy tắc trên ảnh hưởng
> ```

### Combine selector

**HTML**

```html
<div class="hotdog">
  <p>...</p>
  <p>...</p>
  <p class="mustard">...</p>
</div>
```

**CSS**

```css
.hotdog p {
  background: brown;
}
.hotdog p.mustard {
  background: yellow;
}
```

### Layering style with multiple class

**HTML**

```html
<a class="btn btn-success">...</a> <a class="btn btn-danger">...</a>
```

**CSS**

```css
.btn {
  font-size: 16px;
}
.btn-success {
  background: green;
}
.btn-danger {
  background: red;
}
```

### CSS units

#### Absolute units

- **px** (pixel)

```html
<p id="px-unit">pixel unit</p>
```

```css
#px-unit {
  font-size: 25px;
}
```

> <p id="px-unit" style="font-size: 25px">pixel unit</a>

#### Relative units

- **%** (percentages)

```html
<div id="px">
  <div id="percent"></div>
</div>
```

```css
#px {
  width: 500px;
  height: 200px;
}
```

- **em**

```html
<div class="banner">Banner</div>
```

```css
.banner {
  font-size: 14px;
  width: 5em; /* 5em = 14px * 5 */
}
```

- **rem** (root em)
```html
  <div class="parent">
    <div class="child">Child</div>
  </div>
```

```css
  html { /* root element */
    font-size: 12px;
  }
  .parent {
    font-size: 16px;
  }
  .child {
    font-size: 2rem; /* 2rem = 24px = 12px * 2 */
  }
```

