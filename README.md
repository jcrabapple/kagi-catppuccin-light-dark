# Kagi Catppuccin Light/Dark Theme

Copy and paste the contents of custom.css into the Custom CSS box in your Kagi appearance settings.

If you enjoy this theme and would like to buy me a coffee, you can do so via my [Kofi page](https://ko-fi.com/jcrabapple).

# Color Palettes

Your theme will change between light (**Catppuccin Latte**) and dark (**Catpuccin Mocha**) based on your browser/system settings, and via the toggle in the Kagi sidebar. Dark (Mocha) is the default.

## Catppuccin Latte Palette

| Color Name | Hex Code | Description |
|------------|----------|-------------|
| Rosewater  | #dc8a78  | Light pink-orange accent |
| Flamingo   | #dd7878  | Light pink accent |
| Pink       | #ea76cb  | Vibrant pink accent |
| Mauve      | #8839ef  | Purple accent |
| Red        | #d20f39  | Primary red |
| Maroon     | #e64553  | Dark red accent |
| Peach      | #fe640b  | Orange accent |
| Yellow     | #df8e1d  | Primary yellow |
| Green      | #40a02b  | Primary green |
| Teal       | #179299  | Blue-green accent |
| Sky        | #04a5e5  | Light blue accent |
| Sapphire   | #209fb5  | Blue accent |
| Blue       | #1e66f5  | Primary blue |
| Lavender   | #7287fd  | Light purple accent |
| Text       | #4c4f69  | Main text color |
| Subtext1   | #5c5f77  | Dimmed text/comments |
| Subtext0   | #6c6f85  | Dimmer text/comments |
| Overlay2   | #7c7f93  | Overlay highlights |
| Overlay1   | #8c8fa1  | Overlay and inactive elements |
| Overlay0   | #9ca0b0  | Faded overlay elements |
| Surface2   | #acb0be  | Surface highlights |
| Surface1   | #bcc0cc  | Light surface highlights |
| Surface0   | #ccd0da  | Surface colors |
| Base       | #eff1f5  | Base background |
| Mantle     | #e6e9ef  | Slightly darker background |
| Crust      | #dce0e8  | Darkest background |

## Catppuccin Mocha Palette

| Color Name | Hex Code | Description |
|------------|----------|-------------|
| Rosewater  | #f5e0dc  | Light pink-orange accent |
| Flamingo   | #f2cdcd  | Light pink accent |
| Pink       | #f5c2e7  | Vibrant pink accent |
| Mauve      | #cba6f7  | Purple accent |
| Red        | #f38ba8  | Primary red |
| Maroon     | #eba0ac  | Dark red accent |
| Peach      | #fab387  | Orange accent |
| Yellow     | #f9e2af  | Primary yellow |
| Green      | #a6e3a1  | Primary green |
| Teal       | #94e2d5  | Blue-green accent |
| Sky        | #89dceb  | Light blue accent |
| Sapphire   | #74c7ec  | Blue accent |
| Blue       | #89b4fa  | Primary blue |
| Lavender   | #b4befe  | Light purple accent |
| Text       | #cdd6f4  | Main text color |
| Subtext1   | #bac2de  | Dimmed text/comments |
| Subtext0   | #a6adc8  | Dimmer text/comments |
| Overlay2   | #9399b2  | Overlay highlights |
| Overlay1   | #7f849c  | Overlay and inactive elements |
| Overlay0   | #6c7086  | Faded overlay elements |
| Surface2   | #585b70  | Surface highlights |
| Surface1   | #45475a  | Light surface highlights |
| Surface0   | #313244  | Surface colors |
| Base       | #1e1e2e  | Base background |
| Mantle     | #181825  | Slightly darker background |
| Crust      | #11111b  | Darkest background |

# Fonts

If you'd like to change the font, add the following CSS and include the name of your desired font:

```
body {
    font-family: Arial, sans-serif !important;
}
```

For example, I like to use the Poppins font:

```
body {
    font-family: Poppins sans-serif !important;
}

```

# Underlined Search Result Titles

If you'd like to add back the underlining of the titles in search results, remove or comment out the following lines:

```
/* OPTIONAL disable underline on title links in search result */
.__sri-title .__sri_title_link {
  border-bottom: none;
}
```

So it would look like this:

```
/* OPTIONAL disable underline on title links in search result */
/* .__sri-title .__sri_title_link {
  border-bottom: none;
} */
```
