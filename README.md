# Claude Terminal Theme

A warm, earthy terminal color scheme inspired by [Claude's](https://claude.ai) visual identity. Features terracotta orange accents, warm neutrals, and a dark background designed for long coding sessions.

> **Disclaimer:** This is an unofficial, community-made theme. It is not affiliated with or endorsed by Anthropic.

## Preview

<!-- Add a screenshot of your terminal here -->
<!-- ![Claude Terminal Theme](preview.png) -->

*Screenshot coming soon — contributions welcome!*

## Color Palette

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

## Installation

### iTerm2

1. Download [`iterm2/Claude.itermcolors`](iterm2/Claude.itermcolors)
2. Open **iTerm2 > Settings > Profiles > Colors**
3. Click **Color Presets... > Import...**
4. Select the downloaded file
5. Choose **Claude** from the presets dropdown

### Ghostty

Copy [`ghostty/claude`](ghostty/claude) to your Ghostty themes directory:

```bash
cp ghostty/claude ~/.config/ghostty/themes/claude
```

Then set in your config (`~/.config/ghostty/config`):

```
theme = claude
```

### Alacritty

Copy [`alacritty/claude.toml`](alacritty/claude.toml) to your Alacritty themes directory:

```bash
mkdir -p ~/.config/alacritty/themes
cp alacritty/claude.toml ~/.config/alacritty/themes/claude.toml
```

Then import in your config (`~/.config/alacritty/alacritty.toml`):

```toml
import = ["~/.config/alacritty/themes/claude.toml"]
```

### Kitty

Copy [`kitty/claude.conf`](kitty/claude.conf) to your Kitty themes directory:

```bash
cp kitty/claude.conf ~/.config/kitty/themes/claude.conf
```

Then include in your config (`~/.config/kitty/kitty.conf`):

```
include themes/claude.conf
```

### WezTerm

Copy [`wezterm/claude.toml`](wezterm/claude.toml) to your WezTerm colors directory:

```bash
mkdir -p ~/.config/wezterm/colors
cp wezterm/claude.toml ~/.config/wezterm/colors/claude.toml
```

Then set in your config (`~/.wezterm.lua`):

```lua
config.color_scheme = "claude"
```

### Windows Terminal

1. Open **Settings** (Ctrl+,)
2. Click **Open JSON file** in the bottom-left corner
3. Find the `"schemes"` array and add the contents of [`windows-terminal/claude.json`](windows-terminal/claude.json)
4. Set `"colorScheme": "Claude"` in your profile

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
