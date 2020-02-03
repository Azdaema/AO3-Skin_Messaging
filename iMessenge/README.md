# Wrapper
Wrap your whole texting section in this:
```html
<dl class="imessenge">

</dl>
```

### Group texts
In a group text situation, incoming texts will show the sender's name.
```html
<dl class="imessenge grouptext">

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
<dl class="imessenge">

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
```
```html
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
<h1 class="contact">Momo</h1>
```

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
Could also be used with a `<dt></dt>` tag or something, depending on how you prefer it to look in "Hide Creator's Style" mode.

# Colors
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
