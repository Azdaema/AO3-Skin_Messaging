# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessageorig">

</dl>
```
### Grouptext
In a group text situation, incoming texts will show the sender's name.
```html
<dl class="imessageorig grouptext">

</dl>
```
### Green
Green outgoing texts, as opposed to the blue default, can be set for the conversation as a whole.
```html
<dl class="imessageorig gr">

</dl>
```
It can also be done only for specific texts, with the other texts being blue.
```html
<div class="out gr">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
</div>
```

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

# Creative decisions
iMessage circa 2012.

Things I wasn't able to do:
* The left end of the "Messages" button is supposed to be arrow shaped
* I couldn't combine bubble tails with the gradient and outline

### Colors
I was unable to find any documentation of the colors and gradients, so the colors are just grabbed from pictures.
