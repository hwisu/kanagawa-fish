# Kanagawa for Fish

A dark and light theme for [Fish shell](https://fishshell.com/) inspired by the famous painting "The Great Wave off Kanagawa" by Katsushika Hokusai.

This theme is a port of the [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) colorscheme for Neovim.

## Preview

![Kanagawa Wave (Dark)](https://raw.githubusercontent.com/rebelot/kanagawa.nvim/master/kanagawa@2x.png)

## Theme Variants

| Theme | Description | File |
|-------|-------------|------|
| **Wave** (Dark) | Dark theme with deep blue ocean tones | `kanagawa.theme` |
| **Lotus** (Light) | Light theme with warm, paper-like tones | `kanagawa-light.theme` |

## Installation

### Fisher (Recommended)

```fish
fisher install hwisu/kanagawa-fish
```

### Oh My Fish

```fish
omf install https://github.com/hwisu/kanagawa-fish
```

### Manual Installation

```fish
# Clone the repository
git clone https://github.com/hwisu/kanagawa-fish.git

# Copy themes to Fish config
cp kanagawa-fish/themes/*.theme ~/.config/fish/themes/
```

## Usage

```fish
# List available themes
fish_config theme list

# Apply dark theme (Wave)
fish_config theme choose kanagawa

# Apply light theme (Lotus)
fish_config theme choose kanagawa-light

# Save theme permanently
fish_config theme save
```

## Color Palette

### Wave (Dark)

| Element | Color | Hex |
|---------|-------|-----|
| Normal text | ![#DCD7BA](https://via.placeholder.com/12/DCD7BA/DCD7BA.png) | `#DCD7BA` |
| Commands | ![#7FB4CA](https://via.placeholder.com/12/7FB4CA/7FB4CA.png) | `#7FB4CA` |
| Keywords | ![#957FB8](https://via.placeholder.com/12/957FB8/957FB8.png) | `#957FB8` |
| Strings | ![#98BB6C](https://via.placeholder.com/12/98BB6C/98BB6C.png) | `#98BB6C` |
| Parameters | ![#FFA066](https://via.placeholder.com/12/FFA066/FFA066.png) | `#FFA066` |
| Comments | ![#727169](https://via.placeholder.com/12/727169/727169.png) | `#727169` |
| Errors | ![#C34043](https://via.placeholder.com/12/C34043/C34043.png) | `#C34043` |

### Lotus (Light)

| Element | Color | Hex |
|---------|-------|-----|
| Normal text | ![#545464](https://via.placeholder.com/12/545464/545464.png) | `#545464` |
| Commands | ![#4D699B](https://via.placeholder.com/12/4D699B/4D699B.png) | `#4D699B` |
| Keywords | ![#624C83](https://via.placeholder.com/12/624C83/624C83.png) | `#624C83` |
| Strings | ![#6F894E](https://via.placeholder.com/12/6F894E/6F894E.png) | `#6F894E` |
| Parameters | ![#5D57A3](https://via.placeholder.com/12/5D57A3/5D57A3.png) | `#5D57A3` |
| Comments | ![#8A8980](https://via.placeholder.com/12/8A8980/8A8980.png) | `#8A8980` |
| Errors | ![#E82424](https://via.placeholder.com/12/E82424/E82424.png) | `#E82424` |

## Credits

- Original colorscheme: [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim)
- Inspired by the artwork of Katsushika Hokusai

## License

[MIT](LICENSE)
