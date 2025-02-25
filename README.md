# qutebrowser Solarized

## Install

1. Save `solarized-light.py` and/or `solarized-dark.py` in `~/.config/qutebrowser/`
2. Add the one you want to apply to your `config.py` with:

```shell
echo 'config.source("solarized-light.py")' >> ~/.config/qutebrowser/config.py
```

or

```shell
echo 'config.source("solarized-dark.py")' >> ~/.config/qutebrowser/config.py
```

3. If you have an open instance of qutebrowser, run `:config-source` to reload the config

## Credits

- https://ethanschoonover.com/solarized/
- https://bitbucket.org/kartikynwa/dotty2hotty/src/1a9ba9b80f07e1f63b740da5e6970dc5a97f1037/qutebrowser.py
