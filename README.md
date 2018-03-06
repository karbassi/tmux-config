# tmux config file

## Quick install

```sh
git clone --recurse-submodules https://github.com/karbassi/tmux-config.git ~/.config/tmux/
```

If need be, you may need to symlink the config folder.

```sh
ln -s ~/.config/tmux/ ~/.tmux
```

## Features
- Automatically renumber windows in numerical order
- Faster Command Sequences (in milliseconds)
- Highlight status bar on activity
- Set scroll history to 1000
- Support for 256 colors
- Start with window 1 (instead of 0)
- Start with pane 1
- Don't rename windows automatically
- Mouse control (clickable windows, panes, resizable panes)
- Use Ctrl + Shift + Left/Right to move current window to the left or right.
- Use Alt-arrow keys without prefix key to switch panes.
- Present a menu of URLs to open from the visible pane. sweet.
- New window with default path set to last path
- Rather than constraining window size to the maximum size of any client 
  connected to the *session*, constrain window size to the maximum size 
  of any client connected to *that window*. Much more reasonable.
- Solarized Theme
- OS X Config
- Plugins
    - [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect)