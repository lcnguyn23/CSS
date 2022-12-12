# CSS12

## Lesson 5 - Positioning content

![](https://i.postimg.cc/QMmJB2GD/Screenshot-2022-12-09-161738.png)

### Float

```html
<header>...</header>
<section>...</section>
<aside>...</aside>
<footer>...</footer>
```

```css
section {
  float: left;
  width: 63%;
}
aside {
  float: right;
  width: 30%;
}

footer {
  clear: both;
  margin-bottom: 0;
}
```

![](https://i.postimg.cc/CKRZTdrT/Screenshot-2022-12-09-162943.png)

## Inline-block

```html
<header>header</header>
<section>section</section>
<section>section</section>
<section>section</section>
<footer>footer</footer>
```

```css
header,
section,
aside,
footer {
  margin: 0 1.5% 24px 1.5%;
}
section {
  display: inline-block;
  width: 30%;
}
footer {
  margin-bottom: 0;
}
```

![](https://i.postimg.cc/cJN8Dwkx/Screenshot-2022-12-12-145941.png)

## Absolute
