## Center Profile
- Margin your profile to center


## Preview:
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/c42f72ed-b98c-46d5-9a8b-fdf699983d57)
![image](https://github.com/sang765/Discord-CSS-Snippets/assets/80249864/562fb6d7-2715-4551-a967-2cad935d5c5f)



## CSS Code:
```css
/* Center Profile */
[class^="UserProfile_"] {
  text-align: center;
}
[class*="nameTagSmall_"],
[class*="title_"],
[class*="container_"],
[class*="UserProfileSection_"] > div,
[class*="tabBar_"],
[class*="guildNick_"],
[class*="connectedAccountNameTextContainer_"],
[class*="connectedAccountChildren_"] {
  justify-content: center;
}
[class*="textLeft_"] {
  display: flex;
}
div.TextProps__defaultColor.defaultColor__30336.TextStyle__text-lg\/semibold.text-lg-semibold__9539a {
  margin-right: 0px !important;
}
[class*="userInfoText_"],
[class*="profileMutuals_"],
[class*="mainContainer_"] {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
  margin-bottom: 10px;
}
[class*="note_"] textarea,
[class*="textarea_"] {
  text-align: center;
}
/* Hide Copy Username Button */
[class*="clickTarget_"] > div > div:nth-child(2) {
    display: none;
}
/* Fix Welcome New Member Message To Center*/
[class*="ThreadStarterMessage_"] {
  justify-content: left !important;
}
```