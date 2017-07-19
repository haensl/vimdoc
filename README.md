# VIMDOC

A collection of vim commands & tricks.

### Revert document to an earlier/later version
```bash
:earlier 15m
:later 15m
```

### Dump output of command into current buffer
```bash
:.! ls
```

### To upper-/lowercase
```bash
viwu
viwU
```

### View changelist
```bash
:changes
```

### Move through changelist
```bash
g;
g,
```

### Hex mode
```bash
:%!xxd
:%!xxd -r # back to normal mode
```

### Reselect last visual selection
```bash
gv
```

### Create HTML rendering of current buffer
```bash
:%TOhtml
```

### Open file that's currently under the cursor
```bash
gf
gF # recognises [file name]:[line number]
```

### Go to last/next position
```bash
ctrl+o # last
ctrl+i # next
```

### Autocomplete file name
```bash
ctrl+x ctrl+f
```

### Autocomplete line
```bash
ctrl+x ctrl+l
```

### Go to shell
```bash
ctrl+z
fg # go back to vim
```

### Autoindent block
```bash
=% # place cursor on brace and indent until closing brace
```

### Paste word under line in command
```bash
# with cursor over word
ctrl+r ctrl+w
```

### Join lines
```bash
J
```
