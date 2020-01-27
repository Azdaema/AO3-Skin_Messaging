# `ios`
First, `ios` is the wrapper class. The whole skin is set up to only effect things _inside the wrapper_. So you could also use this skin for which was mostly paragraph of prose, but had one text conversion.

```css
<div class="ios">
	<div class="in">
		<p>incoming text</p>
	</div>
	<div class="out">
		<p>outgoing text</p>
	</div>
</div>
```

# `in` and `out`
`in` and `out` are for incoming and outgoing texts respectively. Texts within the same one will be grouped together, treated like they were sent in rapid succession. You can use two `in` or `out` in a row to show that someone waited a minute, with no reply.

```css
<div class="ios">
	<div class="in">
		<p>are you there yet?</p>
		<p>Where are you?</p>
	</div>
	<div class="in">
		<p>hello?? seriously where are you???</p>
	</div>
</div>
```

# `pic`
`pic` can be used for 2 different things:
1. Sending photos
2. That up to 3 big emojis thing
```css
<div class="ios">
	<div class="in">
		<p class="pic"><img src="https://picture_image_link.jpg" /></p>
	</div>
	<div class="out">
		<p class="pic">💖💖💖</p>
	</div>
</div>
```

# `time`
`time` is for times. On my phone, for texts older than one week, iOS does it in the format of:
>> **[3-letter day of the week abrv], [3-letter month abrv] [day of the month]**, [time] [AM/PM]

```
<div class="ios">
	<p class="time"><b>Jan 1</b>, 3:27 AM</p>
	<div class="in">
		<p>I love sening you tinight.</p>
	</div>
</div>
```
