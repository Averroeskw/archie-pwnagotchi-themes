# Archie's Pwnagotchi Themes

Custom Fancygotchi themes for Pwnagotchi with unique pixel art faces and backgrounds.

**Made by Archie**

## Themes Included (12)

| Theme | Inspired By | Face Style | Color |
|-------|-------------|------------|-------|
| **dedsec** | Watch Dogs | Skull mask with X eyes | Green |
| **gits** | Ghost in the Shell | Cyber visor + circuits | Cyan |
| **fsociety** | Mr. Robot | Red skull mask | Red |
| **lain** | Serial Experiments Lain | Bear suit face | Magenta |
| **nerv** | Neon Genesis Evangelion | EVA-01 mecha head | Orange |
| **akira** | Akira (Neo-Tokyo) | Red pill capsule "41" | Red |
| **cyberpunk** | Cyberpunk 2077 | Yellow cyber visor | Yellow |
| **morty** | Rick and Morty | Real Morty pixel art | Yellow |
| **rick** | Rick and Morty | Real Rick pixel art | Cyan |
| **hackers** | Hackers (1995) | Bomb icon pixel art | Green |
| **holo** | Spice and Wolf | Wolf/anime pixel art | Magenta |
| **vaultboy** | Fallout | Real Vault Boy pixel art | Yellow |

## Features

- Unique pixel art faces for each theme
- High-quality backgrounds (DedSec artwork, custom patterns)
- Boot animations
- Full Fancygotchi widget configuration
- Optimized for 320x240 Display Hat Mini
- Correct rotation for 180° displays

## Installation

1. Copy themes to your Pwnagotchi:
```bash
scp -r * pi@10.0.0.2:/usr/local/share/pwnagotchi/custom-plugins/themes/
```

2. Set your theme in `/etc/pwnagotchi/config.toml`:
```toml
main.plugins.Fancygotchi.theme = "morty"
```

3. Restart Pwnagotchi:
```bash
sudo systemctl restart pwnagotchi
```

## Requirements

- Pwnagotchi with Fancygotchi plugin
- Display Hat Mini (320x240) or compatible display

## License

MIT License - Free to use and modify.

## Credits

Created by **Archie**

### Artwork Sources
- Face artwork from [PWNAGOTCHI-CUSTOM-FACES-MOD](https://github.com/roodriiigooo/PWNAGOTCHI-CUSTOM-FACES-MOD)
- DedSec backgrounds from [dedsec-grub2-theme](https://github.com/VandalByte/dedsec-grub2-theme)
- Laughing Man logo from [Laughing-Man-Logo](https://github.com/WeirdConstructor/Laughing-Man-Logo)
- Fancygotchi by [V0r-T3x](https://github.com/V0r-T3x/Fancygotchi)
