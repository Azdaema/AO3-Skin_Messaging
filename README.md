# Overview
These are designed ot be used as [AO3 skins](https://archiveofourown.org/admin_posts/1370), which is to say, they were designed to be used in a literary context, where as part of the story, characters text each other. This code can definitely be used for other things too, but there are a few things to be aware of. Like how on AO3, only [these CSS properties](https://archiveofourown.org/help/skins-creating.html) and [these HTML tags](https://archiveofourown.org/help/html-help.html) can be used.

AO3 has an "Hide Creator's Style" option, which basically turns off the CSS. So then you're falling back on the original characteristics of the tags. In that case, you still want it to be clear who is sending which texts. That is why I designed all these based around a `<dl>` list. The basic setup is that `<dt>` is the people's names, and `<dd>` is the texts themselves. The names may or may not be hidden, depending on the app, but if the CSS is turn off, they will always be revealed.

# Features
|                | iMessage | iMessage<br>Retro  | WhatsApp | Snapchat | LINE | Facebook<br>Messenger |
|---------------:|:--------:|:------------------:|:--------:|:--------:|:----:|:---------------------:|
| Contact header | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:               | :heavy_check_mark: | :heavy_check_mark: | :no_entry_sign: |
| Typing footer  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:               | :no_entry_sign:    | :no_entry_sign:    | :no_entry_sign: |
| Group chat     | :heavy_check_mark: | :heavy_check_mark: | :no_entry_sign:                  | :no_entry_sign:    | :heavy_check_mark: |
| Pictures       | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: / :wavy_dash: | :heavy_check_mark: | :heavy_check_mark: |
| Emojis         | :heavy_check_mark: | :wavy_dash:        | :heavy_check_mark:               | :heavy_check_mark: | :heavy_check_mark: |

# Using it
They all have the basic structure of:
* `<dt></dt>` for the characters' names
* `<dd></dd>` for texts themselves

Each section is wrapped in a `<div>`
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

# Other
Most popular app by country:
* circa 2017 https://www.messengerpeople.com/wp-content/uploads/2019/07/statistik-messenger-apps-top-by-country-en-stand-2019-09.png
* circa 2019 https://i.redd.it/cmh3gex4x0531.png

* https://archiveofourown.org/works/12142470 Discord
* https://archiveofourown.org/works/8631214/chapters/20774911 android
* https://archiveofourown.org/works/21038993 KakaoTalk
* https://archiveofourown.org/works/21099596/chapters/50203892 tumblr

<!-- https://www.viget.com/articles/equating-color-and-transparency/ -->
<!-- [Craig Buckler's other way of sizing absolute elements](https://www.sitepoint.com/css-sizing-absolute-position/) -->


# imessage
https://www.theverge.com/2011/12/13/2612736/ios-history-iphone-ipad

old: up until ios 6

new: ios 7 and onward
