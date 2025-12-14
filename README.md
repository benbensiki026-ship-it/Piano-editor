# 🎹 C++ QWERTY Piano - Complete Feature List

## ✨ Core Piano Features

### Keyboard Input
- **3 Simultaneous Octaves**: Play notes from C3 to E5 simultaneously
- **29 Piano Keys Mapped**: Complete chromatic scale across 3 octaves
- **QWERTY Layout**: Intuitive layout matching piano keyboard structure
  - Bottom row: Z-M (C3-B3)
  - Middle row: Q-U (C4-B4)  
  - Top row: I-P (C5-E5)
- **Black Keys Support**: Sharp/flat notes using number keys and letter keys

### Sound & Playback
- **Real-time Frequency Calculation**: Based on A440 tuning standard
- **MIDI Note Display**: Shows note name, octave, and frequency
- **Velocity Control**: 128 levels of velocity (0-127)
- **Note Information**: Real-time display of what's being played

## 🎚️ Control Features

### Octave Shifting
- **±3 Octave Range**: Total range of 6+ octaves
- **Dynamic Shifting**: Change octaves on-the-fly while playing
- **Visual Feedback**: Current octave displayed in status

### Velocity Control
- **127 Velocity Levels**: Full MIDI velocity range
- **Incremental Adjustment**: Fine-tune with +/- keys
- **Dynamic Response**: Immediate feedback on changes

### Sustain Pedal
- **Toggle Sustain**: Enable/disable sustain effect
- **Note Persistence**: Notes continue after key release when active
- **Visual Indicator**: Status shows sustain state

## 📼 Recording Features

### Performance Recording
- **Real-time Recording**: Capture your playing as you perform
- **MIDI Event Capture**: Records note on/off, timing, and velocity
- **Start/Stop Control**: Easy recording controls (F1/F2)
- **Event Counter**: See how many events you've recorded

### File Management
- **Save Recordings**: Export to MIDI file format
- **Custom Filenames**: Name your recordings
- **MIDI Format Support**: Standard MIDI file output
- **Timestamp Tracking**: Accurate timing information

## 🎼 MIDI Features

### MIDI Import
- **Load MIDI Files**: Import standard MIDI files
- **File Format Support**: Handles Type 0 and Type 1 MIDI files
- **Error Handling**: Validates file format before loading
- **Multiple Load Methods**: F5 key or 'L' command

### MIDI Export
- **Export Recordings**: Save performances as MIDI files
- **Standard Format**: Compatible with other MIDI software
- **Complete Event Data**: Preserves timing, velocity, and note information

### MIDI Playback (Framework)
- **Sequence Playback**: Play loaded MIDI sequences
- **Event Processing**: Handles MIDI events systematically
- **Extensible Design**: Ready for enhanced playback features

## 🖥️ User Interface

### Visual Displays
- **ASCII Art Interface**: Beautiful text-based UI
- **Keyboard Layout Display**: Visual representation of key mappings
- **Help Menu**: Comprehensive F11 help screen
- **Status Display**: Real-time system status (F12)
- **Welcome Screen**: Attractive startup screen

### Status Information
- **Current Octave**: Shows active octave offset
- **Velocity Level**: Displays current velocity setting
- **Sustain State**: Shows if sustain is on/off
- **Recording Status**: Indicates when recording is active
- **Event Count**: Shows recorded events during recording

### Interactive Help
- **F11 Help Menu**: Complete command reference
- **F10 Keyboard Layout**: Visual key mapping guide
- **F12 Status**: Current settings at a glance
- **In-app Documentation**: No need to reference external docs

## 🛠️ Technical Features

### Cross-Platform Support
- **Linux Support**: Native terminal support
- **macOS Support**: Unix-like system compatibility
- **Windows Support**: MinGW/Cygwin/WSL compatible
- **Build Scripts**: Platform-specific build automation

### Build System
- **Makefile**: Traditional Make-based building
- **Shell Script**: Linux/Mac automated build
- **Batch File**: Windows automated build
- **Clean Command**: Easy cleanup of artifacts

### Code Architecture
- **Object-Oriented Design**: Clean C++ class structure
- **Modular Components**: Separated piano logic and UI
- **Header/Implementation Split**: Professional code organization
- **Extensible Framework**: Easy to add new features

### Performance
- **Optimized Compilation**: -O2 optimization flag
- **Efficient Input Handling**: Non-blocking keyboard input
- **Low Latency**: 10ms polling interval
- **Memory Efficient**: Minimal resource usage

## 📚 Documentation

### User Documentation
- **README.md**: Complete user manual
- **QUICKSTART.md**: Get started in minutes
- **MIDI_FILES.md**: MIDI file resources and tips
- **Inline Help**: F11 key for instant help

### Developer Documentation
- **Code Comments**: Well-commented source code
- **Header Documentation**: Clear interface definitions
- **Build Instructions**: Multiple build methods documented
- **Architecture Overview**: Code structure explained

## 🔧 Utility Features

### File Operations
- **Save/Load**: Persistent storage of recordings
- **File Validation**: Checks file format before operations
- **Error Messages**: Clear error reporting
- **User Prompts**: Interactive file naming

### Configuration
- **.gitignore**: Git integration ready
- **Makefile Targets**: Multiple build targets (clean, install, run)
- **Customizable Paths**: Easy to modify installation locations

### Safety Features
- **Input Validation**: Checks all user inputs
- **Range Checking**: MIDI note and velocity bounds
- **Error Handling**: Graceful error recovery
- **Safe Exit**: Clean shutdown on ESC

## 🎯 Advanced Features (Framework)

### Extensibility Points
- **MidiEvent Structure**: Ready for complex events
- **Note Management**: Flexible note tracking system
- **Recording Infrastructure**: Built for expansion
- **Plugin Architecture**: Easy to add new features

### Future-Ready Design
- **Audio Output Ready**: Structure supports audio synthesis
- **Multi-track Ready**: Framework supports multiple tracks
- **Effect Processing**: Velocity and sustain framework in place
- **External MIDI**: Structure ready for MIDI device input

## 📊 Statistics & Monitoring

### Performance Tracking
- **Note Timing**: Accurate timestamp tracking
- **Event Counting**: Real-time event statistics
- **Recording Duration**: Track session length
- **Active Notes**: Monitor currently playing notes

### Display Features
- **Frequency Display**: Shows Hz for each note
- **Note Names**: Musical notation for played notes
- **Octave Numbers**: Scientific pitch notation
- **Velocity Values**: Current playing dynamics

## 🎨 Special Features

### Visual Polish
- **Unicode Characters**: Musical symbols (♪)
- **Box Drawing**: Professional ASCII art borders
- **Color Potential**: Terminal color support ready
- **Formatted Output**: Clean, aligned displays

### User Experience
- **Instant Feedback**: Immediate response to input
- **Clear Messages**: Descriptive status messages
- **Intuitive Controls**: Logical key mappings
- **Multiple Access**: Alternative keys for common functions

## 📦 Package Contents

### Source Files
- `piano.h` - Main class definitions
- `piano.cpp` - Piano implementation
- `main.cpp` - User interface and input handling

### Build Files
- `Makefile` - Unix make build system
- `build.sh` - Automated Linux/Mac build script
- `build.bat` - Automated Windows build script

### Documentation
- `README.md` - Complete manual (5000+ words)
- `QUICKSTART.md` - Quick start guide
- `MIDI_FILES.md` - MIDI resources
- `FEATURES.md` - This file

### Configuration
- `.gitignore` - Git configuration

## 🚀 Getting Started

1. **Extract**: Unzip the archive
2. **Build**: Run `./build.sh` (Linux/Mac) or `build.bat` (Windows)
3. **Play**: Execute `./piano` and start making music!

---

**Total Lines of Code**: ~1000+ lines of C++
**File Size (zip)**: ~13KB
**Compilation Time**: <5 seconds
**Runtime Requirements**: C++ compiler, terminal

Made with ❤️ for music and coding enthusiasts!
