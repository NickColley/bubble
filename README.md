bubble
======

A perfect ratio circle with centered text.

```html
<div class="bubble">
  <div class="bubble-outer">
    <div class="bubble-inner">
      <div class="bubble-text">
        <h2>Hello, World.</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      </div>
    </div>
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
.bubble-outer {
  position: absolute;
  left: 0; top: 0; right: 0; bottom: 0;
}
.bubble-inner {
  display: table;
  height: 100%;
  width: 100%;
}
.bubble-text {
  display: table-cell;
  vertical-align: middle;
  text-align: center;
  padding: 10%;
}
```

on codepen: http://codepen.io/nickcolley/pen/AIjay

Works IE8+ (with the exception to border-radius although you could try something like PIE.. http://css3pie.com/ :/)

Let me know if there's a better way to do this. Would love the feedback.
