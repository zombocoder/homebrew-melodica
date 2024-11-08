# Homebrew Melodica

This is the official Homebrew tap for [Melodica](https://github.com/zombocoder/melodica), a console-based audio player built with Go. With this tap, you can install and manage `melodica` through Homebrew on macOS.

## Installation

To install Melodica via Homebrew:

1. **Add the Tap**:

   ```bash
   brew tap zombocoder/melodica
   ```

2. **Install Melodica**:

   ```bash
   brew install melodica
   ```

This will download, build, and install the latest release of Melodica.

## Updating Melodica

To update to the latest version:

```bash
brew update
brew upgrade melodica
```

## Features

- **Cross-platform Compatibility**: Supports macOS, Windows, and Linux.
- **Intuitive Controls**:
  - `Enter`: Play selected track
  - `s`: Stop playback
  - `n`: Next track
  - `p`: Previous track
  - `x`: Pause/Resume playback
  - `>`: Volume up
  - `<`: Volume down
  - `Esc`: Quit application

## Usage

To run Melodica after installation, simply use:

```bash
melodica path/to/playlist.txt
```

## Example Playlist

To create a quick sample playlist, download `playlist.txt`:

```bash
curl -o playlist.txt https://raw.githubusercontent.com/zombocoder/melodica/main/playlist.txt
```

Then, start Melodica with the playlist:

```bash
melodica playlist.txt
```

## Uninstallation

To remove Melodica from your system:

```bash
brew uninstall melodica
```

## License

Melodica is licensed under the [MIT License](https://github.com/zombocoder/melodica/blob/main/LICENSE).

---

### Additional Resources

For more information, visit the [Melodica GitHub repository](https://github.com/zombocoder/melodica) or refer to the [Homebrew documentation](https://docs.brew.sh/).
