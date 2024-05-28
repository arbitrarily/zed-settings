# [zed](https://zed.dev) settings

```bash
# Theme - modified
ln -s $(pwd)/themes/zedokai.json ~/.config/zed/themes

# Settings & Keybindings
ln -s $(pwd)/*.json ~/.config/zed
```

I run these commands from the Git `zed-settings` directory.

## Settings

Installs `settings.json` and `keymap.json` to `~/.config/zed`.

There are lists of all available settings `Ctrl` + `Shift` + `P` and typing `default`.

## Theme
![image](https://github.com/arbitrarily/startyparty/assets/899183/47c5c05b-b09e-4e26-b2bd-90cbd739b117)

Installs `zedokai.json` theme to `~/.config/zed/themes`.

[Zedokai](https://github.com/slymax/zedokai/blob/main/themes/zedokai.json)
`Zedokai` with darker backgrounds.

[Theme Schema](https://zed.dev/schema/themes/v0.1.0.json)
