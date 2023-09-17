# Catppuccin Theme Modification

This project is about making some changes to the Catppuccin theme using [Spicetify](https://github.com/khanhas/spicetify-cli) and introducing a new color theme called "Bard."

## Catppuccin Theme

The main theme used here is Catppuccin. This theme offers a customized music playback experience for Spicetify users, with modifications to the theme's appearance and color scheme updates.

## Bard Color Theme

We've added a new color theme called "Bard" to the project, built on top of the Catppuccin Theme. Bard is designed to refresh Spotify's interface with different colors and design elements.

## Installation

1. Start by installing Spicetify on your computer if you haven't already. You can download it from [here](https://github.com/khanhas/spicetify-cli).

2. Clone this theme and the Bard color theme repositories to your computer:

```bash
   git clone https://github.com/WoXy-Sensei/bard-spicetify
```

3. Add the themes to Spicetify:

```
cp -r bard-spicetify ~/.config/spicetify/Themes/
```

4. Enable the themes:

```
spicetify config current_theme bard-spicetify
spicetify config color_scheme bard
spicetify config inject_css 1 inject_theme_js 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

5. Finish

Restart the Spotify desktop client, and enjoy the Catppuccin theme and the Bard color theme!

## Screenshots
[theme1](https://i.imgur.com/ZGHkuLg_d.webp?maxwidth=760&fidelity=grand)
[theme2](https://imgur.com/KWQ10GC)
[theme3](https://imgur.com/qD4pYPw)

## Contributing

Both themes are still under development, and we welcome your contributions. Please open an issue for any bug reports or suggestions, or submit a pull request.

