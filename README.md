# fcitx-skin-material-nord
fcitx-skin-material with Nord color scheme

## Screenshot


## Usage

### Installation

```sh
git clone https://github.com/evansan/fcitx-skin-material-nord.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord
cp -r material-nord/  ~/.local/share/fcitx5/themes/
```

### Enabling

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as

```dosini
Theme=material-nord

```

Then restart fcitx5 to apply the theme.

```sh
fcitx5 -r
```
