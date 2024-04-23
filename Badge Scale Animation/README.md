## Badge Scale Animation
- Add animation for your badges


## Preview:
<img src="assets/Discord_r3ovjmXoWy.gif" alt="Preview">



## CSS Code:
```css
/* Badge Scale Animation */
[class*="anchorUnderlineOnHover"],
.vc-platform-indicator /*Vencord Platfrom Badge*/{
  scale: 1;
  transition: all 0.5s;
}
[class*="anchorUnderlineOnHover"]:hover,
.vc-platform-indicator:hover {
  scale: 1.3;
}
/* Fix Embed Scale */
[class*="embedTitle_"],
[class*="embedAuthorName_"],
[class*="downloadLink_"] {
  scale: 1 !important;
}
```