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
| Black | ![#201d18](https://singlecolorimage.com/get/201d18/12x12) `#201d18` | ![#605d56](https://singlecolorimage.com/get/605d56/12x12) `#605d56` |
| Red | ![#c4564a](https://singlecolorimage.com/get/c4564a/12x12) `#c4564a` | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Green | ![#788c5d](https://singlecolorimage.com/get/788c5d/12x12) `#788c5d` | ![#96ad75](https://singlecolorimage.com/get/96ad75/12x12) `#96ad75` |
| Yellow | ![#c1944a](https://singlecolorimage.com/get/c1944a/12x12) `#c1944a` | ![#d4ad5e](https://singlecolorimage.com/get/d4ad5e/12x12) `#d4ad5e` |
| Blue | ![#6a9bcc](https://singlecolorimage.com/get/6a9bcc/12x12) `#6a9bcc` | ![#89b5de](https://singlecolorimage.com/get/89b5de/12x12) `#89b5de` |
| Magenta | ![#a87098](https://singlecolorimage.com/get/a87098/12x12) `#a87098` | ![#c08ab4](https://singlecolorimage.com/get/c08ab4/12x12) `#c08ab4` |
| Cyan | ![#5da3a0](https://singlecolorimage.com/get/5da3a0/12x12) `#5da3a0` | ![#7bbfbc](https://singlecolorimage.com/get/7bbfbc/12x12) `#7bbfbc` |
| White | ![#b0aea5](https://singlecolorimage.com/get/b0aea5/12x12) `#b0aea5` | ![#f4f3ee](https://singlecolorimage.com/get/f4f3ee/12x12) `#f4f3ee` |

| UI Element | Color |
|------------|-------|
| Background | ![#1a1815](https://singlecolorimage.com/get/1a1815/12x12) `#1a1815` |
| Foreground | ![#e8e6e3](https://singlecolorimage.com/get/e8e6e3/12x12) `#e8e6e3` |
| Cursor | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Selection | ![#3e3328](https://singlecolorimage.com/get/3e3328/12x12) `#3e3328` |

### Light

| Color | Normal | Bright |
|-------|--------|--------|
| Black | ![#1f1e1d](https://singlecolorimage.com/get/1f1e1d/12x12) `#1f1e1d` | ![#8a877f](https://singlecolorimage.com/get/8a877f/12x12) `#8a877f` |
| Red | ![#b5443a](https://singlecolorimage.com/get/b5443a/12x12) `#b5443a` | ![#c4564a](https://singlecolorimage.com/get/c4564a/12x12) `#c4564a` |
| Green | ![#5e7340](https://singlecolorimage.com/get/5e7340/12x12) `#5e7340` | ![#788c5d](https://singlecolorimage.com/get/788c5d/12x12) `#788c5d` |
| Yellow | ![#a07830](https://singlecolorimage.com/get/a07830/12x12) `#a07830` | ![#c1944a](https://singlecolorimage.com/get/c1944a/12x12) `#c1944a` |
| Blue | ![#4a7faf](https://singlecolorimage.com/get/4a7faf/12x12) `#4a7faf` | ![#6a9bcc](https://singlecolorimage.com/get/6a9bcc/12x12) `#6a9bcc` |
| Magenta | ![#8e567e](https://singlecolorimage.com/get/8e567e/12x12) `#8e567e` | ![#a87098](https://singlecolorimage.com/get/a87098/12x12) `#a87098` |
| Cyan | ![#438885](https://singlecolorimage.com/get/438885/12x12) `#438885` | ![#5da3a0](https://singlecolorimage.com/get/5da3a0/12x12) `#5da3a0` |
| White | ![#b0aea5](https://singlecolorimage.com/get/b0aea5/12x12) `#b0aea5` | ![#f4f3ee](https://singlecolorimage.com/get/f4f3ee/12x12) `#f4f3ee` |

| UI Element | Color |
|------------|-------|
| Background | ![#faf9f5](https://singlecolorimage.com/get/faf9f5/12x12) `#faf9f5` |
| Foreground | ![#1f1e1d](https://singlecolorimage.com/get/1f1e1d/12x12) `#1f1e1d` |
| Cursor | ![#d97757](https://singlecolorimage.com/get/d97757/12x12) `#d97757` |
| Selection | ![#d9d5cc](https://singlecolorimage.com/get/d9d5cc/12x12) `#d9d5cc` |

## Installation

### iTerm2

1. Download [`iterm2/Claude.itermcolors`](iterm2/Claude.itermcolors) (dark) or [`iterm2/Claude Light.itermcolors`](iterm2/Claude%20Light.itermcolors) (light)
2. Open **iTerm2 > Settings > Profiles > Colors**
3. Click **Color Presets... > Import...**
4. Select the downloaded file
5. Choose **Claude** or **Claude Light** from the presets dropdown

### Ghostty

Copy the theme file to your Ghostty themes directory:

```bash
# Dark
cp ghostty/claude ~/.config/ghostty/themes/claude

# Light
cp ghostty/claude-light ~/.config/ghostty/themes/claude-light
```

Then set in your config (`~/.config/ghostty/config`):

```
theme = claude
# or
theme = claude-light
```

### Alacritty

Copy the theme file to your Alacritty themes directory:

```bash
mkdir -p ~/.config/alacritty/themes

# Dark
cp alacritty/claude.toml ~/.config/alacritty/themes/claude.toml

# Light
cp alacritty/claude-light.toml ~/.config/alacritty/themes/claude-light.toml
```

Then import in your config (`~/.config/alacritty/alacritty.toml`):

```toml
import = ["~/.config/alacritty/themes/claude.toml"]
# or
import = ["~/.config/alacritty/themes/claude-light.toml"]
```

### Kitty

Copy the theme file to your Kitty themes directory:

```bash
# Dark
cp kitty/claude.conf ~/.config/kitty/themes/claude.conf

# Light
cp kitty/claude-light.conf ~/.config/kitty/themes/claude-light.conf
```

Then include in your config (`~/.config/kitty/kitty.conf`):

```
include themes/claude.conf
# or
include themes/claude-light.conf
```

### WezTerm

Copy the theme file to your WezTerm colors directory:

```bash
mkdir -p ~/.config/wezterm/colors

# Dark
cp wezterm/claude.toml ~/.config/wezterm/colors/claude.toml

# Light
cp wezterm/claude-light.toml ~/.config/wezterm/colors/claude-light.toml
```

Then set in your config (`~/.wezterm.lua`):

```lua
config.color_scheme = "claude"
-- or
config.color_scheme = "Claude Light"
```

### Windows Terminal

1. Open **Settings** (Ctrl+,)
2. Click **Open JSON file** in the bottom-left corner
3. Find the `"schemes"` array and add the contents of [`windows-terminal/claude.json`](windows-terminal/claude.json) (dark) or [`windows-terminal/claude-light.json`](windows-terminal/claude-light.json) (light)
4. Set `"colorScheme": "Claude"` or `"colorScheme": "Claude Light"` in your profile

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
