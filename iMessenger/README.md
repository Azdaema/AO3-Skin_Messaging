# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessenger">

</dl>
```

### Group texts
In a group text situation, incoming texts will show the sender's name.
```html
<dl class="imessenger grouptext">

</dl>
```

# Texts
* `<dt></dt>` is for the characters' names. They will he hidden unless a reader turns off the work skin. Then they will show up, so it's still clear who is sending which messages.
* `<dd></dd>` is for texts themselves.

Classes:
* `class="in"` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `class="out"` is for outgoing texts: the ones on the righthand side, being sent from from phone.
	* `class="out gr"` is for green outgoing texts.

```html
<dl class="imessenger">

	<div class="in">
		<dt>Alice</dt>
		<dd>are you there yet?</dd>
		<dd>Where are you?</dd>
	</div>

	<div class="out">
		<dt>Bob</dt>
		<dd>I'm waiting outside</dd>
		<dd>wait I can see you now</dd>
	</div>

</dl>
```

## Texts without bubbles
### Photos and rich links
`class="pic"` is for pictures and rich links (that thing where you send a youtube video link, and then there's a little video thingy rather than a link).

```html
<div class="out">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
	<dd class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" /></dd>
</div>

<div class="in">
	<dt>Ricky</dt>
	<dd class="pic"><iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe></dd>
</div>
```

### Emojis
`class="emoji"` is for up to 3 large emojis.
```html
<div class="in">
	<dt>Mabel</dt>
	<dd class="emoji">💖💖💖</dd>
</div>
```


# Other things
I use header tags for these, so than when someone clicks "Hide Creator's Style", they are still clearly distinct from the body of the conversation.

### Contact header
```html
<h1 class="contact"><span class="arrow"></span>Momo</h1>
```

`<span class="arrow"></span>` creates the "back" arrow, and is optional.

### Time
```html
<h4 class="time"><b>Today,</b> 11:49 AM</h4>
```

### Read receipts
```html
<div class="gr out">
	<dt>Mimi</dt>
	<dd>Can I copy your homework?</dd>
</div>
<p class="read"><b>Read</b> 5:55 PM</p>
```
