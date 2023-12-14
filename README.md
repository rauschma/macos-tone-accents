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

## Input source “ABC – Extended”

* Go to “Settings > Keyboard > Text Input > Input Sources > Edit...”
    * Install the input source (=keyboard layout) “English > ABC – Extended”
    * Alas, there is no extended version for keyboard layouts other than English.
* Now you can use:
    * 1st tone (ā): Option-A
    * 2nd tone (á): Option-E
    * 3rd tone (ǎ): Option-V
    * 4th tone (à): Option-~ (key under Esc)
* Other ways of typing accents: https://support.apple.com/en-gb/guide/mac-help/mh27474/mac
