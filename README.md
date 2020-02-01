# Overview
These are designed ot be used as [AO3 skins](https://archiveofourown.org/admin_posts/1370), which is to say, they were designed to be used in a literary context, where as part of the story, characters text each other. This code can definitely be used for other things too, but there are a few things to be aware of.

AO3 throws `#workskin` in front of everything, so that's what that's about.

AO3 has an "Hide Creator's Style" option, which basically turns off the CSS. So then you're falling back on the original characteristics of the tags. In that case, you still want it to be clear who is sending which texts. That is why I designed all these based around a `<dl>` list. The basic setup is that `<dt>` is the people's names, and `<dd>` is the texts themselves. The names may or may not be hidden, depending on the app, but if the CSS is turn off, they will always be revealed.

# Using it
They all have the basic structure of:
* `<dt></dt>` for the characters' names
* `<dd></dd>` for texts themselves

Each section is wrapped in a `<div></div`
* `class="out"` is for outgoing texts; the ones being sent from from the POV phone.
* `class="in"` is for incoming texts; the ones being sent from another phone
```html
<dl class="wrapper">

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
Although each one has small alterations, depending on how that app works.

# Credits
* **iMessenger** draws upon:
  * [CodenameCarrot and La_Temperanza's](https://archiveofourown.org/works/6434845/chapters/14729722)
  * [Mark Swardstrom's](https://codepen.io/swards/pen/gxQmbj)
  * [2ne's header](https://codepen.io/2ne/pen/osvpj)
* **iMessenger Vintage** draws upon:
  * [Sean Thomas Burke's memebro](https://gist.github.com/seantomburke/3381999)
  * [Craig Buckler's other way of sizing absolute elements](https://www.sitepoint.com/css-sizing-absolute-position/)
* **WhatsApp** draws upon:
  * [ran_a_dom's](https://archiveofourown.org/works/15842043/chapters/36893073)
  * [Benni's](https://codepen.io/8eni/pen/YWoRGm)
  * [Rumbiiha swaibu's](https://codepen.io/swaibu/pen/QxJjwN)
* **Snapchat** is pretty much a wholecloth original.

# Other
* LINE
  * https://archiveofourown.org/works/19150123/chapters/45514369
  * https://archiveofourown.org/works/17489243
* https://archiveofourown.org/works/19249828 Facebook Messenger Chat
* https://archiveofourown.org/works/12142470 Discord
* https://archiveofourown.org/works/8631214/chapters/20774911 android
* https://archiveofourown.org/works/21038993 KakaoTalk
* https://archiveofourown.org/works/21099596/chapters/50203892 tumblr
