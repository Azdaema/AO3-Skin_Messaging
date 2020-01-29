# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessenger">

</dl>
```

# Texts
* `<dt></dt>` is for the characters' names. They will he hidden unless a reader turns off the work skin. Then they will show up, so it's still clear who is sending which messages.
* `<dd></dd>` is for texts themselves.

Classes:
* `in` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `out` is for outgoing texts: the ones on the righthand side, being sent from from phone.
* `g_out` is for green outgoing texts.

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
## Atypical texts
`pic` is a class for texts which do not have a bubble around them. Typically this means:
* pictures
* up to 3 emojis
* rich links (that thing where you send a youtube video link and then there's a little video thingy rather than a link)

### Photos
```html
<div class="out">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
	<dd class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" /></dd>
</div>
```

### Emojis
```html
<div class="in">
	<dt>Mabel</dt>
	<dd class="pic">💖💖💖</dd>
</div>
```

### Rich links
```html
<div class="in">
	<dt>Ricky</dt>
	<dd class="pic"><iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe></dd>
</div>
```

# Other things
I use header tags for these, so than when someone clicks "Hide Creator's Style", they are still clearly distinct from the body of the conversation.

### Contact header
```html
<h1 class="contact"><span class="arrow"></span>Momo</h1>
```

### Time
```html
<h4 class="time"><b>Today,</b> 11:49 AM</h4>
```
