# Claude Terminal Theme

A warm, earthy terminal color scheme inspired by [Claude's](https://claude.ai) visual identity. Available in **dark** and **light** variants, featuring terracotta orange accents, warm neutrals, and backgrounds designed for long coding sessions.

> **Disclaimer:** This is an unofficial, community-made theme. It is not affiliated with or endorsed by Anthropic.

## Preview

<!-- Add a screenshot of your terminal here -->
<!-- ![Claude Terminal Theme](preview.png) -->

*Screenshots coming soon — contributions welcome!*

## Color Palette

### Dark

| Color | Normal | Bright |
|-------|--------|--------|
| Black | ![#141413](https://singlecolorimage.com/get/141413/12x12) `#141413` | ![#66645f](https://singlecolorimage.com/get/66645f/12x12) `#66645f` |
| Red | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` | ![#e89a7e](https://singlecolorimage.com/get/e89a7e/12x12) `#e89a7e` |
| Green | ![#788c5d](https://singlecolorimage.com/get/788c5d/12x12) `#788c5d` | ![#92a87a](https://singlecolorimage.com/get/92a87a/12x12) `#92a87a` |
| Yellow | ![#c9a96e](https://singlecolorimage.com/get/c9a96e/12x12) `#c9a96e` | ![#d9be8a](https://singlecolorimage.com/get/d9be8a/12x12) `#d9be8a` |
| Blue | ![#6a9bcc](https://singlecolorimage.com/get/6a9bcc/12x12) `#6a9bcc` | ![#85b3d9](https://singlecolorimage.com/get/85b3d9/12x12) `#85b3d9` |
| Magenta | ![#9b7ea4](https://singlecolorimage.com/get/9b7ea4/12x12) `#9b7ea4` | ![#b298b8](https://singlecolorimage.com/get/b298b8/12x12) `#b298b8` |
| Cyan | ![#6aaa96](https://singlecolorimage.com/get/6aaa96/12x12) `#6aaa96` | ![#84bfae](https://singlecolorimage.com/get/84bfae/12x12) `#84bfae` |
| White | ![#e8e6dc](https://singlecolorimage.com/get/e8e6dc/12x12) `#e8e6dc` | ![#faf9f5](https://singlecolorimage.com/get/faf9f5/12x12) `#faf9f5` |

| UI Element | Color |
|------------|-------|
| Background | ![#141413](https://singlecolorimage.com/get/141413/12x12) `#141413` |
| Foreground | ![#e8e6dc](https://singlecolorimage.com/get/e8e6dc/12x12) `#e8e6dc` |
| Cursor | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Selection | ![#383734](https://singlecolorimage.com/get/383734/12x12) `#383734` |

### Light

| Color | Normal | Bright |
|-------|--------|--------|
| Black | ![#141413](https://singlecolorimage.com/get/141413/12x12) `#141413` | ![#b0aea5](https://singlecolorimage.com/get/b0aea5/12x12) `#b0aea5` |
| Red | ![#b8512e](https://singlecolorimage.com/get/b8512e/12x12) `#b8512e` | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Green | ![#5e7245](https://singlecolorimage.com/get/5e7245/12x12) `#5e7245` | ![#788c5d](https://singlecolorimage.com/get/788c5d/12x12) `#788c5d` |
| Yellow | ![#9e7a30](https://singlecolorimage.com/get/9e7a30/12x12) `#9e7a30` | ![#b8944a](https://singlecolorimage.com/get/b8944a/12x12) `#b8944a` |
| Blue | ![#4a7ea8](https://singlecolorimage.com/get/4a7ea8/12x12) `#4a7ea8` | ![#6a9bcc](https://singlecolorimage.com/get/6a9bcc/12x12) `#6a9bcc` |
| Magenta | ![#7a5c84](https://singlecolorimage.com/get/7a5c84/12x12) `#7a5c84` | ![#9b7ea4](https://singlecolorimage.com/get/9b7ea4/12x12) `#9b7ea4` |
| Cyan | ![#4a8a78](https://singlecolorimage.com/get/4a8a78/12x12) `#4a8a78` | ![#6aaa96](https://singlecolorimage.com/get/6aaa96/12x12) `#6aaa96` |
| White | ![#b0aea5](https://singlecolorimage.com/get/b0aea5/12x12) `#b0aea5` | ![#141413](https://singlecolorimage.com/get/141413/12x12) `#141413` |

| UI Element | Color |
|------------|-------|
| Background | ![#faf9f5](https://singlecolorimage.com/get/faf9f5/12x12) `#faf9f5` |
| Foreground | ![#2a2a28](https://singlecolorimage.com/get/2a2a28/12x12) `#2a2a28` |
| Cursor | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Selection | ![#e8e6dc](https://singlecolorimage.com/get/e8e6dc/12x12) `#e8e6dc` |

## Installation

### iTerm2

1. Download [`iterm2/Claude Dark.itermcolors`](iterm2/Claude%20Dark.itermcolors) or [`iterm2/Claude Light.itermcolors`](iterm2/Claude%20Light.itermcolors)
2. Open **iTerm2 > Settings > Profiles > Colors**
3. Click **Color Presets... > Import...**
4. Select the downloaded file
5. Choose **Claude Dark** or **Claude Light** from the presets dropdown

### Ghostty

Copy the theme file to your Ghostty themes directory:

```bash
# Dark
cp ghostty/claude-dark ~/.config/ghostty/themes/claude-dark

# Light
cp ghostty/claude-light ~/.config/ghostty/themes/claude-light
```

Then set in your config (`~/.config/ghostty/config`):

```
theme = claude-dark
# or
theme = claude-light
```

### Alacritty

Copy the theme file to your Alacritty themes directory:

```bash
mkdir -p ~/.config/alacritty/themes

# Dark
cp alacritty/claude-dark.toml ~/.config/alacritty/themes/claude-dark.toml

# Light
cp alacritty/claude-light.toml ~/.config/alacritty/themes/claude-light.toml
```

Then import in your config (`~/.config/alacritty/alacritty.toml`):

```toml
import = ["~/.config/alacritty/themes/claude-dark.toml"]
# or
import = ["~/.config/alacritty/themes/claude-light.toml"]
```

### Kitty

Copy the theme file to your Kitty themes directory:

```bash
# Dark
cp kitty/claude-dark.conf ~/.config/kitty/themes/claude-dark.conf

# Light
cp kitty/claude-light.conf ~/.config/kitty/themes/claude-light.conf
```

Then include in your config (`~/.config/kitty/kitty.conf`):

```
include themes/claude-dark.conf
# or
include themes/claude-light.conf
```

### WezTerm

Copy the theme file to your WezTerm colors directory:

```bash
mkdir -p ~/.config/wezterm/colors

# Dark
cp wezterm/claude-dark.toml ~/.config/wezterm/colors/claude-dark.toml

# Light
cp wezterm/claude-light.toml ~/.config/wezterm/colors/claude-light.toml
```

Then set in your config (`~/.wezterm.lua`):

```lua
config.color_scheme = "Claude Dark"
-- or
config.color_scheme = "Claude Light"
```

### Windows Terminal

1. Open **Settings** (Ctrl+,)
2. Click **Open JSON file** in the bottom-left corner
3. Find the `"schemes"` array and add the contents of [`windows-terminal/claude-dark.json`](windows-terminal/claude-dark.json) or [`windows-terminal/claude-light.json`](windows-terminal/claude-light.json)
4. Set `"colorScheme": "Claude Dark"` or `"colorScheme": "Claude Light"` in your profile

## Font Recommendation

This theme pairs well with monospaced fonts that have warm, rounded character. Some suggestions:

- **SF Mono** (macOS — available in Terminal.app and Font Book)
- **Berkeley Mono**
- **JetBrains Mono**
- **Iosevka**

## Contributing

Contributions are welcome! If you'd like to port this theme to another terminal or improve an existing port:

1. Fork this repo
2. Add your theme file in a new directory named after the terminal
3. Update this README with installation instructions
4. Open a pull request

## License

[MIT](LICENSE)
