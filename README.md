[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/prt.svg)](https://jcs-emacs.github.io/jcs-elpa/#/prt)

# prt
> Progress Reporter Library (Emacs)

[![CI](https://github.com/jcs-elpa/prt/actions/workflows/test.yml/badge.svg)](https://github.com/jcs-elpa/prt/actions/workflows/test.yml)

## ๐พ Quickstart

```elisp
(prt-with "Start counting... "
  (dotimes (count 100)
    (sit-for 0.1)
    (prt-update rt (format " %s" count)))
  (prt-done rt))
```

## ๐ง Customization

#### ๐งช Variables

* `prt-pulse-characters` - Characters to use for pulsing progress reporters.

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
