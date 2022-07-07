```
I have a vim, I have a emacs.
Eh~ vim-emacs!
I have a code, I have a vim-emacs.
Eh~ code-vim-emacs!
CVE!
```

What's `CVE` ?  Code-Vim-Emacs ! 😏

Yep, it's just a simple and hybrid keymap. Just Enjoy it. 🌟

## Overview

> ! Let's make a pact that `C` refer to `Ctrl`, `M` refer to `Alt` or `Meta`， and `S` refer to `Shift` in the following contents.

CVE pays main attention for the basic cursor moving. CVE is non-invasive which means that the original keys of VSCode still work well.

You should know that a key is just bind to some command, and commands are the really worker.

In VSCode, you can show the command pattle via `C-S-p`, but `M-x` maybe also a better choice. Now, we will give our keybindings in the following table:

| Command             | VSCode    | CVE       | Description          |
|---------------------|-----------|-----------|----------------------|
| Show All Commands   | `C-S-p`   | `M-x`     |                      |
| Go to File          | `C-p`     | `M-p`     |                      |
| cursorLeft          | `←`       | `M-h`     |                      |
| cursorDown          | `↓`       | `M-j`     | selectNextSuggestion |
| cursorUp            | `↑`       | `M-k`     | selectPrevSuggestion |
| cursorRight         | `→`       | `M-l`     |                      |
| cursorHome          | `Home`    | `M-g`     |                      |
| cursorEnd           | `End`     | `M-;`     |                      |
| Insert Snippet      |           | `M-i`     |                      |
| Toggle Terminal     | `C-~`     | `M-n`     |                      |
| Trigger Suggest     | `C-space` | `M-'`     | `C-'` is ok          |
| Toggle Line Comment | `C-/`     | `C-;`     |                      |
| Undo                | `C-z`     | `C-/`     |                      |
| Show Explorer       | `C-S-e`   | `C-j C-e` |                      |
| Replace in Files    | `C-S-f`   | `C-j C-f` | `M-s` is ok          |
| Show Source Control | `C-S-g`   | `C-j C-g` |                      |
|                     |           |           |                      |

Of course, there has other keybindings, just to explore and custom them yourselves. Come on 😄.

## Keyboard Shortcuts

Here is a intial keybindings screenshot:

![cve](images/tn.jpg)
