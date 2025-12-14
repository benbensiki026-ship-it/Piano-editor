cd /home/BenBenSIKK/waterfall-piano && cat > README.md << 'EOF'
# 88-Key Waterfall Piano

Waterfall piano visualization with full 88-key keyboard and MIDI file support.

## Features
- Full 88-key piano (A0 to C8)
- MIDI file import and playback
- Waterfall note visualization
- Multi-channel color coding
- Adjustable playback/scroll speed
- Velocity-sensitive display

## Quick Start

### Linux
```bash
sudo apt-get install libsdl2-dev g++ make
make
./waterfall-piano song.mid
```

### Windows
```bash
# Install SDL2 and MinGW
g++ -std=c++14 -o waterfall-piano.exe main.cpp -lSDL2
waterfall-piano.exe song.mid
```

## Controls
| Key | Action |
|-----|--------|
| SPACE | Play/Pause |
| R | Restart |
| ↑/↓ | Scroll Speed |
| ←/→ | Playback Speed |
| +/- | Skip ±5s |
| ESC | Quit |

## Requirements
- SDL2
- C++14 compiler
- MIDI file (optional)

## Finding MIDI Files
- BitMIDI: https://bitmidi.com/
- FreeMIDI: http://freemidi.org/
- MuseScore: https://musescore.com/

## Build
```bash
# Simple
make

# CMake
mkdir build && cd build
cmake .. && make
```

## License
MIT License - See LICENSE file
EOF
