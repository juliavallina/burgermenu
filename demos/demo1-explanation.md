### HTML

```html
<nav id="menu-example" class="burgermenu-left">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="has-children">
      <a href="#">Slide Panel Submenu</a>
      <ul class="is-children">
        <li class="back"><a href="#">&lt; Back</a></li>
        <li><a href="#">Submenu element</a></li>
        <li><a href="#">Submenu element</a></li>
        <li><a href="#">Submenu element</a></li>
      </ul>
    </li>
    <li class="dropdown">
      <a href="#">Dropdown Submenu</a>
      <ul>
        <li><a href="#">Dropdown element</a></li>
        <li><a href="#">Dropdown element</a></li>
        <li><a href="#">Dropdown element</a></li>
      </ul>
    </li>
  </ul>
</nav>

<div class="page-wrapper">
  <a id="menu-toggle" href="#menu-example">Toggle Menu</a>
</div>
```

### JS

```js
$(function() {
  $('#menu-example').burgermenu();
});
```