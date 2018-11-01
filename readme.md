# clone-indirect-buffer-other-frame [![Build Status](https://travis-ci.org/EricCrosson/clone-indirect-buffer-other-frame.svg?branch=master)](https://travis-ci.org/EricCrosson/clone-indirect-buffer-other-frame) [![MELPA](https://melpa.org/packages/clone-indirect-buffer-other-frame-badge.svg)](https://melpa.org/#/clone-indirect-buffer-other-frame)

> Clone the current buffer and display it in a new frame.

## Install

```lisp
(use-package clone-indirect-buffer-other-frame
  :quelpa (clone-indirect-buffer-other-frame
           :fetcher github
           :repo "ericcrosson/clone-indirect-buffer-other-frame"))
```

Or manually, after downloading into your `load-path`

```lisp
(require 'clone-indirect-buffer-other-frame)
```

## Related

- [Emacs documentation on Indirect Buffers](http://www.gnu.org/software/emacs/manual/html_node/emacs/Indirect-Buffers.html)
- [original StackOverflow post](https://stackoverflow.com/a/47333316)

## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
