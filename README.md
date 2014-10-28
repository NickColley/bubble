bubble
======

```html
<div class="bubble">
  <div class="bubble-body">
    <span class="bubble-text">Hello, World.</span>
  </div>
</div>
```

```css
.bubble {
 overflow: hidden;
 position: relative;
 padding: 50%;
 border-radius: 50%;
 background-color: #EEE;
}

.bubble-body {
  position: absolute;
  display: table;
  left: 0; top: 0; right: 0; bottom: 0;
  margin: auto;
  height: 100%;
  width: 100%;
}

.bubble-text {
  display: table-cell;
  text-align: center;
  padding: 10%;
  font-size: 10vw;
}
```
