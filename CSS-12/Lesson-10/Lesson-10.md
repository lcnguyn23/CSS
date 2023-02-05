# CSS12

## Lesson 10 - Building forms

### Forms

```html
<form action="/login" method="post">
  ...
</form>
```

### Text Fields & Textareas 

#### Text fields

```html
<input type="text" name="username" placeholder="username">
```
**Demo**
<input type="text" name="username" placeholder="username">

```html
<input type="date" name="birthday">
<input type="time" name="game-time">
<input type="email" name="email-address" >
<input type="url" name="website">
<input type="number" name="cost">
<input type="tel" name="phone-number">
```

#### Textareas
```html
<textarea name="comment">Add your comment here</textarea>
```
**Demo**
<textarea name="comment">Add your comment here</textarea>

#### Multiple choice input & Menus

##### Radio buttons
```html
<input type="radio" name="day" value="Friday" checked> Friday
<input type="radio" name="day" value="Saturday"> Saturday
<input type="radio" name="day" value="Sunday"> Sunday
```
**Demo**
<input type="radio" name="day" value="Friday" checked> Friday
<input type="radio" name="day" value="Saturday"> Saturday
<input type="radio" name="day" value="Sunday"> Sunday

##### Check box
```html
<input type="checkbox" name="day" value="Friday" checked> Friday
<input type="checkbox" name="day" value="Saturday"> Saturday
<input type="checkbox" name="day" value="Sunday"> Sunday
```
**Demo**
<input type="checkbox" name="day" value="Friday" checked> Friday
<input type="checkbox" name="day" value="Saturday"> Saturday
<input type="checkbox" name="day" value="Sunday"> Sunday

##### Dropdown list
```html
<select name="day">
  <option value="Friday" selected>Friday</option>
  <option value="Saturday">Saturday</option>
  <option value="Sunday">Sunday</option>
</select>
```
**Demo**
<select name="day">
  <option value="Friday" selected>Friday</option>
  <option value="Saturday">Saturday</option>
  <option value="Sunday">Sunday</option>
</select>

##### Multiple selections
```html
<select name="day" multiple>
  <option value="Friday" selected>Friday</option>
  <option value="Saturday">Saturday</option>
  <option value="Sunday">Sunday</option>
</select>
```
**Demo**
<select name="day" multiple>
  <option value="Friday" selected>Friday</option>
  <option value="Saturday">Saturday</option>
  <option value="Sunday">Sunday</option>
</select>

#### Form button

##### Submit input
```html
<input type="submit" name="submit" value="Submit">
```
**Demo**
<input type="submit" name="submit" value="Submit">

##### Submit button
```html
<button name="submit">
  <strong>Send Us</strong> a Message
</button>
```
**Demo**
<button name="submit">
  <strong>Send Us</strong> a Message
</button>

#### File input

```html
<input type="file" name="file">
```
**Demo**
<input type="file" name="file">

### Organizing Form Elements

#### Label

```html
<label for="username">Username</label>
<input type="text" name="username" id="username">
```
**Demo**
<label for="username">Username</label>
<input type="text" name="username" id="username">

#### Fieldset & Legend
```html
<fieldset>
  <legend>Login</legend>
  <label>
    Username
    <input type="text" name="username">
  </label>
  <label>
    Password
    <input type="text" name="password">
  </label>
</fieldset>
```
**Demo**
<fieldset>
  <legend>Login</legend>
  <label>
    Username
    <input type="text" name="username">
  </label>
  <label>
    Password
    <input type="text" name="password">
  </label>
</fieldset>

### Form & input attribute

#### Disable
```html
<label>
  Username
  <input type="text" name="username" disabled>
</label>
```
**Demo**
<label>
  Username
  <input type="text" name="username" disabled>
</label>

#### Required
```html
<label>
  Email Address
  <input type="email" name="email-address" required>
</label>
```
**Demo**
<form>
  <label>
    Email Address
    <input type="email" name="email-address" required>
  </label>
   <input type="submit" name="submit">
</form>
