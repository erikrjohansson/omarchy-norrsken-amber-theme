# Norrsken Amber

An amber variant of [Norrsken](https://github.com/erikrjohansson/omarchy-norrsken-theme): warm amber on a deep brown-black, with softly lit window edges, a translucent shell, and a glowing planet horizon.

![Norrsken Amber desktop preview](preview.png)

Neovim, the [cliamp](https://github.com/bjarneo/cliamp) music player, [Flea](https://github.com/erikrjohansson/flea), and btop using Norrsken Amber.

## Background

One **6K (6016 × 3384)** background: a thin amber planet edge against a star field with crisp pinpoint stars.

[![Norrsken Amber horizon](backgrounds/1-horisont.jpg)](backgrounds/1-horisont.jpg)

## Install

```bash
omarchy theme install https://github.com/erikrjohansson/omarchy-norrsken-amber-theme.git
```

Tested on Omarchy **4.0.4**.

## Palette

| Role | Color |
| --- | --- |
| Main surfaces | `#0e0906` |
| Raised surfaces | `#1a120c` |
| Text | `#f3e3cf` |
| Accent | `#ffb45e` |
| Active border | `#ffb45e` |
| Selection | `#3a2414` |
| Muted text | `#9a8470` |

## Customization and compatibility

`colors.toml` supplies the shared palette and the active window border. Omarchy generates terminal and supported application configurations from it. `shell.toml` styles the shell surfaces as translucent glass, and `gtk.css` styles GTK applications on setups that link GTK to the current theme. Update those files too when changing palette colors, then reapply the theme.

Norrsken Amber contains no application patches or install hooks.

## License

[MIT](LICENSE). Copyright (c) 2026 Erik Johansson.

Attribution for adapted upstream portions is recorded separately in [third-party notices](THIRD_PARTY_NOTICES.md).
