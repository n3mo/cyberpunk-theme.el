Cyberpunk Theme
===============

Cyberpunk color theme for the emacs 24+ built-in color theme support known loosely as <code>deftheme</code>. The theme is <i>mostly</i> a direct port of the [overtone/emacs-live](https://github.com/overtone/emacs-live) theme of the same name (designed originally for the <code>color-theme</code> package). Many mode-specific customizations, listed below, have also been added.

Installation
============

Ensure that cyberpunk-theme.el is on the custom-theme-load-path like this: 

```lisp
(add-to-list 'custom-theme-load-path "~/path/to/cyberpunk-theme.el")
```

You can then load the theme at any time by running the command <code>M-x load-theme</code> and entering cyberpunk when prompted for "load custom theme: "

If you want cyberpunk-theme to be set at startup, add the following line to your .emacs init file:

```lisp
(load-theme 'cyberpunk t)
```

Specific Modes
==============

In addition to basic face settings, cyberpunk-theme has specially-tailored support for the following modes. Please share any suggestions for additional modes. Modes marked with \* are currently defined, but poorly so. If you use one of these modes and have customization suggestions I would greatly appreciate any feedback on how to make a more seamless experience.

* AUCTeX/LaTeX
* MuMaMo\*
* autocomplete
* compilation-mode\*
* erc
* eshell
* flymake\*
* flyspell
* full-ack\*
* gnus
* grep
* helm\*
* hl-line-mode
* ido
* isearch
* jabber\*
* js2\*
* magit
* message-mode
* mew\*
* mic-paren\*
* newsticker\*
* org-mode
* outline
* rainbow-delimiters
* wanderlust\*
* whitespace-mode\*
 
Acknowledgments 
===============

This theme is a port of the [overtone/emacs-live](https://github.com/overtone/emacs-live) theme of the same name. The original theme was designed for use with the color-theme package. 

Bugs & Improvements
===================

Please report any problems that you find, along with any suggestions or contributions to the theme. 
