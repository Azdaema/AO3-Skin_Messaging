For a theme, you generally want something like:

```css
/* wallpaper */
.line.themename {background-image: url("FILL_IN");}

/* outgoing text bubble color */
.line.themename .out dd {background: FILL_IN;}
.line.themename .out dd:before {border-color: FILL_IN;}

/* incoming text bubble color */
.line.themename .in dd {background: FILL_IN;}
.line.themename .in dd:before {border-color: FILL_IN;}

/* text font color */
.line.themename .out dd,
.line.themename .in dd {color: FILL_IN}

/* timestamp font color */
.line.themename .out dd sub,
.line.themename .in dd sub {color: FILL_IN;}
```
