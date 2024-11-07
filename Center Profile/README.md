## Center Profile
- Margin your profile to center


## Preview:
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
/* Center Profile On Simplified Profile */
/* Center Profile On Simplified Profile */
[class*=Size] [class^=usernameRow],
[class*=Size] [class^=tags_],
[class*=Size] [class^=root_],
[class*=Size] [class^=body] [style^=gap],
[class*=Size] [class^=mutuals_],
[class*=Size] [class^=chipletContainerInner],
[class*=Size] [class^=container] [class^=buttonContainer],
[class^=biteSize_] [class^=activityBiteSizePopout_] [class^=headerContainer_],
[class^=biteSize_] [class^=activityBiteSizePopout_] [class^=details_],
[class*=Size] [class^=blockquoteContainer]:has([class^=blockquoteDivider]),
[class^=biteSize] [role=group], /*Badges*/
[class*=Size] [class^=tabBar],
[class*=Size] [class^=memberSinceWrapper],
[class*=Size] section [class^=list],
[class^=userPanelOuter] [class^=usernameRow],
[class^=userPanelOuter] [class^=tags_] {
  justify-content: center;
}
[class*=Size] [class^=nicknameIcons],
[class^=userPanelOuter] [class^=nicknameIcons] {
  display: none;
}
[class*=Size] [class^=chipletContainerInner] {
  display: flex;
}
[class*=Size] [class^=descriptionClamp],
[class*=Size] [class^=container] [class^=defaultColor],
[class^=biteSize_] [class^=activityBiteSizePopout_],
[class*=Size] [class^=markup],
[class*=Size] [class^=section] [class*=defaultColor],
[class*=Size] textarea,
[class^=userPanelOuter] [class^=overlayBackground] [class^=section] {
  text-align: center;
}
[class*=Size] [class^=viewFullBio] {
  margin: 12px auto 0px;
}
[class^=activityBiteSizePopout] [class^=textLeft],
[class^=fullSize] [class^=activitySimplifiedProfile] [class^=defaultColor] {
  text-align: left;
}
```