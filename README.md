# Project Tabs Restored for macOS

When a new project opens in a separate window, this plugin invokes the IDE's **Merge All Project Windows** action after the new window becomes visible. It supports IntelliJ IDEA 2025 and 2026 on macOS.

This is a maintained fork of [macOS Force Project Tabs](https://github.com/MatCyg/mac_os_force_project_tabs) by Mat Cygert. The original MIT license and copyright notice are retained in [LICENSE](LICENSE).

The original plugin and this fork have different plugin IDs. Uninstall the original plugin before installing this fork so that both do not attempt to merge windows at the same time.

## Build

With JDK 21 or newer, run `./gradlew buildPlugin`. The distributable ZIP is placed in `build/distributions/`.
