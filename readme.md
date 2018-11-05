# pine-script-mode [![Build Status](https://travis-ci.org/EricCrosson/pine-script-mode.svg?branch=master)](https://travis-ci.org/EricCrosson/pine-script-mode)

> GNU Emacs major-mode for [Trading View](https://tradingview.com) [Pine script](https://www.tradingview.com/study-script-reference/).

## Install

With `use-package`

```lisp
(use-package pine-script-mode
  :ensure t
  :mode (("\\.pine" . pine-script-mode)))
```

Or manually, after downloading into your `load-path`

```lisp
(require 'pine-script-mode)
(add-to-list 'auto-mode-alist '("\\.pine$" . pine-script-mode))
```

## Example

Here is a buffer displaying the script
[CM\_Pivot\_Points\_Custom](https://www.tradingview.com/script/8J7SSNmo-CM-Pivot-Points-Custom/).

![Rendered example](https://raw.githubusercontent.com/EricCrosson/pine-script-mode/add-demo-to-readme/img/demo.png)

The buffer in this image is also using

- [nord-theme](https://emacsthemes.com/themes/nord-theme.html)
- [rainbow-mode](https://elpa.gnu.org/packages/rainbow-mode.html)

## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
