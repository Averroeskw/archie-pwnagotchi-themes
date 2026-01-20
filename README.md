# Archie's Pwnagotchi Themes

Custom Fancygotchi themes for Pwnagotchi with epic visual effects.

**Made by Archie**

## Themes Included

| Theme | Inspired By | Boot Animation Style |
|-------|-------------|---------------------|
| **dedsec** | Watch Dogs | Matrix Rain |
| **gits** | Ghost in the Shell | Glitch Effect |
| **lain** | Serial Experiments Lain | Terminal Boot |
| **nerv** | Neon Genesis Evangelion | Glitch Effect |
| **akira** | Akira (Neo-Tokyo) | Matrix Rain |
| **fsociety** | Mr. Robot | Terminal Boot |
| **deusex** | Deus Ex | Glitch Effect |
| **bladerunner** | Blade Runner | Matrix Rain |
| **transistor** | Transistor | Terminal Boot |
| **shodan** | System Shock | Glitch Effect |
| **awgeez** | Rick and Morty | Matrix Rain |
| **neurallink** | Neural Network | Terminal Boot |

## Visual Effects

- CRT scanline overlays
- Vignette darkening at screen edges
- Matrix rain falling character animations
- Glitch/RGB split effects
- Terminal-style typing boot sequences
- Glow effects on face expressions
- Themed procedural backgrounds (grids, hexagons, circuits)

## Installation

1. Copy themes to your Pwnagotchi:
```bash
scp -r * pi@10.0.0.2:/usr/local/share/pwnagotchi/custom-plugins/themes/
```

2. Set your theme in `/etc/pwnagotchi/config.toml`:
```toml
main.plugins.fancygotchi.theme = "dedsec"
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

Created by **Archie** with love for the Pwnagotchi community.
