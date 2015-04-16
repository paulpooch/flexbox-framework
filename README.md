# flexbox-framework
A lightweight cross-browser flexbox css framework.

## Example usage

```html
<!-- Create a row of 3 columns. -->

<!-- flexstart = Align the columns left. -->
<!-- flexitemscenter = Vertical align the columns center. -->
<div class="flextainer flexstart flexitemscenter">

  <!-- Take 1/5 of the available width, but not less than 100px. -->
  <div class"flex1" style="min-width: 100px;">
    Column one.
  </div>
  
  <!-- Take 3/5 of the available width. -->
  <div class="flex3">
    Column two.
  </div>
  
  <!-- Take 1/5 of the available width. Vertical align top (override the flexitemscenter rule). -->
  <div class="flex1 flexselfstart">
    Column three.
  </div>

</div>
```
