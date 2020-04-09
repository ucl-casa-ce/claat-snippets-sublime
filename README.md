# Introduction

A collection of snippets for [CLAAT (CodeLab As A Thing)](https://github.com/googlecodelabs/tools) (Google's CodeLab As A Thing) markdown files which supports the learning and teaching within [UCL Connected Environments Lab](https://www.connected-environments.org).

![Overview Preview](https://github.com/ucl-casa-ce/claat-snippets-vscode/raw/master/img/overview.gif)

# Installation

### Via Package Control
The easiest way is to install it via [Package Control](https://packagecontrol.io).

- Install [Package Control](https://packagecontrol.io/installation).
- Go to **Command Palette** <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> or <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
- Select **Package Control : Install Package**
- Search for **Claat Snippets**

### Manual

- Clone the repository or download the [ZIP](https://github.com/ucl-casa-ce/claat-snippets-sublime/archive/master.zip)
- Extract the archive
- Put it in your **Packages**( `Preferences > Browse Packages...` ) directory.  

# Usage

Type part of a snippet, starting with `!claat`, press `enter` and the snippet will unfold. For snippets in markdown format you need to press `ctrl+space` (Windows / Linux) or `cmd+space` (OSX).  Pressing tab will allow you to skip between fields. 

# CLAAT Snippets

**Note**: Sublime doesn't like exclaimation points in snippets triggers therefore it is omitted from this extension.

| Snippet | Content |
| ------- | ------- |
| `claat-header` | Creates a Codelab Header |
| `claat-create-empty-step` | Create an Empty Codelab Step |
| `claat-create-example-step` | Create an Example Codelab Step |
| `claat-create-parts-list` | Create a Parts List |
| `claat-infobox` | Add a positive style info box |
| `claat-infobox-negative` | Add a negative style info box |
| `claat-download-button` | Add a download link |


# Future Work

The plan is to intgrate this into the claat workflow in the future by allowing building of the codelab within vscode.  Watch this space!

# Reporting Issues

Issues should be reported in the [project issue tracker](https://github.com/ucl-casa-ce/claat-snippets-sublime/issues).

# Author

Steven Gray - 08-04-2020

# Licence

All of CLAAT Snippets is licensed under the MIT license.

Copyright (c) 2020 Steven Gray - UCL CASA Connected Environments

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
