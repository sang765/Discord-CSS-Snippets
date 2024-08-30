## Center Profile
- Margin your profile to center


## Preview:
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
/* Center Profile On Simplified Profile */
/* biteSizeOuter */
[class*=SizeOuter] [class^=usernameRow],
[class*=SizeOuter] [class^=tags_],
[class*=SizeOuter] [class^=root_],
[class*=SizeOuter] [class^=body] [style^=gap],
[class*=SizeOuter] [class^=mutuals_],
[class*=SizeOuter] [class^=chipletContainerInner],
[class*=SizeOuter] [class^=container] [class^=buttonContainer],
[class^=biteSizeOuter_] [class^=activityBiteSizePopout_] [class^=headerContainer_],
[class^=biteSizeOuter_] [class^=activityBiteSizePopout_] [class^=details_],
[class*=SizeOuter] [class^=blockquoteContainer]:has([class^=blockquoteDivider]),
[class^=biteSizeOuter] [role=group] /*Badges*/{
  justify-content: center;
}
[class*=SizeOuter] [class^=nicknameIcons] {
  display: none;
}
[class*=SizeOuter] [class^=chipletContainerInner] {
  display: flex;
}
[class*=SizeOuter] [class^=descriptionClamp],
[class*=SizeOuter] [class^=container] [class^=defaultColor],
[class^=biteSizeOuter_] [class^=activityBiteSizePopout_] {
  text-align: center;
}
[class*=SizeOuter] [class^=viewFullBio] {
  left: 9.5vh;
}
[class^=activityBiteSizePopout] [class^=textLeft] {
  text-align: left;
}
/* fullSizeOuter */
[class*=SizeOuter] [class^=tabBar],
[class*=SizeOuter] [class^=memberSinceWrapper] {
  justify-content: center;
}
[class*=SizeOuter] [class^=markup],
[class*=SizeOuter] [class^=section] [class*=defaultColor],
[class*=SizeOuter] textarea {
  text-align: center;
}
[class^=fullSizeOuter] [class^=activitySimplifiedProfile] [class^=defaultColor] {
  text-align: left;
}
/* User Panel */ 
[class^=userPanelOuter] [class^=usernameRow],
[class^=userPanelOuter] [class^=tags_] {
  justify-content: center;
}
[class^=userPanelOuter] [class^=overlayBackground] [class^=section] {
  text-align: center;
}
[class^=userPanelOuter] [class^=nicknameIcons] {
  display: none;
}
```