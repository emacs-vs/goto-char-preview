[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![MELPA](https://melpa.org/packages/goto-char-preview-badge.svg)](https://melpa.org/#/goto-char-preview)
[![MELPA Stable](https://stable.melpa.org/packages/goto-char-preview-badge.svg)](https://stable.melpa.org/#/goto-char-preview)

# goto-char-preview
> Preview character when executing `goto-char` command.

[![CI](https://github.com/emacs-vs/goto-char-preview/actions/workflows/test.yml/badge.svg)](https://github.com/emacs-vs/goto-char-preview/actions/workflows/test.yml)

<p align="center">
  <img src="./etc/goto-char-preview-demo.gif" width="450" height="513"/>
</p>

Normally `goto-char` will just ask for input of the character position then once 
you hit `RET`; it will just go to that character position. This package makes this
better by navigating the character position while you are inputting in minibuffer.

## 🔧 Usage

Call it from `minibuffer` directly,
```
M-x goto-char-preview
```
Or you can bind it globally to replace `goto-char`:
```el
(global-set-key [remap goto-char] 'goto-char-preview)
```

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
