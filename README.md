[![GNU ELPA][gnu-elpa-image]][gnu-elpa]
[![MELPA][melpa-image]][melpa]

Introduction
============

Emacs Lisp Module to add [ipdb](https://pypi.org/project/ipdb/) support to [realgud](https://github.com/realgud/realgud).


Installation
=============

From ELPA or MELPA
------------------

Inside GNU Emacs evaluate:

```lisp
  (package-install realgud-ipdb)
```


From github source
-------------------

* Have `realgud` and `test-simple` installed.
* Edit this README.md file. (Or rather just make sure that you are in the _directory_ where this file is located).
* From inside GNU Emacs, evaluate:
```lisp
  (compile (format "EMACSLOADPATH=:%s:%s ./autogen.sh" (file-name-directory (locate-library "test-simple.elc")) (file-name-directory (locate-library "realgud.elc"))))
```

[gnu-elpa-image]: https://elpa.gnu.org/packages/realgud-ipdb.svg
[gnu-elpa]: https://elpa.gnu.org/packages/realgud-ipdb.html
[melpa-image]: http://melpa.org/packages/realgud-ipdb-badge.svg
[melpa]: http://melpa.org/#/realgud-ipdb
