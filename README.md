# MacOS pinyin tone accents

Use Control-Option-[tone number] plus a vowel to type a character with a tone accent.

## MacOS key bindings

* File: `DefaultKeyBinding.dict`
* For many macOS apps such as TextEdit (but not, e.g., Visual Studio Code)
* Installation:
    * Path: `~/Library/KeyBindings/DefaultKeyBinding.dict`

More information on macOS key bindings:

* https://code.visualstudio.com/docs/getstarted/keybindings
* https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/EventOverview/TextDefaultsBindings/TextDefaultsBindings.html
* Examples:
    * Comprehensive: https://github.com/ttscoff/KeyBindings
    * https://gist.github.com/trusktr/1e5e516df4e8032cbc3d


## Visual Studio Code

* File: `keybindings.json`
* Installation:
    * Command: “Preferences: Open Keyboard Shortcuts”
    * Click on the icon “Open Keyboard Shortcuts (JSON)” in the top right corner.
    * Edit the JSON data.

More information on VS Code key bindings:

* https://code.visualstudio.com/docs/getstarted/keybindings
* Adding entries to JSON via “Define Keybinding” lets you look up the IDs of various keys.
    * Some of these IDs are unexpected—e.g., the ID for the German “Ö” key is `[Semicolon]`.
