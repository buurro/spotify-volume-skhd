# Spotify volume control for skhd

## Prerequisites

- [skhd](https://github.com/koekeishiya/skhd)

## Installation

```bash
# copy the scripts
mkdir -p ~/.local/bin && cp spotify-volume-* ~/.local/bin

# add skhd config
echo "
# spotify volume
alt - g : ~/.local/bin/spotify-volume-down
alt - h : ~/.local/bin/spotify-volume-up" >> ~/.skhdrc
```
