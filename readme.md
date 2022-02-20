# pine-script-mode [![Build Status](https://travis-ci.org/EricCrosson/pine-script-mode.svg?branch=master)](https://travis-ci.org/EricCrosson/pine-script-mode) [![MELPA Stable](https://stable.melpa.org/packages/pine-script-mode-badge.svg)](https://stable.melpa.org/#/pine-script-mode) [![MELPA](https://melpa.org/packages/pine-script-mode-badge.svg)](https://melpa.org/#/pine-script-mode)

> GNU Emacs major-mode for [Trading View](https://tradingview.com) [Pine script](https://www.tradingview.com/study-script-reference/).


`Update: 20.02.2022:` Pine Script Version 5 support will be added soon, ironing out kinks


## Install

From [MELPA](https://melpa.org/)

```lisp
(use-package pine-script-mode
  :ensure t
  :pin melpa-stable
  :mode (("\\.pine" . pine-script-mode)))
```

Or manually, after downloading into your `load-path`

```lisp
(require 'pine-script-mode)
(add-to-list 'auto-mode-alist '("\\.pine$" . pine-script-mode))
```

## Example of Syntax highlighting

Here is a buffer displaying the script
[Volume Footprint [LUX]](https://www.tradingview.com/v/cdU6E9rm/) by [LuxAlgo](https://www.tradingview.com/u/LuxAlgo/).

![Rendered example](https://raw.githubusercontent.com/EricCrosson/pine-script-mode/master/img/luxalgo-demo.png)

The Emacs 28 buffer in this image is also using 

- [Modus Vivendi Theme](https://gitlab.com/protesilaos/modus-themes/)


## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
