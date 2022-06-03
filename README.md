# Tmux configuration

Sort of opinionated. Works greate with <https://github.com/jmbuhr/quarto-nvim-kickstarter>.
To use, put the file `.tmux.config` into your home folder.
Either manually or with (if you don't already have a tmux config):

```bash
cd ~
wget https://raw.githubusercontent.com/jmbuhr/tmux-kickstarter/main/.tmux.conf
```

Then:

- install tpm: `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
- open tmux
- press prefix + I (capital i, as in Install) to fetch the plugins
- restart tmux
- prefix + U updates plugins

The default prefix is `ctrl-b`, with this configuration it will be `ctrl-space`.

