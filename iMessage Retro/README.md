# Texts
* `class="in"` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `class="out"` is for outgoing texts: the ones on the righthand side, being sent from from phone.
  * `class="out gr"` is for green outgoing texts.

# Features
### Pictures
```html
<div class="out">
  <dt>Aulus Agerius</dt>
  <dd>Look what they're selling at the forum</dd>
  <dd class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" /></dd>
</div>
```

### Time
```html
<h4 class="time">Apr 11, 2012, 7:01 PM</h4>
```

### Group texts
In a group text situation, incoming texts will show the sender's name.
```html
<dl class="phone grouptext">

</dl>
```

### Contact header
```html
<h1 class="contact">Momo</h1>
```
