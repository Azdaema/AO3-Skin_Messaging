# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessage">

</dl>
```
### Border
If you want the phone-area to be outlined:
```html
<dl class="imessage border">

</dl>
```
### Grouptext
In a group text situation, incoming texts will show the sender's name.
```html
<dl class="imessage grouptext">

</dl>
```
### Green
Green outgoing texts, as opposed to the blue default, can be set for the conversation as a whole.
```html
<dl class="imessage gr">

</dl>
```
It can also be done only for specific texts, with the other texts being blue.
```html
<div class="out gr">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
</div>
```

# Header and footer
### Contact header
`<h1>` and `<h2>` are good for this.
```html
<h1 class="contact">Momo</h1>
```
### Unsent text footer
```html
<div class="footer">
	<kbd class="typebar">I'm in love with you</kbd>
</div>
```
The send button can be made green via `<dl class="imessage gr">` or `<kbd class="typebar gr">`.

# Other features
### Time
`<h4>` and `<h5>` are good for this.
```html
<h4 class="time"><b>Today,</b> 11:49 AM</h4>
```

### Pictures
`<dd class="pic">` is for pictures.
```html
<div class="out">
	<dt>Aulus Agerius</dt>
	<dd>Look what they're selling at the forum</dd>
	<dd class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" /></dd>
</div>
```
It also works with embedded videos, to simulate rich links. Rich links are that thing where you send a youtube video link, and then there's a little video thingy rather than a link.
```html
<div class="in">
	<dt>Ricky</dt>
	<dd class="pic"><iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe></dd>
</div>
```

### Emojis
`<dd class="emoji">` is for up to 3 large emojis.
```html
<div class="in">
	<dt>Mabel</dt>
	<dd class="emoji">💖💖💖</dd>
</div>
```

### Read receipts
`<p>` and `<dt>` both work for this, depending on how you prefer it to look in "Hide Creator's Style" mode. Basically anything except `<dd>`.
```html
<div class="gr out">
	<dt>Mimi</dt>
	<dd>Can I copy your homework?</dd>
	<p class="read"><b>Read</b> 5:55 PM</p>
</div>
```

# Creative decisions
It's a bit of a mashup of iMessage over the years.

The contact header is circa 2015, because that was the last one without a contact image, and I'm guessing most people won't want to go find an image for this. However, it doesn't have the ":arrow_left: Messages" and "Details" buttons like circa 2015, but the minimalistic just a back arrow of circa 2019.

The footer only has a camera icon, like before they added the Apple store icon alongside it.

### Colors
iOS colors: iOS documentation [here](https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/color/), or more extensive documentation [here](https://noahgilmore.com/blog/dark-mode-uicolor-compatibility/).

I _think_ these are the colors used for each part.

### Bubbles
|               | light mode | dark mode |
| ------------: | :--------- | :-------- |
| `systemGray5` | ![#e5e5ea](https://placehold.it/15/e5e5ea?text=+) `rgba(229,229,234, 1.0)` | ![#2c2c2e](https://placehold.it/15/2c2c2e?text=+) `rgba(44,44,46, 1.0)`
| `systemBlue`  | ![#007aff](https://placehold.it/15/007aff?text=+) `rgba(0,122,255, 1.0)` | ![#0a84ff](https://placehold.it/15/0a84ff?text=+) `rgba(10,132,255, 1.0)`
| `systemGreen` | ![#34c759](https://placehold.it/15/34c759?text=+) `rgba(52,199,89, 1.0)` | ![#30d158](https://placehold.it/15/30d158?text=+) `rgba(48,209,88, 1.0)`

### Time
|               | light mode | dark mode |
| ------------: | :--------- | :-------- |
| `systemGray`  | ![#8e8e93](https://placehold.it/15/8e8e93?text=+) `rgba(142,142,147, 1.0)` | ![#8e8e93](https://placehold.it/15/8e8e93?text=+) `rgba(142,142,147, 1.0)`

### Header
|               | light mode | dark mode |
| ------------: | :--------- | :-------- |
| `systemGray6` | ![#f2f2f7](https://placehold.it/15/f2f2f7?text=+) `rgba(242,242,247, 1.0)` | ![#1c1c1e](https://placehold.it/15/1c1c1e?text=+) `rgba(28,28,30, 1.0)`
| `link`        | ![#007aff](https://placehold.it/15/007aff?text=+) `rgba(0,122,255, 1.0)` | ![#0984ff](https://placehold.it/15/0984ff?text=+) `rgba(9,132,255, 1.0)`
| `separator`   | ![#c6c6c8](https://placehold.it/15/c6c6c8?text=+) `rgba(60,60,67, 0.29)` | ![#38383a](https://placehold.it/15/38383a?text=+) `rgba(84,84,88, 0.6)`
