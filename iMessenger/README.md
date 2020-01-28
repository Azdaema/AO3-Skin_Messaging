# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessenger">

</dl>
```
# Texts
* `in` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `out` is for outgoing texts: the ones on the righthand side, being sent from from phone.

```html
<dl class="imessenger">

	<div class="in">
		<dt>Character1</dt>
		<dd>are you there yet?</dd>
		<dd>Where are you?</dd>
	</div>

	<div class="out">
		<dt>Character2</dt>
		<dd>I'm waiting outside</dd>
		<dd>wait I can see you now</dd>
	</div>

</dl>
```

; `<dt></dt>` 
: For the characters' names. They will he hidden unless a reader turns off the work skin. Then they will show up, so it's still clear who is sending which messages.

; `<dd></dd>`
: For the texts themselves.

# Timestamps
```html
<h4 class="time">timestamp content</h4>
```

# Atypical texts
`pic` is a class for texts which do not have a bubble around them. Typically this means pictures, up to 3 emojis, and rich links.

### Photos
```html
<div class="out">
	<dt>Cersei</dt>
	<dd>Look what they got at the tap</dd>
	<dd class="pic"><img src="https://thumbs.worthpoint.com/zoom/images3/1/0817/09/bally-baby-pac-man-pacman-commercial_1_325f8047914c5ee8676857358454b56f.jpg" /></dd>
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
	<dt>Jaime</dt>
	<dd class="pic"><iframe src="https://www.youtube.com/embed/2an_WWubKmU?controls=0&amp;start=325&amp;modestbranding=1"></iframe></dd>
	<dd>Fitting name, no?</dd>
</div>
```
