## Tmux Tutorial
A short introduction to Tmux, for future developments.

Tmux is a terminal multiplexer displaying multiple windows in a single session,
making it easier for tasks that operate in multiple windows.

All commands start with `Ctrl + b`.

## Start
- Run `tmux`
- Use `Ctrl + b` then `?` for appropriate commands.
## Creating named Tmux Session
- `tmux new -s session_name`
## Detaching
- `Ctrl + b` `d` (programming in Tmux will still be running, i.e, persistent)
## Reattaching session
- `tmux ls`
- `tmux attach-session -t <session_name>`
## Some popular commands
- `Ctrl + b` `c`: Create new window
- `Ctrl + b` `w`: Choose a window from a list
- `Ctrl + b` `0`: Switch to window numbered 0
- `Ctrl + b` `,`: Rename the current window
- `Ctrl + b` `%`: Split the current pane horizontally into 2 panes
- `Ctrl + b` `"`: Split the current pane vertically into 2 panes
- `Ctrl + b` `o`: Switch to the next pane
- `Ctrl + b` `;`: Toggle between previous/current pane
- `Ctrl + b` `x`: Close the current pane
