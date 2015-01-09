# Intro

It's perl extension for urxvt which allows to use fifo.

# Installation

Add to `.Xresources`:

```
URxvt.perl-ext-common: [another extensions],fifo
URxvt.keysym.Mod4-C-f: perl:fifo:start
URxvt.fifo.file: /tmp/urxvt.fifo
```

# Usage

```
echo date > /tmp/urxvt.fifo
```

### to be continued
