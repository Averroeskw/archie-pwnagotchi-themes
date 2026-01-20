# Archie's Pwnagotchi Themes

Custom Fancygotchi themes for Pwnagotchi with real pixel art faces and backgrounds.

**Made by Archie**

## Themes Included

| Theme | Inspired By | Face Style | Background |
|-------|-------------|------------|------------|
| **morty** | Rick and Morty | Real Morty pixel art | Custom |
| **rick** | Rick and Morty | Real Rick pixel art | Custom |
| **hackers** | Hackers (1995) | Bomb icon pixel art | Retro green grid |
| **holo** | Spice and Wolf | Wolf/anime pixel art | Pink anime |
| **vaultboy** | Fallout | Real Vault Boy pixel art | Retro gold |
| **dedsec** | Watch Dogs | Skull mask with X eyes | DedSec Wrench artwork |
| **gits** | Ghost in the Shell | Cyber visor + circuits | Cyber grid |
| **fsociety** | Mr. Robot | Red skull mask | DedSec Reaper artwork |
| **lain** | Serial Experiments Lain | Bear suit face | Glitch pattern |
| **nerv** | Neon Genesis Evangelion | EVA-01 mecha head | Hexagon pattern |
| **akira** | Akira (Neo-Tokyo) | Red pill capsule "41" | Neon streaks |
| **cyberpunk** | Cyberpunk 2077 | Yellow cyber visor | DedSec Hackerden |

## Features

- Real pixel art faces (Morty, Rick, Holo, Hackers themes)
- High-quality DedSec backgrounds from Watch Dogs
- Laughing Man logo integration for Ghost in the Shell theme
- Terminal-style boot animations
- Optimized for 320x240 Display Hat Mini
- Pre-rotated 180° for correct display orientation

## Installation

1. Copy themes to your Pwnagotchi:
```bash
scp -r * pi@10.0.0.2:/usr/local/share/pwnagotchi/custom-plugins/themes/
```

2. Set your theme in `/etc/pwnagotchi/config.toml`:
```toml
main.plugins.fancygotchi.theme = "morty"
```

3. Restart Pwnagotchi:
```bash
sudo systemctl restart pwnagotchi
```

## Requirements

- Pwnagotchi with Fancygotchi plugin
- Display Hat Mini (320x240) or compatible display
- Display rotation: 180°

## License

MIT License - Free to use and modify.

## Credits

Created by **Archie**

### Artwork Sources
- Face artwork from [PWNAGOTCHI-CUSTOM-FACES-MOD](https://github.com/roodriiigooo/PWNAGOTCHI-CUSTOM-FACES-MOD)
- DedSec backgrounds from [dedsec-grub2-theme](https://github.com/VandalByte/dedsec-grub2-theme)
- Laughing Man logo from [Laughing-Man-Logo](https://github.com/WeirdConstructor/Laughing-Man-Logo)
