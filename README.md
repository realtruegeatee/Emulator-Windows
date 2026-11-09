# Emulator-Windows

A lightweight Windows-style desktop emulator that runs entirely in the browser.

## Overview

This project is a browser demo rather than a full virtual machine. It provides a small desktop, Start menu, taskbar clock, app windows, and local browser persistence.

## Features

- Windows-style desktop and taskbar
- Notepad with locally saved notes
- Calculator with basic arithmetic
- Settings for accent color and contrast
- File Explorer with browser file upload, virtual files, and downloads
- App Store with persistent app installation
- Draggable desktop icons and application windows
- Responsive layout for desktop and mobile browsers

## Getting Started

### Prerequisites

- A modern web browser

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/realtruegeatee/Emulator-Windows.git
   cd Emulator-Windows
   ```

2. Open `docs/index.html` in a browser, or serve the repository with any static web server.

### Usage

The live demo is published at:
`https://realtruegeatee.github.io/Emulator-Windows/`

Files and installed apps are stored locally in the browser. The demo cannot access the host computer's files without an explicit upload, and it cannot install native Windows applications.

## Project Structure

```
Emulator-Windows/
├── docs/index.html
├── .github/workflows/pages.yml
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is currently unlicensed. Please add a license file if needed.

## Support

For questions, issues, or suggestions, please open an issue in the repository.

---

**Repository**: [realtruegeatee/Emulator-Windows](https://github.com/realtruegeatee/Emulator-Windows)
