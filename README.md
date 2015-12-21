# Discord-iM@S-Theme
iM@S Themes for Discord.

## How To Use

### Using Console

#### Installing
1. Ctrl + Shift + I in Discord
2. Open Console
3. Enter the following: <br>
```javascript
var customCSSl = document.createElement("link");
customCSSl.setAttribute("rel", "stylesheet");
customCSSl.setAttribute("type", "text/css");
//Replace NAME below with character's name, e.g. Yayoi
customCSSl.setAttribute("href", "https://Natsulus.github.io/Discord-iM-S-Theme/NAME%20Theme.css");
document.getElementsByTagName("head").item(0).appendChild(customCSSl);
```
#### Changing Themes
1. Use the following:
```javascript
document.getElementsByTagName("head").item(0).removeChild(customCSSl);
//Replace NAME below with character's name, e.g. Yayoi
customCSSl.setAttribute("href", "https://Natsulus.github.io/Discord-iM-S-Theme/NAME%20Theme.css");
document.getElementsByTagName("head").item(0).appendChild(customCSSl);
```
#### Uninstalling
1. The following will remove the theme:
```javascript
document.getElementsByTagName("head").item(0).removeChild(customCSSl);
```
### Using BetterDiscordApp
TBA
