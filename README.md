# Beam Remote — releases

Binary releases of Beam Remote. Source is closed; this repository holds release builds only.

Download from [Releases](../../releases). Asset names: `beam-remote-<version>-<platform>-<type>-<arch>.<ext>`

| Platform | Viewer | Host | Tools |
|---|---|---|---|
| Windows x64 | `windows-viewer-x64.zip` | `windows-host-x64.zip` (agent + service) | `windows-tools-x64.zip` |
| macOS Apple silicon | `macos-viewer-arm64.tar.gz` | `macos-host-arm64.tar.gz` | `macos-tools-arm64.tar.gz` |
| Android arm64 | `android-viewer-arm64.apk` | `android-host-arm64.apk` | |

Tools: `beam-remote` controls a paired host from the shell (screenshots, input, clipboard,
files; `beam-remote pair <name> '<beam://…>' <PIN>` first) and `beam-remote-mcp` is an MCP
server (stdio) that lets an AI agent do the same.

Checksums: `SHA256SUMS.txt` on each release. Only the latest release is kept.
