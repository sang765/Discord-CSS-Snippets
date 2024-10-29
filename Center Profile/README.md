## Center Profile
- Margin your profile to center


## Preview:
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
/* Center Profile On Simplified Profile */
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
[class^=biteSizeOuter] [role=group], /*Badges*/
[class*=SizeOuter] [class^=tabBar],
[class*=SizeOuter] [class^=memberSinceWrapper],
[class*=SizeOuter] section [class^=list],
[class^=userPanelOuter] [class^=usernameRow],
[class^=userPanelOuter] [class^=tags_] {
  justify-content: center;
}
[class*=SizeOuter] [class^=nicknameIcons],
[class^=userPanelOuter] [class^=nicknameIcons] {
  display: none;
}
[class*=SizeOuter] [class^=chipletContainerInner] {
  display: flex;
}
[class*=SizeOuter] [class^=descriptionClamp],
[class*=SizeOuter] [class^=container] [class^=defaultColor],
[class^=biteSizeOuter_] [class^=activityBiteSizePopout_],
[class*=SizeOuter] [class^=markup],
[class*=SizeOuter] [class^=section] [class*=defaultColor],
[class*=SizeOuter] textarea,
[class^=userPanelOuter] [class^=overlayBackground] [class^=section] {
  text-align: center;
}
[class*=SizeOuter] [class^=viewFullBio] {
  margin: 12px auto 0px;
}
[class^=activityBiteSizePopout] [class^=textLeft],
[class^=fullSizeOuter] [class^=activitySimplifiedProfile] [class^=defaultColor] {
  text-align: left;
}
```