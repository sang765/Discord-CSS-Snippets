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
[class^=outer] [class^=wrapper][class*=biteSize]:not(:has([d="M5.26 12.45c.1.03.18.08.25.14l.52.44 5.26 5.26a1 1 0 0 1 0 1.42l-.58.58a1 1 0 0 1-1.42 0l-1.61-1.61a.25.25 0 0 0-.36 0L6.3 19.7a1 1 0 0 0-.29.7V21a1 1 0 0 1-1 1H3.41a1 1 0 0 1-.7-.3l-.42-.4a1 1 0 0 1-.29-.71V19a1 1 0 0 1 1-1h.59a1 1 0 0 0 .7-.3l1.03-1.02c.1-.1.1-.26 0-.36l-1.61-1.61a1 1 0 0 1 0-1.42l.58-.58a1 1 0 0 1 .97-.26ZM18.01 10.37a1 1 0 0 1-1.4-.11L13.86 7a1 1 0 0 1 0-1.3l2.7-3.18c.28-.34.7-.53 1.14-.53H21a1 1 0 0 1 1 1v3.3c0 .45-.2.86-.53 1.15L18 10.37Z"])) {
	right: 31.5%;
}
```
