# Keyboard cheatsheet

Type `keys` to open this file. Press `q` to close it, `/` to search.

## herdr (panes, tabs, agents)

Start: `herdr`. Press `ctrl+b`, release, then press the key.
If you forget a key: `ctrl+b` then `?` shows all keys.

### Panes
| Key                   | Action                              |
|-----------------------|-------------------------------------|
| `ctrl+b` `h/j/k/l`    | Go to pane left / down / up / right |
| `ctrl+b` `%`          | Split, new pane on the right        |
| `ctrl+b` `"`          | Split, new pane below               |
| `ctrl+b` `z`          | Zoom pane (full screen), again = back |
| `ctrl+b` `x`          | Close pane                          |
| `ctrl+b` `H/J/K/L`    | Move (swap) pane left/down/up/right |
| `ctrl+b` `r`          | Resize mode (h/j/k/l, Esc to stop)  |

### Tabs
| Key                   | Action                    |
|-----------------------|---------------------------|
| `ctrl+b` `c`          | New tab                   |
| `ctrl+b` `n` / `p`    | Next / previous tab       |
| `ctrl+b` `1`..`9`     | Go to tab 1..9            |
| `ctrl+b` `T`          | Rename tab                |
| `ctrl+b` `&`          | Close tab                 |

### Workspaces and agents
| Key                   | Action                                  |
|-----------------------|-----------------------------------------|
| `ctrl+b` `g`          | Go to: search workspaces, tabs, agents  |
| `ctrl+b` `w`          | Workspace navigation (Esc to leave)     |
| `ctrl+b` `N`          | New workspace                           |
| `ctrl+b` `W`          | Rename workspace                        |
| `ctrl+b` `D`          | Close workspace                         |
| `ctrl+b` `b`          | Show / hide sidebar (agents panel)      |
| `ctrl+b` `q`          | Detach. All keeps running. `herdr` = back |

### Copy text
| Key                   | Action                          |
|-----------------------|---------------------------------|
| `ctrl+b` `y`          | Copy mode                       |
| `v` or `space`        | Start selection                 |
| `y` or `enter`        | Copy                            |
| `q` or `esc`          | Cancel                          |

## WezTerm (the window)
| Key                   | Action                    |
|-----------------------|---------------------------|
| `cmd+t` / `cmd+w`     | New tab / close tab       |
| `cmd+1`..`9`          | Go to tab 1..9            |
| `cmd+shift+[` / `]`   | Previous / next tab       |
| `cmd+n`               | New window                |
| `cmd+f`               | Search the output         |
| `cmd+=` / `cmd+-` / `cmd+0` | Text bigger / smaller / reset |

Tip: use herdr for panes and tabs, not WezTerm. herdr keeps them when you close the window.

## Shell (zsh)
| Key / command         | Action                              |
|-----------------------|-------------------------------------|
| `ctrl+f`              | Accept the grey suggestion          |
| `ctrl+r`              | Search old commands                 |
| `ctrl+a` / `ctrl+e`   | Go to start / end of line           |
| `ctrl+w`              | Delete the word before the cursor   |
| `ctrl+u`              | Delete the full line                |
| `ctrl+l`              | Clear the screen                    |
| `ctrl+c`              | Stop the running command            |
| `tab`                 | Complete a command or path          |
| `..`                  | Go up one folder                    |
| `add` / `push` / `pull` | git add . / git push / git pull   |
| `m`                   | git switch main                     |
| `lazygit`             | Git in the terminal                 |
| `cc`                  | Claude, no permission prompts (careful) |
| `co`                  | Codex, full auto (careful)          |

## Neovim (`nvim`)
Leader key = `space`.
| Key                   | Action                          |
|-----------------------|---------------------------------|
| `space` `f`           | Find file                       |
| `space` `s`           | Search text in project          |
| `space` `b`           | Open files (buffers)            |
| `space` `e`           | File browser                    |
| `space` `g`           | Git                             |
| `esc`                 | Save                            |
| `ctrl+a`              | Select all                      |
| `ctrl+w` `h/j/k/l`    | Go to split left/down/up/right  |
| `i` / `esc`           | Start typing / stop typing      |
| `:q`                  | Quit                            |

## macOS
| Key                   | Action                    |
|-----------------------|---------------------------|
| `cmd+space`           | Open an app (Spotlight)   |
| `cmd+tab`             | Switch app                |
| `cmd+backtick`        | Switch window in same app |
| `cmd+q`               | Quit app                  |
