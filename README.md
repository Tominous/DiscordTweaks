# DiscordTweaks
Tweaks little UI problems and adds lots of little features that make life easier.

Versions 0.8.x and below have been deleted (by accident, they were on my old computer.)

## Installation:

Download the latest version from the releases tab, using the code raw from github wont work!
Extract the theme into src/Powercord/Themes *see screenshot:*

![](https://media.discordapp.net/attachments/695592374021390376/713752904971845642/unknown.png)

There are some css add-ons from monstrousdev, if you want to remove them, simply delete the following `@import`s in
the DiscordTweaks.css file:

```css
@import "https://monstrousdev.github.io/themes/addons/iconTabs.css";
@import "https://monstrousdev.github.io/themes/addons/iconTabs-disabledGames.css";
@import "https://monstrousdev.github.io/themes/addons/userSettingsModal.css";
@import "https://monstrousdev.github.io/themes/addons/minimalUserList.css";
```

To un-hide the gift button and the help button, remove the following from `:root` in the DiscordTweaks.css file:

```css
    --messageGiftButtonHide: none;
    --messageHelpButtonHide: none;
```

## Using and contributing to:

[Licensed under Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/)

Feel free to fork and make pull requests, im happy to accept any add-ons as long as they aren't major and ruin anything.


![License](https://image.prntscr.com/image/y_uiNcjTRMyCeAWRt5VNEw.png)

## Screenshots:
![](https://cdn.discordapp.com/attachments/713312122179813386/713749610434134142/unknown.png)
![](https://image.prntscr.com/image/-yy2AklzTiO0oJrKtlmxlw.png)
![](https://media.discordapp.net/attachments/539444185262981120/713714620526886923/unknown.png)
![](https://cdn.discordapp.com/attachments/692467048705687666/713752370122850324/unknown.png)