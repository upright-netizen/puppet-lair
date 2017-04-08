# Puppet Lair
> a dotfiles repo for puppets

[Puppet Lair](https://www.instagram.com/p/BSkRAMjFCtP) is an attempt to consolidate some defaults for terminal and dotfile configuration into a very slim lightweight utility for managing a personalized setup. It's going to start out as a proof of concept. Here are the things I care about:

## ZSH
+ prompt configuration
+ tab completions
+ auto completion / auto suggestions
+ plugin structure

## Vim
+ vimrc
+ pathogen (others might use vundle)
+ plugins
+ plugin config
+ keymaps

## Terminal
+ functions
+ aliases
+ colors
+ path

## Config
+ screen
+ slate
+ git
+ editorconfig
+ linting

## Homebrew
+ Brewfile (to install)
+ Cask?

## Atom
+ config
+ packages

## Mac OS X settings
+ key preferences (see below)

When you set keyboard shortcuts for an app, it add it to a file in `~/Library/Preferences'
```
> defaults read co.zeit.hyper
{
    NSFullScreenMenuItemEverywhere = 0;
    NSTreatUnknownArgumentsAsOpen = NO;
    NSUserKeyEquivalents =     {
        "Select Next Pane" = "@]";
        "Select Previous Pane" = "@[";
    };
}
```
