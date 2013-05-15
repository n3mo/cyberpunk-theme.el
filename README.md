Cyberpunk Theme
===============

Cyberpunk color theme for the emacs 24+ built-in color theme support known loosely as <code>deftheme</code>. The theme is <i>mostly</i> a direct port of the [overtone/emacs-live](https://github.com/overtone/emacs-live) theme of the same name (designed originally for the <code>color-theme</code> package). Many mode-specific customizations, listed below, have also been added.

Installation
============

Manual
------

Ensure that cyberpunk-theme.el is on the custom-theme-load-path like this: 

```lisp
(add-to-list 'custom-theme-load-path "~/path/to/cyberpunk-theme.el")
```

You can then load the theme at any time by running the command <code>M-x load-theme RET cyberpunk</code>.

Package.el
----------

Cyberpunk is available in [MELPA](http://melpa.milkbox.net/). This installation method assumes that you have added MELPA to your package archive list. This can be accomplished in your init file with the following command:

```lisp
(add-to-list 'package-archives
             '("melpa" . "http://melpa.milkbox.net/packages/") t)
```

Once set up, you can install <code>cyberpunk</code> using the following command:

<pre>
M-x package-install cyberpunk-theme
</pre>

or, by alternatively running the command <code>list-packages</code>, marking the cyberpunk-theme package with the command "i" and running the execute execute command "x".

If you want cyberpunk-theme to be set at startup, add the following line to your .emacs init file:

```lisp
(load-theme 'cyberpunk t)
```

Specific Modes
==============

In addition to basic face settings, cyberpunk-theme has specially-tailored support for the following modes. Please share any suggestions for additional modes. Modes marked with \* are currently defined, but poorly so. If you use one of these modes and have customization suggestions I would greatly appreciate any feedback on how to make a more seamless experience.

* AUCTeX/LaTeX\*
* MuMaMo\*
* autocomplete
* compilation-mode\*
* ediff
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

License
=======

Copyright (C) 2012 Nicholas M. Van Horn

Author: Nicholas M. Van Horn <vanhorn.nm@gmail.com>
Keywords: color theme, cyberpunk

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
