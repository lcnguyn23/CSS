# CSS12

## Lesson 2 - Getting to know HTML

### div and span

#### div
```html
  <div>
```
- Thẻ div là block-level-element
- Thẻ div sử dụng để xác định một nhóm thẻ HTML gồm nhiều thẻ HTML khác nhau
```html
  <div class="social">
    <p>I may be found on...</p>
    <p>Additionally, I have a profile on...</p>
  </div>
```
### span
```html
  <span>
```
- Thẻ span là inline-level-element
- Thẻ soan dùng để xác định các đoạn văn bản nhỏ trong một block-level-element
```html
  <p>Soon we'll be <span class="tooltip">writing HTML</span> with the best of them.</p>
```

## Text-based element

- Phần tử dựa trên văn bản dùng để xử lý về văn bản

### Headings
```html
  <h1>Heading Level 1</h1>
  <h2>Heading Level 2</h2>
  <h3>Heading Level 3</h3>
  <h4>Heading Level 4</h4>
  <h5>Heading Level 5</h5>
  <h6>Heading Level 6</h6>
```
<h1>Heading Level 1</h1> 
<h2>Heading Level 2</h2> 
<h3>Heading Level 3</h3> 
<h4>Heading Level 4</h4> 
<h5>Heading Level 5</h5> 
<h6>Heading Level 6</h6> 

### Paragraphs
```html
  <p>Steve Jobs was a co-founder and longtime chief executive officer at Apple. On June 12, 2005, Steve gave the commencement address at Stanford University.</p>

  <p>In his address Steve urged graduates to follow their dreams and, despite any setbacks, to never give up&ndash;advice which he sincerely took to heart.</p>
```

### Bold text
```html
<!-- Strong importance -->
<p><strong>Caution:</strong> Falling rocks.</p>

<!-- Stylistically offset -->
<p>This recipe calls for <b>bacon</b> and <b>baconnaise</b>.</p>
```

### Italicize text
```html
<!-- Stressed emphasis -->
<p>I <em>love</em> Chicago!</p>

<!-- Alternative voice or tone -->
<p>The name <i>Shay</i> means a gift.</p>
```

## Building structure
![building structure](https://learn.shayhowe.com/assets/images/courses/html-css/getting-to-know-html/building-structure.png)

## Hyperlink
```html
  <a href="https://www.google.com">Google</a>
```

### Relative && Absolute paths
```html
  <!-- Relative Path -->
  <a href="about.html">About</a>

  <!-- Absolute Path -->
  <a href="https://www.google.com/">Google</a>
```

### Linking to email address
```html
  <a href="mailto:example@gmail.com?subject=Reaching%20Out&body=How%20are%20you">Email me</a>
```

### Opening link in a new window
```html
  <a href="https://www.google.com" target="_blank">Open in a new window</a>
```

### Linking to parts of the same page
```html
  <body id="top">
    ...
    <a href="#top">Back to top</a>
    ...
  </body>
```

