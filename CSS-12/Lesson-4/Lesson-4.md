# CSS12

## Lesson 4 - Opening the Box Model

### Working with the Box Model

```css
div {
  border: 6px solid #949599;
  height: 100px;
  margin: 20px;
  padding: 20px;
  width: 400px;
}
```

- **Total width** = margin-right + border-right + padding-right + width + padding-left + border-left + margin-left
- **Total height** = margin-top + border-top + padding-top + height + padding-bottom + border-bottom + margin-bottom

![](https://learn.shayhowe.com/assets/images/courses/html-css/opening-the-box-model/box-model.png)

- **Width**: 492px = 20px + 6px + 20px + 400px + 20px + 6px + 20px
- **Height**: 192px = 20px + 6px + 20px + 100px + 20px + 6px + 20px

![](https://thachpham.com/wp-content/uploads/2015/04/box-model.gif)

#### Margin

Độ rộng vùng bao quanh element bên ngoài border

```css
div {
  margin: 20px;
  /* 
    top = 20px; 
    right = 20px;
    bottom = 20px;
    left = 20px;
    */
}
div {
  margin-top: 20px;
  margin-right: 15px;
  margin-bottom: 10px;
  margin-right: 25px;
}
div {
  margin: 20px 25px;
  /* 
    top & bottom = 20px;
    right & left = 25px;
    */
}
div {
  margin: 20px 15px 25px;
  /*
    top = 20px;
    right & left = 15px;
    bottom = 25px;
    */
}
div {
  margin: 20px 15px 25px 10px;
  /*
    top = 20px;
    right = 15px;
    bottom = 25px;
    left = 10px;
    */
}
```

#### Padding

Độ rộng bao quanh element bên trong border

```css
div {
  padding: 20px;
  padding-top: 20px;
  padding-right: 15px;
  padding-bottom: 25px;
  padding-left: 10px;
}
div {
  padding: 20px 25px; /* top & bottom -- right & left */
  padding: 20px 15px 25px; /* top -- right & left -- bottom */
  padding: 20px 15px 25px 10px; /* top -- right -- bottom -- right */
}
```

#### Border

```css
div {
  border: 2px solid black; /* width -- style -- color */
}
div {
  border: 2px dotted black; /* width -- style -- color */
}
div {
  border-top: 2px solid black;
  border-bottom: 2px dotted red;
  border-left: ...;
  border-right: ...;
}
div {
  border-top-width: 6px;
}
div {
  border-radius: 50px;
  border-top-right-radius: 5px;
  border-radius: 15px 50px;
  ...;
}
```

**Demo**

```html
<div class="solid">solid</div>
<div class="dotted">dotted</div>
```

```css
.solid {
  border: 2px solid black;
  border-radius: 50px;
}
.dotted {
  border-top: 2px solid black;
  border-bottom: 5px dotted red;
}
```

<div class="solid" style="border: 2px solid black; margin: 10px; border-radius: 50px;">solid</div>
<div class="dotted" style="border-top: 2px solid black;
  border-bottom: 5px dotted red; margin: 10px;">dotted</div>

### Box sizing

![](https://learn.shayhowe.com/assets/images/courses/html-css/opening-the-box-model/box-sizing.png)

#### Content box

`content-box`: giá trị mặc định, giá trị width và height chỉ áp dụng cho khu vực nội dung bên trong, không bao gôm padding, margin, border.

```css
div {
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}
```

`-webkit-`: Webkit (Google Chrome & Apple Safari)
`-moz-`: Mozilla Firefox
`-ms-`: Microsoft Internet Explorer

#### Padding box

`padding-box`: width và height chỉ bao gồm cho phần nội dung và padding, không bao gồm border và margin.

```css
div {
  box-sizing: padding-box;
}
```

#### Border box

`border-box`: width và heigh sẽ bao gồm cho cả phần nội dung, padding và border nhưng không bao gồm margin.

```css
div {
  box-sizing: border-box;
}
```
