# clone-indirect-buffer-other-frame [![Build Status](https://travis-ci.org/EricCrosson/clone-indirect-buffer-other-frame.svg?branch=master)](https://travis-ci.org/EricCrosson/clone-indirect-buffer-other-frame)

> Clone the current buffer and display it in a new frame.

## Install

With [Quelpa](https://framagit.org/steckerhalter/quelpa)

```lisp
(use-package clone-indirect-buffer-other-frame
  :quelpa (clone-indirect-buffer-other-frame
           :fetcher github
           :repo "ericcrosson/clone-indirect-buffer-other-frame")
  :bind ("C-x 5 c" . clone-indirect-buffer-other-frame))
```

> Note: this project is not destined for [melpa](https://melpa.org/#/)

Or manually, after downloading into your `load-path`

```lisp
(require 'clone-indirect-buffer-other-frame)
```

## Related

- [Emacs documentation on Indirect Buffers](http://www.gnu.org/software/emacs/manual/html_node/emacs/Indirect-Buffers.html)
- [original StackOverflow post](https://stackoverflow.com/a/47333316)

## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
