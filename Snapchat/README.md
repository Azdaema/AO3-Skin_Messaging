# [Icons](https://support.snapchat.com/en-US/a/friends-screen-icon-guide)
Red is the default. Purple and blue need to be specified.

The `opened` and `unopened` ones are either a square or an arrow, based on if it's in `in` or `out`.

The itatics sandwiched in the middle is the hidden backup, for when the skin is turned off.
```html
<dd><span class="icon opened"><i>Snap (without audio) sent and opened</i></span></dd>
<dd><span class="icon opened purple"><i>Snap (with audio) sent and opened</i></span></dd>
<dd><span class="icon opened blue"><i>Chat sent and opened</i></span></dd>

<dd><span class="icon unopened"><i>Snap (without audio) sent</i></span></dd>
<dd><span class="icon unopened purple"><i>Snap (with audio) sent</i></span></dd>
<dd><span class="icon unopened blue"><i>Chat sent</i></span></dd>

<dd><span class="icon screenshot"><i>Screenshot taken of Snap (without audio)</i></span></dd>
<dd><span class="icon screenshot purple"><i>Screenshot taken of your Snap (with audio)</i></span></dd>
<dd><span class="icon screenshot blue"><i>Screenshot taken of chat</i></span></dd>

<dd><span class="icon replayed"><i>Snap (without audio) has been replayed</i></span></dd>
<dd><span class="icon replayed purple"><i>Snap (with audio) has been replayed</i></span></dd>
```

# Date
* Within a week https://pics.me.me/l-telstra-3-35-pm-team-snapchat-dav-nine-tuesday-me-46831517.png
* Past a week - day month year
  * https://pics.me.me/wz-a-046-8-22-pm-team-snapchat-team-a-now-42370891.png
  * https://pics.me.me/verizon-lte-2-00-pm-146-4-anna-anna-what-did-42166575.png

# Optional shitpost addition:
```css
#workskin .snapchat .icon:active:after {
  font-size: 0.6em;
  content: "[No actual nudes. Sorry. This is a fanfic.]" !important;
}
```
