# tmux-config

```
sudo apt-get update
sudo apt-get install tmux

# or if you're macos user
# `brew install tmux`
```

```bash
git clone git@github.com:ruslan-korneev/tmux-config.git ~/.config/tmux
git clone git@github.com:tmux-plugins/tpm.git ~/.config/tmux/plugins/tpm
```

```.tmux.conf
# ~/.tmux.conf
source-file ~/.config/tmux/tmux.conf
```

```bash
tmux new-session -s example
# <C-e>+I - this keybind will install plugins, just wait til something happen
# <C-e>+r - to reload config if you've changed it
```
