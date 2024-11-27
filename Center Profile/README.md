## Center Profile
- Margin your profile to center


## Preview:
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
/* Center Profile On Simplified Profile */
/* Center Profile On Simplified Profile */
[class^=outer] [class^=usernameRow],
[class^=outer] [class^=tags_],
[class^=outer] [class^=root_],
[class^=outer] [class^=body] [style^=gap],
[class^=outer] [class^=mutuals_],
[class^=outer] [class^=chipletContainerInner],
[class^=outer] [class^=container] [class^=buttonContainer],
[class^=biteOuter_] [class^=activityBiteOuterPopout_] [class^=headerContainer_],
[class^=biteOuter_] [class^=activityBiteOuterPopout_] [class^=details_],
[class^=outer] [class^=blockquoteContainer]:has([class^=blockquoteDivider]),
[class^=biteOuter] [role=group], /*Badges*/
[class^=outer] [class^=tabBar],
[class^=outer] [class^=memberSinceWrapper],
[class^=outer] section [class^=list],
[class^=userPanelOuter] [class^=usernameRow],
[class^=userPanelOuter] [class^=tags_] {
  justify-content: center;
}
[class^=outer] [class^=nicknameIcons],
[class^=userPanelOuter] [class^=nicknameIcons] {
  display: none;
}
[class^=outer] [class^=chipletContainerInner] {
  display: flex;
}
[class^=outer] [class^=descriptionClamp],
[class^=outer] [class^=container] [class^=defaultColor],
[class^=biteOuter_] [class^=activityBiteOuterPopout_],
[class^=outer] [class^=markup],
[class^=outer] [class^=section] [class*=defaultColor],
[class^=outer] textarea,
[class^=userPanelOuter] [class^=overlayBackground] [class^=section] {
  text-align: center;
}
[class^=outer] [class^=viewFullBio] {
  margin: 12px auto 0px;
}
[class^=activityBiteOuterPopout] [class^=textLeft],
[class^=fullOuter] [class^=activitySimplifiedProfile] [class^=defaultColor] {
  text-align: left;
}
[class^=outer]:not(:has([class^="visibleContainer"])) [class*="clickable"] {
	left: 36.5%;
}
[class^=outer] [class^=wrapper][class*=biteSize] {
	right: 24.7%;
}
[class^=outer] [class^=wrapper][class*=biteSize]:not(:has([d="M4 14a2 2 0 1 0 0-4 2 2 0 0 0 0 4Zm10-2a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm8 0a2 2 0 1 1-4 0 2 2 0 0 1 4 0Z"])) {
	right: 12px;
}
```
