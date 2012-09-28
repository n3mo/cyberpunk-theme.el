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

This theme is a port of the overtone/emacs-live theme of the same name (https://github.com/overtone/emacs-live). The original theme was designed for use with the color-theme package. This theme adopts the new built-in theme support <code>deftheme</code>. Additionally, this theme strives to offer as many mode-specific customizations as possible, with further tweaks that suit my fancy.
