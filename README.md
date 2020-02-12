<p float="left">
<a href="../../"><img src="https://img.shields.io/github/languages/top/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="Github top language"></a>
<a href="../../"><img src="https://img.shields.io/github/repo-size/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="Repository size"></a>
<a href="../../issues"><img src="https://img.shields.io/github/issues/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="Issues"></a>
<a href="/LICENSE.md"><img src="https://img.shields.io/github/license/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="License"></a>
<a href="../../commits/master"><img src="https://img.shields.io/github/commit-activity/m/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="Commit activity"></a>
<a href="../../commits/master"><img src="https://img.shields.io/github/last-commit/FredHappyface/VSCode.OSKeybindings.svg?style=flat-square" alt="Last commit"></a>
</p>

# VSCode.OSKeybindings

<img src="linuxkeybindings/Linux.png" alt="Project Icon" width="100">
<img src="mackeybindings/Mac.png" alt="Project Icon" width="100">
<img src="windowskeybindings/Windows.png" alt="Project Icon" width="100">


- Use Linux Keybindings on any OS
- Use Mac Keybindings on any OS
- Use Windows Keybindings on any OS

This extension does not remove any existing bindings. On the same os as that of
the keybindings that means everything will be bound twice. On other OS' that
means that the keybindings will be in addition to the default (note that they
take precedence over the default bindings)

Take a look at https://code.visualstudio.com/api/get-started/your-first-extension
to get started.

## Issues/ Conflicts

There are some known issues and conflicts with other keybinding extensions.
Currently, this is best fixed manually - see
- https://github.com/yzhang-gh/vscode-markdown/issues/396
- https://github.com/Microsoft/vscode/issues/39888

Here is a list of those that I have suffered from. Follow the links and copy the
contents of the file into your keybindings json file. Note that I'll add these
to the extension at some point:
- [Markdown All In One](MarkdownAllInOne.json)

## Download
### Clone
#### Using The Command Line
1. Press the Clone or download button in the top right
2. Copy the URL (link)
3. Open the command line and change directory to where you wish to
clone to
4. Type 'git clone' followed by URL in step 2
```bash
$ git clone https://github.com/FredHappyface/VSCode.OSKeybindings
```

More information can be found at
<https://help.github.com/en/articles/cloning-a-repository>

#### Using GitHub Desktop
1. Press the Clone or download button in the top right
2. Click open in desktop
3. Choose the path for where you want and click Clone

More information can be found at
<https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop>

### Download Zip File

1. Download this GitHub repository
2. Extract the zip archive
3. Copy/ move to the desired location


## Licence
BSD2-Patent License
Copyright (c) FredHappyface
(See the [LICENSE](/LICENSE.md) for more information.)
