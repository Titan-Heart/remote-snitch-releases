# remote-snitch

Pre-built binaries for the remote-snitch employee monitoring agent.

## Quick Install (Linux / macOS)

```bash
curl -fsSL https://raw.githubusercontent.com/Titan-Heart/remote-snitch-releases/main/install.sh | sh
```

This detects your OS and architecture, downloads the latest release, and installs to `~/.local/bin`.

To install to a custom directory:

```bash
INSTALL_DIR=/usr/local/bin curl -fsSL https://raw.githubusercontent.com/Titan-Heart/remote-snitch-releases/main/install.sh | sh
```

## Install via cargo-binstall

If you have [cargo-binstall](https://github.com/cargo-bins/cargo-binstall) installed:

```bash
cargo binstall rems-client
```

## Manual Download

Visit the [Releases](https://github.com/Titan-Heart/remote-snitch-releases/releases) page and download the binary for your platform:

| Platform | File |
|----------|------|
| Linux x86_64 | `remote-snitch-x86_64-unknown-linux-gnu.tar.gz` |
| macOS Intel | `remote-snitch-x86_64-apple-darwin.tar.gz` |
| macOS Apple Silicon | `remote-snitch-aarch64-apple-darwin.tar.gz` |
| Windows x86_64 | `remote-snitch-x86_64-pc-windows-msvc.zip` |

## Verify Installation

```bash
remote-snitch --help
```

## Windows

Download the `.zip` from the Releases page, extract `remote-snitch.exe`, and add it to your PATH.
