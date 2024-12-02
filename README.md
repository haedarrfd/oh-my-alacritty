# Oh My Alacritty

> [!WARNING]
> This repository will not receive any further updates, as my **dotfiles** is already set up for general use. For future improvements, please feel free to see my **dotfiles** repo [here](https://github.com/haedarrfd/dotfiles.git).

## Introduction

oh-my-alacritty is my custom configuration setup for [Alacritty](https://alacritty.org/index.html) terminal emulator. Alacritty is my preferred terminal emulator for daily use. It offers a modern and minimalist terminal emulator known for its simplicity. Alacritty is written in **Rust**, it delivers blazing-fast performance and seamless cross-platform support.

## ⚡️ Requirements

- A compatible shell: **bash**, **zsh**, **fish**, **powershell**, or any other shell.
- A Nerd Font installed.

## 📦 Installation

**1. Install Alacritty**

Please refer to the official documentation for installation instructions. See [documentation](https://alacritty.org/index.html#Installation)

**2. Install Alacritty-theme**

Clone the [alacritty/theme](https://github.com/alacritty/alacritty-theme) repository:

```shell
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
```

**3. Add alacritty configuration file**

Alacritty is configured using a TOML file format. My Alacritty configuration file stores in `~/.config/alacritty/alacritty.toml`, please refer to the official documentation for another locations. Clone this configuration setup repository:

```shell
# Adjust according to your preferred storage location.
git clone https://github.com/haedarrfd/oh-my-alacritty ~/.config/alacritty
```

## 🎨 Themes

Browse the themes in the cloned alacritty-themes repository, replace `{theme}` in your `alacritty.toml` with your preferred colorscheme:

```toml
[general]
import = [
    "~/.config/alacritty/themes/themes/{theme}.toml"
]
```
