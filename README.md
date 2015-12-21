# Discord-iM@S-Theme

iM@S Themes for Discord.
## Currently Available Themes

- Yayoi

## How To Use

### Using Console

If you don't know how to get to console:

1. Ctrl + Shift + I in Discord
2. Open Console
#### Install iM@S Theme
```javascript
iMASCSS = document.createElement("link");
iMASCSS.setAttribute("id", "iMASCSS");
iMASCSS.setAttribute("rel", "stylesheet");
iMASCSS.setAttribute("type", "text/css");
document.getElementsByTagName("head").item(0).appendChild(iMASCSS);
```
#### Select/Change Themes
```javascript
// Replace NAME below with character's name, e.g. Yayoi
document.getElementById("iMASCSS").setAttribute("href", "https://Natsulus.github.io/Discord-iMAS-Theme/NAME%20Theme.css");
```
#### Remove Theme
```javascript
document.getElementById("iMASCSS").setAttribute("href", "");
```
#### Uninstall iM@S Theme
```javascript
document.getElementsByTagName("head").item(0).removeChild(iMASCSS);
delete iMASCSS;
```
### Using BetterDiscordApp

[Installation Info is Available Here](https://github.com/Jiiks/BetterDiscordApp)
#### Custom CSS

Copy and paste from the **_NAME_ Theme.css** file. _NAME_ being the character's name. (Do not use the BDA version)
#### Themes

Download the BDA version of the css themes you want to `%appdata%\BetterDiscord\themes\`.
