# Columns
### Basic usage
Create a row using the `row` class.
```html
<div class="row"></div>
```
A row has columns.
```html
<div class="row">
    <div class="column-33 bg-hotpink">
        <h1>Hello World!</h1>
    </div>
    <div class="column-66">
        <p>This column takes up 66.66666667% of the page</p>
    </div>
</div>
```
The following column sizes are available.
```html
<div class="column-20"></div> <!-- Takes up 20% of the page -->
<div class="column-25"></div> <!-- Takes up 25% of the page -->
<div class="column-33"></div> <!-- Takes up 33.33% of the page -->
<div class="column-40"></div> <!-- Takes up 40% of the page -->
<div class="column-50"></div> <!-- Takes up 50% of the page -->
<div class="column-60"></div> <!-- Takes up 60% of the page -->
<div class="column-66"></div> <!-- Takes up 66.66% of the page -->
<div class="column-80"></div> <!-- Takes up 80% of the page -->
<div class="column-100"></div> <!-- Takes up 100% of the page -->
```
If all the columns do not fit onto one row then the row will continue onto the next line.
### Variables
`$column-sizes` – a list of numbers. By default set to `$column-sizes: 20 25 100/3 40 50 60 2*100/3 80 100;
`.