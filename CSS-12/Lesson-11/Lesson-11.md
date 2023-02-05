# CSS12

## Lesson 11 - Organizing Data with Tables

### Creating a Table

#### Table
```html
<table>
  ...
</table>
```

#### Table row
```html
<table>
  <tr>
    ...
  </tr>
  <tr>
    ...
  </tr>
</table>
```

#### Table data
```html
<table>
  <tr>
    <td>Orange</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Tea</td>
    <td>3</td>
  </tr>
</table>
```
**Demo**
<table>
  <tr>
    <td>Orange</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Tea</td>
    <td>3</td>
  </tr>
</table>

#### Table header
```html
<table>
  <tr>
    <th>Name</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>Orange</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Tea</td>
    <td>3</td>
  </tr>
</table>
```
**Demo**
<table>
  <tr>
    <th>Name</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>Orange</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Tea</td>
    <td>3</td>
  </tr>
</table>

### Table structure

#### Table caption

```html
<table>
  <caption>Food shop</caption>
  ...
</table>
```
**Demo**
<table>
  <caption>Food shop</caption>
  <tr>
    <th>Name</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>Orange</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Milk</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Tea</td>
    <td>3</td>
  </tr>
</table>

#### Table head, body & foot
```html
<table>
  <caption>Food shop</caption>

  <!-- Head -->
  <thead>
    <tr>
      <th>Name</th>
      <th>Quantity</th>
    </tr>
  </thead>

  <!-- Body -->
  <tbody>
    <tr>
      <td>Orange</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Milk</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Tea</td>
      <td>3</td>
    </tr>
  <tbody>

  <!-- Foot -->
  <tfoot>
    <tr>
      <td>Total</td>
      <td>6</td>
    </tr>
  </tfoot>
</table>
```
**Demo**
<table>
  <caption>Food shop</caption>

  <!-- Head -->
  <thead>
    <tr>
      <th>Name</th>
      <th>Quantity</th>
    </tr>
  </thead>

  <!-- Body -->
  <tbody>
    <tr>
      <td>Orange</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Milk</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Tea</td>
      <td>3</td>
    </tr>
  <tbody>

  <!-- Foot -->
  <tfoot>
    <tr>
      <td>Total</td>
      <td>6</td>
    </tr>
  </tfoot>
</table>