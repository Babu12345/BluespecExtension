# Bluespec System Verilog Extension
A language extension to support Bluespec System Verilog in Visual Studio Code.

## Features
* Syntax Highlighting
* Snippets
    * `package`
    * `interface`
    * 'method'
    * 'method-norm'
    * 'interface-with-paramter'
    * `module`
    * `rule`
    * `begin...end`
    * `mkAutoFSM`, `mkAlwaysFSM`
    * 'typedef-struct'
    * 'type-def-norm'
    * 'case'
    * 'case-matches'
    * 'action'
    * 'actionvalue'
    * 'function'
    * 'import'
    * Adding more by the day


## Installation
To install from the current directory use the command:
1.vsce package //Note may need to change version name when updating. It's in package.json
2.code --install-extension myextension.vsix



## Thanks
* https://github.com/thotypous/sublime-bsv
* https://github.com/aninhumer/SublimeBluespec
* https://github.com/Raamakrishnan/bsv-for-vscode(Provided most of the initial code)
