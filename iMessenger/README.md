# Timestamps
```html
<h4 class="time">timestamp content</h4>
```

# Texts
* `in` is for incoming texts: the ones on the lefthand side, being sent from another phone.
* `out` is for outgoing texts: the ones on the righthand side, being sent from from phone.

```html
<div class="in/out">
  <dt>character's name</dt>
  <dd>text</dd>
  <dd>second text sent just after the first</dd>
</div>
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
