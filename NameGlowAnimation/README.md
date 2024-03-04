## Name Glow Animation
- Added glow animation for display name, member list and mention


## Screenshot Preview:
![image](https://github.com/sang765/vencord-css-snippets/assets/80249864/06f9711f-90e8-4541-8552-4c1a26e59376)
![image](https://github.com/sang765/vencord-css-snippets/assets/80249864/20ce2b12-278b-4aae-8c06-f4e0cbab4d0e)


## CSS Code:
```css
/* Username, Memberlist and Nickname Glow */
.username_d272d6,
.username_d30d99,
.nickname__3d1d7,
.text-lg-semibold__18f10,
.mention {
  text-shadow: 0px 0px 0px currentColor;
  animation: glow 1s ease-in-out infinite alternate;
}
@keyframes glow {
 form {
	text-shadow: 0px 0px 0px currentColor, 0px 0px 5px currentColor, 0px 0px 10px currentColor;
 }
 to {
	text-shadow: 0px 0px 5px currentColor, 0px 0px 10px currentColor, 0px 0px 15px currentColor;
 }
}
```
