# monte-mode for emacs

[Monte][] is a nascent dynamic programming language reminiscent of Python
and E, designed to support secure distributed computing using a
capability-based object model.

For developing monte in emacs, we provide:

  - monte indentation
  - a monte flycheck checker based on a monte lint service

## Getting Started

  1. [Install monte][1]
  2. `cd devbot; monte eval repl-server.mt`
  3. In emacs, Use M-x load-file to load `elisp/monte-indent.el` and then `elisp/monte.el`

[1]: http://monte.readthedocs.io/en/latest/intro.html#installation

[Monte]: http://www.monte-language.org/
