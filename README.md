CSS-Absolute Center
===================

A Simple CSS Framework for centering HTML elements.

##How to Use

Create a parent block and a child block. For example
```html
<div>    <!-- Parent -->
    <div>    <!-- Child -->
    . . . . . . . .
    </div>
</div>
```

Add classes `.absolute-center-wrapper` to the _parent_ block and `.absolute-center` to the _child_ block.
```html
<div class="absolute-center-wrapper">    <!-- Parent -->
    <div class="absolute-center">    <!-- Child -->
    . . . . . . . .
    </div>
</div>
```
Now add this `css` segment to your stylesheet.
```css
.absolute-center-wrapper {
width: 100%;
height: 100%;
display: table;
}
.absolute-center {
display: table-cell;
vertical-align: middle;
text-align: center;
}
```
And you are done.

###License
This project and source code is licensed under MIT [(http://opensource.org/licenses/MIT)](http://opensource.org/licenses/MIT).

###Version
1.0 (Stable)

###Author
Debashis Barman [(www.debashisbarman.in)](http://www.debashisbarman.in).
