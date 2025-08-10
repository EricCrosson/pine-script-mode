# pine-script-mode [![MELPA Stable](https://stable.melpa.org/packages/pine-script-mode-badge.svg)](https://stable.melpa.org/#/pine-script-mode) [![MELPA](https://melpa.org/packages/pine-script-mode-badge.svg)](https://melpa.org/#/pine-script-mode)

> GNU Emacs major-mode for [Trading View](https://tradingview.com) [Pine Script Docs](https://www.tradingview.com/pine-script-docs/).

**Pine Script Version 6 supported**

## Install

From [MELPA](https://melpa.org/)

```elisp
(use-package pine-script-mode
  :ensure t)
```

Or manually, after downloading into your `load-path`

```elisp
(require 'pine-script-mode)
(add-to-list 'auto-mode-alist '("\\.pine$" . pine-script-mode))
```

## License
GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
