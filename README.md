# # Shortcuts.fm

## Printer-friendly keyboard shortcuts for all your favorite Mac apps

## Submitting Shortcuts for an App

 1. Create an <app>.md file
Follow the format below for the front matter. 

* The layout must be `shortcuts` and the category must be one of: `communication, design, development, music, productivity, social, utilities`.

* The data-file should be the same name at the .md file. 
* The sections can be whatever you want, but should also be referenced in the data file. 

```
---
layout: shortcuts
name: 1Password
category: utilities
data-file: 1password
sections:
  - Hotkeys
  - General
  - 1Password Mini
---
```

2. Create a <app>.yml data file. 
This file will contain all the sections and shortcuts referenced in the markdown file. 

Here’s an example: 

```
name: 1Password

sections:
  - hotkeys
  - general
  - 1password mini

hotkeys:
  - shortcut: ⌘ \
    desc: Fill Logins into Web Browser

  - shortcut: ⌥ ⌘ \
    desc: Show 1Password Mini

  - shortcut: ⌃ ⌥ ⌘ L
    desc: Lock 1Password

general:
  - shortcut: ⌘ ,
    desc: Open Preferences

  - shortcut: ⌘ {
    desc: Previous Category
```

3. Submit a pull request with your app!


