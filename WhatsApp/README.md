# Wrapper
Wrap your whole texting section in this:
```html
<dl class="whatsapp">

</dl>
```

# Timestamps
In WhatsApp, every single text has a timestamp attached to it, and they're always visable.

```html
<div class="out">
  <dt>Ricky</dt>
  <dd>double blue checkmark<sub>4:12 PM</sub></dd>
  <dd>double gray checkmark<sub class="received">4:13 PM</sub></dd>
  <dd>single gray checkmark<sub class="notreceived">4:14 PM</sub></dd>
</div>
```

### Days
The label for what day it is is:
```html
<h4 class="day">Today</h4>
```

# Emojis
```html
<div class="in">
  <dt>Mabel</dt>
  <dd class="emoji1">💖<sub>4:16 PM</sub></dd>
  <dd class="emoji2">💖💖<sub>4:16 PM</sub></dd>
  <dd class="emoji3">💖💖💖<sub>4:16 PM</sub></dd>
</div>
```

# Pictures
If you're sending an image plus a text with it, it's:

```html
<div class="out">
  <dt>Aulus Agerius</dt>
  <dd class="pic">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" />
    Should I buy you one?
    <sub>4:16 PM</sub>
  </dd>
</div>
```

Where are if you're _only_ sending a picture, without any text, the class is `class="pic solo"`. This makes it so that the timestamp is in the corner of the image.

```html
<div class="out">
  <dt>Aulus Agerius</dt>
  <dd class="pic solo">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Uncrossed_gladius.jpg" />
    <sub>4:16 PM</sub>
  </dd>
</div>
```

# Colors
[WhatsApp brand standards](https://whatsappbrand.com/)

|                      | hex       | swatch |
| -------------------: | :-------- | :----- |
| Teal Green           | `#075E54` | ![#075E54](https://placehold.it/15/075E54?text=+)
|                      | `#128C7E` | ![#128C7E](https://placehold.it/15/128C7E?text=+)
| Light Green          | `#25D366` | ![#25D366](https://placehold.it/15/25D366?text=+)
| White                | `#FFFFFF` | ![#FFFFFF](https://placehold.it/15/FFFFFF?text=+)
| Outgoing Chat Bubble | `#DCF8C6` | ![#DCF8C6](https://placehold.it/15/DCF8C6?text=+)
| Checkmark Blue       | `#34B7F1` | ![#34B7F1](https://placehold.it/15/34B7F1?text=+)
| Chat Background      | `#ECE5DD` | ![#ECE5DD](https://placehold.it/15/ECE5DD?text=+)
