# flymake-bridge

A lsp-bridge Flymake backend for server diagnostics.

## usage

Enable it by calling `flymake-bridge-setup' from a file-visiting buffer. Or to add it to hooks such as:

``` elisp
(require 'flymake-bridge)
(add-hook 'lsp-bridge-mode-hook #'flymake-bridge-setup)
```
