# TEST5000
# Plugins do not install 
## ChatGPT fix:

Move the Config File: Place your config file in `~/.config/tmux/tmux.conf` (create the directory tmux if it doesn't exist).

Create a Symbolic Link: Link this file back to the default location ~/.tmux.conf with:<br>
`ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf`
