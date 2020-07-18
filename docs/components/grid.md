# Grid

> Flexbox based mobile first 12 columns grid system.

<!-- Example: -->
<div class="row margin-top-small">
    <div class="column-12"> 
        <div class="text-center text-white background-primary">12</div>
    </div>
</div>

<!-- Example -->
<div class="row margin-top-small">
    <div class="column-6"> 
        <div class="text-center text-white background-primary">6</div>
    </div>
    <div class="column-6"> 
        <div class="text-center text-white background-primary">6</div>
    </div>
</div>

<!-- Example -->
<div class="row margin-top-small">
    <div class="column-4"> 
        <div class="text-center text-white background-primary">4</div>
    </div>
    <div class="column-4"> 
        <div class="text-center text-white background-primary">4</div>
    </div>
    <div class="column-4"> 
        <div class="text-center text-white background-primary">4</div>
    </div>
</div>

<!-- Example -->
<div class="row margin-top-small">
    <div class="column-3"> 
        <div class="text-center text-white background-primary">3</div>
    </div>
    <div class="column-3"> 
        <div class="text-center text-white background-primary">3</div>
    </div>
    <div class="column-3"> 
        <div class="text-center text-white background-primary">3</div>
    </div>
    <div class="column-3"> 
        <div class="text-center text-white background-primary">3</div>
    </div>
</div>

### Example: 12-width column

```html
<div class="row">
    <div class="column-12">
        <!-- 12-width column -->
    </div>
</div>
```

### Example: 6-width columns

```html
<div class="row">
    <div class="column-6">
        <!-- 6-width column -->
    </div>
    <div class="column-6">
        <!-- 6-width column -->
    </div>
</div>
```

### Example: Nested columns

```html
<div class="row">
    <div class="column-12">
        <!-- Nested columns -->
        <div class="row">
            <div class="column-6"></div>
            <div class="column-6"></div>
        </div>
    </div>
</div>
```