### HTML

```html
<nav id="menu-example" class="burgermenu-left">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="has-children">
      <a href="#">Banner Panel</a>
      <div class="is-children">
        <a href="#" class="back">Back</a>
        <img src="http://lorempixel.com/273/380">
      </div>
    </li>
  </ul>
</nav>

<div class="page-wrapper">
  <a id="menu-toggle" href="#menu-example" class="menu-icon">Toggle Menu</a>
</div>
```

### JS

```js
$(function() {
  $('#menu-example').burgermenu();
});
```