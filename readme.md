# Cobalt3 for iTerm2 and ZSH

Two things for lovers of the [Sublime Text Theme](https://github.com/wesbos/cobalt3). Cobalt3 in your terminal!

![](https://i.imgur.com/TSC8ewE.png)

`cobalt3.itermcolors` is for anyone who uses iTerm2 and wants the colours. The `cobalt3.zsh-theme` is the prompt layout for zsh users. 

They work well together! You will need to install the patched powerline font as well: <https://github.com/powerline/fonts>

####Step-by-step installation
1. Drop the `cobalt3.zsh-theme` file in to the `~/.oh-my-zsh/themes/` directory.
2. Open up your ZSH preferences at `~/.zshrc` and change the theme variable to `ZSH_THEME="cobalt3"`.
3. In iTerm2 access the *Preferences* pane on the *Profiles* tab.
4. Under the *Colors* tab import the `cobalt3.itermcolors` file via the *Load Presets* drop-down.
5. Under the *Text* tab change the font for each type (*Regular* and *Non-ASCII*) to '**Inconsolata for Powerline**'. (Refer to the [powerline-fonts repo](https://github.com/powerline/fonts) for help on font installation.)
6. Refresh ZSH by typing `source ~/.zshrc` on the command line.

---

###Fork of Cobalt2-iTerm
This theme is a fork of [Cobalt2 iTerm theme](https://github.com/wesbos/Cobalt2-iterm) by Wes Bos @wesbos. Thank you Wes and all other contributors for all your efforts. I've forked it to add my own flavor to it. Mostly colors, yes it is purple, because purple can be genius.

