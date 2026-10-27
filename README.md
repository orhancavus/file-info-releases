# File Info — Desktop Downloads (macOS & Linux)

**File Info** is a fast, lightweight native desktop utility for **macOS** and **Linux** that lets you select or drag-and-drop any file to inspect its text content (`.txt`, `.csv`, `.json`, `.xml`, `.md`, `.log`, etc.) and view a concise **File Summary** (Total Size, Total number of words, and File type).

> **Note:** This repository serves as the public **Releases-Only** distribution channel. Pre-built installers are available on the [GitHub Releases](../../releases/latest) page.

---

## Download Latest Release

👉 **[Download from Latest Releases](../../releases/latest)**

| Platform | Architecture | Package Format |
| :--- | :--- | :--- |
| **macOS** | Apple Silicon (`M1` / `M2` / `M3` / `M4`) | `.dmg` / `.app.tar.gz` |
| **macOS** | Intel (`x86_64`) | `.dmg` / `.app.tar.gz` |
| **Linux** | `x86_64` (`Ubuntu`, `Debian`, `Fedora`, `Arch`) | `.AppImage` / `.deb` |

---

## First-Launch Instructions

### macOS (Unsigned App Gatekeeper Notice)
Because the binary is distributed directly without an Apple Developer notarization certificate, macOS Gatekeeper may show an *"unidentified developer"* or *"damaged"* prompt on first launch. Run the following command in Terminal after dragging **File Info.app** to `/Applications`:

```bash
xattr -cr "/Applications/File Info.app"
```

Then open **File Info** normally from Applications or Spotlight.

### Linux (`.AppImage` & `.deb`)
For **AppImage**:
```bash
chmod +x File.Info_*.AppImage
./File.Info_*.AppImage
```

For **Debian / Ubuntu (`.deb`)**:
```bash
sudo dpkg -i file-info_*.deb
```
