
## `<p>`
AO3 is designed for paragraphs of text. If you stick something without `<p>`paragraph tags`</p>` in AO3, it will try to slap `<p></p>` around it.

So to avoid this, I repurposed `<p></p>` as the tags for the texts. First I remove the margin, because having a margin is what `<p></p>` usually does.
```
margin: 0;
```

## Sides
For margin/padding/border, you can specify only one side with the words top/bottom/left/right.
* `border-bottom: solid;` Only a border along the bottom.

If you give 2 numbers in margin/padding, without top/bottom/left/right, the first number will be top/bottom, and the second number will be left/right.
* ```padding: 20px 10px;``` Twice as much padding on the top/bottom as on the sides.

You _can_ do 3 and 4 in the same style (see ["Shorthand Property"](https://www.w3schools.com/css/css_margin.asp)), but I can never remember what's what then. So I prefer:
```
margin: 0;
margin-bottom: 3px;
```
0 margin on all sides except bottom.

## `p:last-child`
iOS text sent in rapid sucession nest together. The space between them is narrower than usual, and only the very last one has a tail. To get this, I use [`p:last-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:last-child) which applies it to the last `<p></p>` element of that type in its wrapper class.

Margin after non-final texs:
```
.ios p {
  margin-bottom: 3px;
}
```

Margin after texts that are the last one in their wrapper.
```
.ios p:last-child {
  margin-bottom: 10px;
}
```

## Font size
`em` = current font-size. So `0.5em` is half the current font-size, `2em` is double the current font-size, etc.
