cyberpunk-theme.el
==================

Cyberpunk theme for emacs built-in color theme support known loosely as <code>deftheme</code>. 

Usage
=====

Ensure that cyberpunk-theme.el is on the custom-theme-load-path like this: 

<pre>
(add-to-list 'custom-theme-load-path "~/path/to/cyberpunk-theme.el")
</pre>

You can then load the theme at any time by running the command <code>M-x load-theme</code> and entering cyberpunk when prompted for "load custom theme: "

If you want cyberpunk-theme to be set at startup, add the following line to your .emacs init file:

<pre>
(load-theme 'cyberpunk t)
</pre>

Acknowledgments 
===============

This theme was originally made available on the overtone/emacs-live github page (https://github.com/overtone/emacs-live) for use with the color-theme package. It was then ported to native theme support for emacs built-in color theme package known loosely as "deftheme" by ??? (original author has been lost to me... email me if you're the one deserving of credit!)

The initial cyberpunk-theme lacked many mode-specific faces. This file strives to be as mode-specific as possible, with further tweaks that suit my fancy.
