# G-code syntax highlighting for Sublime Text
Syntax Definition for Sublime Text that provides highlighting for G code (ISO 6983, DIN 66025, RS-274)

[![Screenshot](docs/screenshot.png)](docs/screenshot.png)


# Installation


## Package Control

Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> to open the console. Then:

Enter:
``` 
Package Control: Install Package
```

Then search for:
``` 
G code
```

Install the package, and enjoy! `G-code` is now available as one of the syntax highlighting options!


## Out of Maintenance 

<s>Hi, unfortunately I stopped maintaining this shortly after creating it. I use vim almost exclusively now, and lately there has not been much new g code to read.</s>

Picked back up by [Gabriel Staples](https://github.com/ElectricRCAircraftGuy) on 19 Mar. 2022.


# Notes to developers of this package

_Tested in Sublime Text 4 (build 4126) on Linux Ubuntu 20.04._


1. `.tmLanguage` and `.YAML-tmLanguage` files are apparently some sort of ubiquitous [TextMate](https://en.wikipedia.org/wiki/TextMate)-inspired language grammar files used for specifying syntax highlighting rules. 
1. Marlin g-code (for 3D printers) official reference pages: https://marlinfw.org/meta/gcode/
1. Sublime Text pages:
    1. Syntax Definitions: http://www.sublimetext.com/docs/syntax.html
    1. www.sublimetext.com/docs/syntax.html
1. Package Control: Customizing Packages: https://packagecontrol.io/docs/customizing_packages
1. \*\*\*\*\*TextMate language grammars documentation: https://macromates.com/manual/en/language_grammars; ex:
    1. `support.variable`, `comment.line`, `markup.bold`, `support.function`, etc.
1. To have Sublime Text **auto-convert a Textmate `.tmLanguage` file into a `.sublime-syntax` file** for you, open up the `.tmLanguage` file in Sublime Text, then go to Tools --> Developer --> "New Syntax from \*.tmLanguage..."
1. To **check a syntax highlighting scope of a particular place in a source code file**, in order to check to see if your syntax highlighting is working, or to see what scope a certain color and formatting come from for a syntax highlighting you like, place your cursor in the code where you want to check, then go to `Tools` --> `Developer` --> `Show Scope Name`. Click the "Copy" link in the little box that pops up over the source code if you'd like to copy that scope name.
