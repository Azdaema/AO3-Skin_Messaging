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
