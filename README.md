# My st with patches
=====

git@github.com:giao/st_from_suckless.git

## st.info

in section :

```
# tmux extensions, see TERMINFO EXTENSIONS in tmux(1)
  Se,
  Ss,
  Tc,
  Ms=\E]52;%p1%s;%p2%s\007,
```
Set Se to:
- '\033[4 q'  // underline
- '\e[5 q'  // Vertical bar
- '\e[2 q' // Block

