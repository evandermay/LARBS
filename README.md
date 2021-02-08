# My fork of Luke's Auto-Rice Bootstraping Scripts (LARBS)


## Installation:

On an Arch based distribution as root, run the following:

```
git clone https://github.com/evandermay/LARBS
cd larbs
sh larbs.sh
```

That's it.

## What is LARBS?

LARBS is a script that autoinstalls and autoconfigures a fully-functioning
and minimal terminal-and-vim-based Arch Linux environment.

LARBS can be run on a fresh install of Arch or Artix Linux, and provides you
with a fully configured diving-board for work or more customization.

## Some notes and interesting things:

I have a line to install the starship prompt, but that takes you out of the installer for just a second so that needs to be fixed 

I like to run these Firefox plugins: Firenvim, Ublock Origin, and HTTPS Everywhere. I'm looking into ways to autoinstall these but I haven't picked one yet. 

I don't use a display manager, so I need to find a way to run prime-switch after I logout as root. 

I need to create a keybinding pdf that can be pulled up for anyone that needs it. 

Caps Lock is mapped to backspace, which is mapped to esc, and esc is mapped to caps lock. I just like this a lot better, and it just feels more comfortable once you get used to it. - These can be edited in .Xmodmap once instaled. 
