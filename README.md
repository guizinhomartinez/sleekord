# Custom Discord Theme
This Discord theme aims to make the Discord experience better, making the UI more modern and easy on the eyes. The theme is lightweight and beautiful. New releases come after 40 commits on the project. Alternatively, you can use the latest commit verison, as they are almost always stable and do not have problems.
Currently on the project, there are only two settings you can change blur-ammount and font-primary, you can change these by following the installation guide.

## Installation
There are two ways of using this theme: manually and automatically. The manual way is more complicated but allows you to change variables in the project.

### Manual
First, go to your Discord themes folder (either Vencord, or BetterDiscord). There, create a new file and make it a CSS file (example: Discord-theme.css). Now, paste the following code into the file:

```
:root {
    --blur-ammount: 50px; /* Default is 50px, change this to how much you want */
    --font-primary: "SF Pro Display", Satoshi, "gg sans", sans-serif; /* Default is "SF Pro Display", change this to whatever font you want */
}

https://raw.githubusercontent.com/guizinhomartinez/custom-discord-theme/refs/heads/main/theme.css
```

This method insures that the theme is always following the latest Git commit, and thus you will not have to update the theme, as it will be updated automatically. Alternatively, you can copy and paste the source of the theme into the file aswell, but this requires manual updating.

### Automatic
(As far as I know, this only applies to Vencord, as I do not use BetterDiscord)
<br> Go to Settings > Themes > Online Themes
<br> Paste this URL:<br>
```
https://raw.githubusercontent.com/guizinhomartinez/custom-discord-theme/refs/heads/main/theme.css
```
<br> This method also is linked to the latest Git commit, and thus will also not have to require updating manually.

## Good info to know
- This project is maintained only by me, so if I lose interest for the theme and you wish to continue development, feel free to open a Pull Request or fork the project.
- This theme is unlikely to break, but new Discord updates always break some elements, so wait a couple of hours for a hotfix update before opening an Issue.

