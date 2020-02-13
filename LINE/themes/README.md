For a theme, you generally want something like:

```css
/* wallpaper */
.line.themename {background-image: url("");}

/* outgoing text bubble color */
.line.themename .out dd {background: #a8bf85;}
.line.themename .out dd:before {border-color: #a8bf85;}

/* incoming text bubble color */
.line.themename .in dd {background: #96aeaa;}
.line.themename .in dd:before {border-color: #96aeaa;}

/* text font color */
.line.themename .out dd,
.line.themename .in dd {color: white}

/* timestamp font color */
.line.themename .out dd sub,
.line.themename .in dd sub {color: #8a5a3b;}
```
