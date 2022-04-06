# fcitx-skin-material-nord
fcitx-skin-material with Nord color scheme

## Screenshot
![Screenshot](./sample.png)


## 使用方法

### 安装

```sh
git clone https://github.com/evansan/fcitx-skin-material-nord.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord
cp -r material-nord/  ~/.local/share/fcitx5/themes/
```

### 配置

在 `~/.config/fcitx5/conf/classicui.conf` 修改 `Theme` 为以下

```dosini
Theme=material-nord

```

最后重启生效

```sh
fcitx5 -r
```

## Usage

### Installation

```sh
git clone https://github.com/evansan/fcitx-skin-material-nord.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord
cp -r material-nord/  ~/.local/share/fcitx5/themes/
```

### Configuration

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as follow

```dosini
Theme=material-nord

```

Then restart fcitx5 to apply the theme

```sh
fcitx5 -r
```


Inspired by [fcitx-skin-material](https://github.com/hrko/fcitx-skin-material)
