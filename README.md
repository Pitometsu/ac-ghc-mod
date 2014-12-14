###Ac Ghc Mod
Smart auto-complete sources for haskell mode
***
####Usage

    M-x el-get-install RET ac-ghc-mod

Add next to `init-ac-ghc-mod.el` in your `el-get-user-package-directory`:

```elisp
(add-hook 'haskell-mode-hook 'haskell-ac-ghc-mod-hook)
```
