# dotfiles

## to install
` git clone https://github.com/andyedison/dotfiles.git ~/dotfiles `


## tmuxp
started using tmuxp to generate sessions given yaml files. [tmuxp repo here](https://github.com/tmux-python/tmuxp)

example bash setup, assuming you have a config.yaml, docker.yaml, and dba.yaml defined in your ~/.tmuxp directory
```bash
# tmux setup
tmux has-session -t dba 1> /dev/null 2>&1
if [ $? -eq 1 ]; then
        # last one listed is attached
        tmuxp load config docker dba
fi
```
