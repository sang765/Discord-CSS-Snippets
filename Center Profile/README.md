## Center Profile
- Margin your profile to center


## Preview (Old):
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
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
[class^=userPanelOuter] [class^=usernameRow],
[class^=userPanelOuter] [class^=tags_],
[class^=outer] [class^=section_] [class^=list_],
[class^=outer] [class^=section_]:has([class^=connectedAccountContainer_]) [class^=connectedAccounts_],
[class^=outer] [class^=section] [class^=header],
[class^=outer] [class^=section] [class^=connections] {
	justify-content: center;
}
[class^=outer] [class^=nicknameIcons],
[class^=userPanelOuter] [class^=nicknameIcons],
[class^=outer] [class^=connectedAccountsColumn_]:not(:has([class^=connectedAccountContainer_])){
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
[class^=fullOuter] [class^=activitySimplifiedProfile] [class^=defaultColor],
[class^=outer] [class^=section] [class*=defaultColor]:has([class^=voiceIcon]){
	text-align: left;
}
[class^='mask_'] > foreignObject {
	mask-image: none;
}
[class^=wrapper] [class^="mask_"] foreignObject [class^=avatarStack] img,
[id^=chat-message] [class^=contents] [class^=avatar_] {
	border-radius: 50px;
}
```
