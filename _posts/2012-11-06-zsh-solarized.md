---
layout: post
title: "oh-my-zsh, powerline, solarized"
description: ""
category: 
tags: []
---
{% include JB/setup %}
I just 'wasted' a few hours changing my shell from ```bash``` to ```zsh```. I
like the ```agnoster``` ```oh-my-zsh``` theme with ```solarized``` colors.
As ```agnoster``` needs a powerline patched font I figured I might
as well use ```vim-powerline```. The stuff is available here:

- [solarized](http://ethanschoonover.com/solarized)
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [powerline patched fonts](https://gist.github.com/1595572)
- [vim-powerline](https://github.com/Lokaltog/vim-powerline)

To use the ```Menlo``` font with ```urxvt``` one can put the following into
```.Xresources```:


    URxvt*font:                 xft:Menlo for Powerline:regular:size=12
    URxvt*imFont:               xft:Menlo for Powerline:regular:size=12
    URxvt*boldFont:             xft:Menlo for Powerline:bold:size=12
    URxvt*italicFont:           xft:Menlo for Powerline:italic:size=12
    URxvt*boldItalicFont:       xft:Menlo for Powerline:bold:italic:size=12

The ```fontpatcher``` utility in ```vim-powerline``` allows you to patch your own fonts for powerline. I'd like to use the
[dina](http://www.donationcoder.com/Software/Jibz/Dina/) font but for some
reason I can't get it to work with ```urxvt``` after patching it for Powerline :-/ Still looks pretty neat with Menlo:

[![Where is the image?][1]]
[1]: {{ BASE_PATH }}/images/zsh_powerline.png

