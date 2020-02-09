# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessageorig">

</dl>
```

# Texts
* `class="in"` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `class="out"` is for outgoing texts: the ones on the righthand side, being sent from from phone.
	* `class="out gr"` is for green outgoing texts.

# Features
### Contact header
`<h1>` and `<h2>` are good for this.
```html
<h1 class="contact">Momo</h1>
```

### Time
`<h4>` and `<h5>` are good for this.
```html
<h4 class="time"><b>Today,</b> 11:49 AM</h4>
```

### Pictures
```html
<div class="out">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
	<dd class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" /></dd>
</div>
```

### Group texts
In group text mode, incoming texts will show the sender's name.
```html
<dl class="imessageorig grouptext">

</dl>
```
