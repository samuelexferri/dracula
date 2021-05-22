# Thunderbird

Theme: [Dracula](https://draculatheme.com/) (Modified)

Dracula theme for Mozilla Thunderbird

## Instructions

Unlock custom CSS usage in Thunderbird 69 and newer:

    Settings/Options > Advanced > General > Config Editor...
    toolkit.legacyUserProfileCustomizations.stylesheets > true

Move `chrome` folder and `user.js` file to:

    C:\Users\[user]\AppData\Roaming\Thunderbird\Profiles\[random letters and numbers].default\

Install the theme add-on:

    Tools > Add-ons > Settings (cog wheel) > Install Add-on From File...

This theme is from Dracula but I change the sidebar border color in `manifest.json`:

    "sidebar_border": "rgb(40, 42, 54)",

Modify the start page in Thunderbird settings: `https://draculatheme.com/`
