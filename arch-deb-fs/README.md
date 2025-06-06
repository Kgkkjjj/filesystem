# Arch & Debian Compatible Filesystem with GUI

This project provides a minimal filesystem prototype in C with a simple GUI,
intended for Arch Linux and Debian-based systems. The design focuses on
simplicity while offering a set of features users will love.

## Features (14 Things Users Will Love)

1. **Cross-Platform Builds** - Works on both Arch Linux and Debian derivatives.
2. **Graphical Interface** - GTK-based GUI for easy management.
3. **FUSE Integration** - Mount the filesystem in user space.
4. **Modular Design** - Separated core logic and GUI code for maintainability.
5. **Easy Configuration** - Simple config file to customize behavior.
6. **Pluggable Storage Backends** - Supports multiple data storage methods.
7. **Transaction Logging** - Basic journaling for reliability.
8. **CLI Utilities** - Command-line tools for scripting support.
9. **Multilingual UI** - Localization-ready interface.
10. **Package Build Scripts** - PKGBUILD and Debian packaging templates.
11. **Extensible API** - Hooks for adding custom modules.
12. **Documentation** - Developer and user docs included.
13. **Unit Test Framework** - Basic C test suite example.
14. **Open Source License** - Licensed under MIT for flexibility.

## Building

Use the provided Makefile. Dependencies include `gcc`, `make`, and `gtk+-3.0`.

```bash
make
```

## Running

After building, run the executable:

```bash
./fs_gui
```

This will launch the GUI, allowing you to mount and manage the prototype
filesystem.
