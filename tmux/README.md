# Tmux

Install plugins

```
prefix + I
```

tmux-sidebar

```
prefix + TAB
prefix + BACKSPACE (focus)
```

tmux-copycat

```
prefix + /
n - next match
N - prev match
```

tmux-urlview

Dependencies

```bash
brew install reattach-to-user-namespace
```

```bash
brew install urlview
```

```
prefix + u
```

tmux-open

in visual mode selection highlight filename and press `o`

tmux-fpp (facebook pathpicker)

```
prefix + f
```

tmux-yank

```
prefix + y (copy command line)

selection then y (copy selection)
```

Unbind all keys

```bash
:unbind-key -a
```

Reload tmux conf

```
$ tmux source-file ~/.tmux.conf
```

Send commands to inner window (ie when SSHing)

```
C-b b <keys>
```

# License

MIT