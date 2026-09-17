# monochrome ◼️

black base, gray text, one red accent.  
Omarchy theme, no rainbows involved.

---

## what's inside

| | |
|---|---|
| palette | `#000000` base, `#dadada` text, `#d70000` accent |
| terminal | `colors.toml` — black bg, gray scale, red accent |
| window | `hyprland.conf` — red gradient active border, 4/5 gaps, rounding 6 |
| lock | `hyprlock.conf` — black with red ring |
| notifications | `mako.ini` — black, red border, top-right |
| monitor | `btop.theme` + `cava_theme` — gray graphs, red peaks |
| multiplexer | `tmux.conf` — base / muted / accent vars |
| gtk | `gtk.css` — black + red |
| apps | steam, telegram, vesktop (`vencord.theme.css`), vscode (`Noctokai`), nvim (`monochrome`) |
| background | `backgrounds/empty.png` — pure black |

---

## palette

| role | color |
|---|---|
| background | `#000000` |
| text | `#dadada` |
| muted | `#707070` |
| dim | `#303030` / `#1c1c1c` |
| accent | `#d70000` |

grays do the work, red only where it matters: borders, cursor, selection, highlights.

---

## setup

```bash
omarchy theme install https://github.com/kovs713/monochrome.git
omarchy theme set Monochrome
```

based on [Solitude](https://github.com/HANCORE-linux/omarchy-solitude-theme) + [`monochrome.lua`](https://github.com/kovs713/nvim-config/blob/master/colors/monochrome.lua) from my nvim config.

### extras

vscode follows `vscode.json` (`Noctokai` theme). telegram / steam / vesktop files apply through their own import.

---

> steal whatever, no attribution needed
