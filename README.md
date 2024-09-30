# Tmux Shim Configuration for Zellij

This repository contains a [Zellij][zellij] configuration that makes `zellij` feel a lit more like [`tmux`][tmux]

> ![NOTE]
> If you don't know what either of these tools are, you might want to check out [terminal multiplexers on wikipedia][wiki-terminal-multiplexers]

This repository contains two files:

```
tmux-zellij-shim-config
├── config.kdl
├── layouts
│   └── default.kdl
├── LICENSE
└── README.md
```

- `config.kdl` contains the Zellij configuration
- `layouts/default.kdl` contains the default layout I used to override and force removal of the bottom bar

These files were stored in `$HOME/.config/zellij` for me (i.e. `$HOME/.config/zellij/config.kdl` existed), so they should be copyable to wherever your config is stored.

[zellij]: https://zellij.dev
[wiki-terminal-multiplexers]: https://en.wikipedia.org/wiki/Terminal_multiplexer
[tmux]: https://github.com/tmux/tmux/wiki
