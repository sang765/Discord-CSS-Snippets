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
[class^=outer] [class^=section_] [class^=list_] {
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
[class^=fullOuter] [class^=activitySimplifiedProfile] [class^=defaultColor],
[class^=outer] [class^=section] [class*=defaultColor]:has([class^=voiceIcon]) {
	text-align: left;
}
[class^=outer]:not(:has([class^="visibleContainer"])) [class^=avatar][class*="clickable"] {
	left: 36.5%;
}
[class^=outer] [class^=footer]:has(button) [class^=wrapper][class*=biteSize]:has(:nth-child(1):last-child),
[class^=outer]:has([class^="visibleContainer"]) [class^=wrapper][class*=biteSize]:has(:nth-child(3):last-child),
[class^=outer]:has([class^="visibleContainer"]) [class^=wrapper][class*=biteSize]:has(:nth-child(4)) {
	right: 12px;
}
[class^=outer]:not(:has([class^="visibleContainer"])) [class^=wrapper][class*=biteSize]:has(:nth-child(2):last-child) {
	right: 38%;
}
[class^=outer]:not(:has([class^="visibleContainer"])) [class^=wrapper][class*=biteSize]:has(:nth-child(3):last-child) {
	right: 31.5%;
}
[class^=outer]:not(:has([class^="visibleContainer"])) [class^=wrapper][class*=biteSize]:has(:nth-child(4):last-child) {
	right: 24.7%;
}
[class^=outer]:has([class*=biteSize]) [class^=addCustomStatusButtonBubble] [class^=statusBubbleOuter]::after,
[class^=outer]:has([class*=biteSize]) [class^=addCustomStatusButtonBubble] [class^=statusBubbleOuter]::before {
	display: none;
}
[class^=outer]:has([class*=biteSize]) [class^=addCustomStatusButtonBubble] {
	top: 30px;
	margin-top: 10px;
    	left: 92px;
	margin-bottom: 25px;
}
[class^='mask_'] > foreignObject {
	mask-image: none;
}
[class^=wrapper] [class^="mask_"] foreignObject [class^=avatarStack] img,
[id^=chat-message] [class^=contents] [class^=avatar_] {
	border-radius: 50px;
}
```
