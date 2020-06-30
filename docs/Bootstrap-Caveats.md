% Boostrap Caveats


#### Use of `.fa-fw` and `.fa-border` on the same icon
Please add to your stylesheet:
```css
.fa-fw.fa-border {
  width: 1.58571429em;
}
```

Ref: [#8309](https://github.com/FortAwesome/Font-Awesome/issues/8309)

---

#### Icon placement when used in input with feedback
Use this markup:
```html
<div class="form-group has-feedback">
  <label class="control-label">Font Awesome</label>
  <input type="text" class="form-control">
  <span class="form-control-feedback">
    <i class="fa fa-search"></i>
  </span>
</div>
```

Ref: [#4313](https://github.com/FortAwesome/Font-Awesome/issues/4313)