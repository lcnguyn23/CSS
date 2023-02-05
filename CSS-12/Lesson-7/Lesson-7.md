# CSS12

## Lesson 7 - Setting backgrounds & gradients

### Background color

```css
div {
  background-color: #555;
}
```

### Background image
```css
div {
  background-image: url("example.png");
}
```

#### Background repeat

```css
div {
  background-image: url("example.png");
  background-repeat: no-repeat; /*repeat, repeat-x, repeat-y*/
}
```

#### Background position
```css
div {
  background-image: url("example.png");
  background-position: 20px 10px;
  background-repeat: no-repeat;
}
```

#### Linear gradient background
```css
div {
  background: #466368;
  background: -webkit-linear-gradient(#648880, #293f50);
  background:    -moz-linear-gradient(#648880, #293f50);
  background:         linear-gradient(#648880, #293f50);
}
```
#### Changing the direction of the gradient
```css
div {
  background: #466368;
  background: linear-gradient(to right bottom, #648880, #293f50);
}
```

