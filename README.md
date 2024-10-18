# Acme Cross-Assembler for VS Code (C64, MEGA65))
This extension provides ACME cross-assembler language support for [Visual Studio Code](https://marketplace.visualstudio.com/). Now you can develop Commodore 64 and MEGA65 games in 6502 assembly code using a powerful modern interface.

This extension was forked from Tony Landi's original extension that supported just the C64: https://marketplace.visualstudio.com/items?itemName=TonyLandi.acmecrossassembler

Changes in this extension is the additional opcodes provided by the 45gs10 CPU used in the MEGA65. You cal also still develop for the C64.

_**This extension is still a work-in-progress as such, there is still a lot of work to be done... and I have a day job.**_

## Features

- Syntax highlighting and source editing for Marco Baye's [ACME cross-assembler](https://sourceforge.net/projects/acme-crossass). 

#### Screenshots
TODO

## How to use this extension?

Install and open [Visual Studio Code](https://code.visualstudio.com). Press `Ctrl+Shift+X` or `Cmd+Shift+X` to open the Extensions pane. Find and install the _Acme Cross Assembler_ extension. You can also install the extension from the [Marketplace](https://marketplace.visualstudio.com). Open any `.asm` or `.acme` file in VS Code. The extension is now activated.

### Customizing the extension features

Given that the extension is still early in development there aren't really any features to customize. So you get what it has for now.

## Building and Debugging the Extension

You can set up a development environment for debugging the extension during extension development.
Read more at [Building, Debugging and Sideloading the extension in Visual Studio Code](https://github.com/Microsoft/vscode-go/wiki/Building,-Debugging-and-Sideloading-the-extension-in-Visual-Studio-Code).

## Known Issues

None yet. Let's see how long that lasts.

## About ACME Cross-Assembler
Marco Baye's [ACME cross-assembler](https://sourceforge.net/projects/acme-crossass) is a very popular tool which can produce code for the 6502, 6510 (including illegal opcodes), 65c02 and 65816 processors. 

This assembler has been ported to several platforms including Amiga, DOS, and Linux. It includes support the standard assembler stuff like global/local/anonymous labels, offset assembly, conditional assembly and looping assembly. It can include other source files as well as binaries while assembling.

## Acknowledgements

Thanks to [Tony Landi for his original C64 Extension](https://marketplace.visualstudio.com/items?itemName=TonyLandi.acmecrossassembler).

This project was heavily influenced by [Zeh Fernando's](https://github.com/zeh/vscode-dasm) work on a similar extension for the [DASM Macro Assembler](https://marketplace.visualstudio.com/items?itemName=zehfernando.vscode-dasm) used to develop Atari 2600 games.

## Contribute
I have chosen to keep the code on my private GIT repo for the time being. I may make this a public project in the future.

## License

[GNU Public License v3.0](http://www.gnu.org/licenses/gpl-3.0.html).