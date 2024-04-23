# Tmux configuration

- [Tmux cheatsheet](https://tmuxcheatsheet.com/)
# Commands

- `tmux source-file ~/.config/tmux/tmux.conf` -> Source changes
- `<leader> I` -> Install plugins

## Sessions
- `tmux new -s <session_name>` -> Create new session with name
- `tmux ls` | `<leader> s` -> List sessions
- `tmux a` -> Attach to last session
- `tmux a -t <session_name>` -> Attach to session

- `tmux kill-ses -t <session_name>` -> Kill session
- `tmux kill-ses -a` -> Kill all sessions but the curren
- `tmux kill-server` -> Kill server

- `<leader> w` -> Session and window preview
- `<leader> (` -> Move to previous session
- `<leader> )` -> Move to next session
- `<leader> $` -> Rename sesion
- `<leader> d` -> Detach from session

## Windows

- `tmux new -s <session_name> -n <window_name>` -> Create new window and session with names

- `<leader> c` -> Create new window
- `<leader> w` -> Session and window preview
- `<leader> ,` -> Rename current window
- `<leader> &` -> Close current window
- `<leader> p` -> Previous window
- `<leader> n` -> Next window
- `<leader> 0....9` -> Switch to window by number
- `<leader> l` -> Toggle last active window

## Panes

- `:join-pane -s <pane_1> -t <pane_2>` -> Join two windows as panes (Merge window 2 to window 1 as panes)

- `<leader> ;` -> Toggle last active pane
- `<leader> q` -> Show pane numbers
- `<leader> %` -> Split pane horizontally
- `<leader> "` -> Split pane vertically
- `<leader> x` -> Close current pane

- `<leader> Spacebar` -> Toggle between pane layouts
- `<leader> q` -> Show pane numbers
- `<leader> q 0...9` -> Switch to pane by number 

- `<leader> z` -> Toggle pane zoom

- `<leader> !` -> Convert pane into a window
