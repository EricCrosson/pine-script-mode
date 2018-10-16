# pine-script-mode [![Build Status](https://travis-ci.org/EricCrosson/pine-script-mode.svg?branch=master)](https://travis-ci.org/EricCrosson/pine-script-mode)

> GNU Emacs major-mode for [Trading View](https://tradingview.com) Pine script

## Install

With `use-package`

```lisp
  (use-package pine-script-mode
      :quelpa
        (pine-script-mode :fetcher github
                       :repo "ericcrosson/pine-script-mode")
    :mode (("\\.pine" . pine-script-mode)))
```

Or manually

```lisp
(require 'pine-script-mode)
(add-to-list 'auto-mode-alist '("\\.pine$" . pine-script-mode))
```

## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
