# iTE Releases

Public binary releases for [iTE](https://ite.kiishi.space)

iTE is an AI coding agent that runs in your terminal. 


[![iTE Demo](https://ite.kiishi.space/ite-prev.png)](https://ite.kiishi.space/demo.mp4)

## Install

### macOS / Linux

```bash
curl -fsSL https://ite.kiishi.space/install.sh | bash
```

### Windows (PowerShell)

```powershell
irm https://ite.kiishi.space/install.ps1 | iex
```

The installer detects your OS and architecture, downloads the latest standalone iTE binary, verifies its checksum, and adds `ite` to your PATH. No dependencies required.

Supported targets: `darwin-arm64`, `darwin-x64`, `linux-x64`, `win32-x64`.

## Verifying Integrity

The installer automatically verifies the SHA-256 checksum of every downloaded archive against the [release manifest](https://ite.kiishi.space/releases/manifest.json).

## From Source

If you prefer installing from source:

```bash
pipx install ite-agent          # isolated environment
uv tool install ite-agent        # via uv
pip install ite-agent            # global pip
```

## Documentation

- [iTE Docs](https://ite.kiishi.space/docs)
