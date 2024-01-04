# Helix Config Files
### These files are stored under $HOME/.config/helix

## To clone
```bash
git clone git@github.com:brianwoo/helix-editor-config.git $HOME/.config/helix
```

## To fix syntax highlighting not working
```bash
hx -g fetch
hx -g build
```

## To show if Helix supports a programming lang
```bash
hx --health go
hx --health python
```

## Cheatsheet
|Function   |Keystrokes   |   |
|-----------|-------------|---|
|Open file in buffer   |[Sp] f   |   |
|Goto Next/Prev buffer |gn / gp   |   |
|Goto Last buffer |ga   |   |
|H/V split new buffer |:hnew / :vnew   |   |
|Jump between splits |C-w up/down/left/right   |   |
|Close Split |[Sp] wq   |   |
|Close buffer |:bc   |   |
|Line copy (yank) |xy   |   |
|Word copy (yank) |wy   |   |
|   |   |   |

## Tutorial
[0 to LSP : Helix RC From Scratch](https://www.youtube.com/watch?v=aiSI6vdZWgE)

[Goimports](https://github.com/helix-editor/helix/discussions/4681)