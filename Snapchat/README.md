# Wrapper
Wrap your whole texting section in this:
```html
<dl class="snapchat">

</dl>
```

# Features
### [Icons](https://support.snapchat.com/en-US/a/friends-screen-icon-guide)
* Red is the default. Purple and blue need to be specified.
* The `opened` and `unopened` ones are either a square or an arrow, based on if it's in `in` or `out`.
* The itatics sandwiched in the middle is the hidden backup, for when the skin is turned off.

```html
<dd><span class="icon opened"><i>Snap (without audio) sent and opened</i></span></dd>
<dd><span class="icon opened purple"><i>Snap (with audio) sent and opened</i></span></dd>
<dd><span class="icon opened blue"><i>Chat sent and opened</i></span></dd>

<dd><span class="icon unopened"><i>Snap (without audio) sent</i></span></dd>
<dd><span class="icon unopened purple"><i>Snap (with audio) sent</i></span></dd>
<dd><span class="icon unopened blue"><i>Chat sent</i></span></dd>

<dd><span class="icon screenshot"><i>Screenshot taken of Snap (without audio)</i></span></dd>
<dd><span class="icon screenshot purple"><i>Screenshot taken of Snap (with audio)</i></span></dd>
<dd><span class="icon screenshot blue"><i>Screenshot taken of chat</i></span></dd>

<dd><span class="icon replay"><i>Snap (without audio) has been replayed</i></span></dd>
<dd><span class="icon replay purple"><i>Snap (with audio) has been replayed</i></span></dd>
```

### Day
```html
<h4 class="day">Febuary 6th</h4>
```

### Emoji
```html
<dd class="emoji">💖</dd>
```

### "No nudes"
The wrapper for this is `<dl class="snapchat nonudes">`. This is so this feature can be applied selectively. For example, maybe you have one fic which _is_ sexting, and you want to use it _there_, but you've got another fic where they're sending each other pictures of their dogs, and you don't want to use it there.

# Colors
[Snapchat brand standards](https://docs.snapchat.com/docs/design-guidelines/)

|                 | hex       | swatch |
| --------------: | :-------- | :----- |
| Snapchat Yellow | `#fffc00` | ![#fffc00](https://placehold.it/15/fffc00?text=+)
| Chat            | `#3cb2e2` | ![#3cb2e2](https://placehold.it/15/3cb2e2?text=+)
| Memories        | `#e92754` | ![#e92754](https://placehold.it/15/e92754?text=+)
| Stories         | `#9b55a0` | ![#9b55a0](https://placehold.it/15/9b55a0?text=+)
| N/A             | `#03a588` | ![#03a588](https://placehold.it/15/03a588?text=+)
