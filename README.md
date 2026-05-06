# Leenium

A dark, teal-accented theme for [Omarchy](https://github.com/basecamp/omarchy). Deep abyss backgrounds with glowing mint highlights and a retro pixel aesthetic.

![Preview](preview.png)

![Lock screen](preview-unlock.png)

---

## Color Palette

| Role | Hex | |
|---|---|---|
| Background | `#060b0f` | ![](https://placehold.co/16x16/060b0f/060b0f.png) |
| Surface | `#0b1319` | ![](https://placehold.co/16x16/0b1319/0b1319.png) |
| Overlay | `#1d313d` | ![](https://placehold.co/16x16/1d313d/1d313d.png) |
| Muted | `#8cb7a9` | ![](https://placehold.co/16x16/8cb7a9/8cb7a9.png) |
| Foreground | `#d8f7ea` | ![](https://placehold.co/16x16/d8f7ea/d8f7ea.png) |
| Accent (Teal) | `#35d6a0` | ![](https://placehold.co/16x16/35d6a0/35d6a0.png) |
| Cyan | `#94f1cd` | ![](https://placehold.co/16x16/94f1cd/94f1cd.png) |
| Blue | `#376781` | ![](https://placehold.co/16x16/376781/376781.png) |
| Yellow | `#ffd479` | ![](https://placehold.co/16x16/ffd479/ffd479.png) |
| Red | `#ff5f56` | ![](https://placehold.co/16x16/ff5f56/ff5f56.png) |

---

## What's Included

| File | Applies to |
|---|---|
| `colors.toml` | Omarchy color definitions (terminal, UI) |
| `btop.theme` | btop system monitor |
| `chromium.theme` | Chromium / Chrome NTP accent |
| `waybar.css` | Waybar status bar color variables |
| `swayosd.css` | SwayOSD on-screen display (volume, brightness) |
| `neovim.lua` | Neovim via [leenium.nvim](https://github.com/drunkleen/leenium.nvim) |
| `vscode.json` | VS Code color customizations |
| `icons.theme` | Icon pack (`Yaru-olive`) |
| `backgrounds/` | 6 wallpapers |

### Backgrounds

- `leenium.png` — abstract dark signature wallpaper
- `artificial-valley.jpg` — misty mountain valley
- `creation.png` — artistic generative
- `dresden.png` — Dresden cityscape
- `london.png` — London cityscape
- `rasht.png` — Rasht cityscape

---

## Installation

```bash
omarchy theme install https://github.com/drunkleen/leenium.omarchy
```

Or manually clone into your Omarchy themes directory:

```bash
git clone https://github.com/drunkleen/leenium.omarchy \
  ~/.local/share/omarchy/themes/leenium
omarchy theme apply leenium
```

---

## License

MIT
