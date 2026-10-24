# Agento's Office — releases

Installers for **Agento's Office**, a live pixel-art office where every character is a Claude agent.
This repository holds only the installers (and the update feed the app reads). The source code is private.

## Install

Download from the [latest release](../../releases/latest):

- **Windows**: `Agentos-Office-<version>-win-x64.exe`. Windows SmartScreen may warn because the app isn't
  code-signed: choose **More info → Run anyway**.
- **macOS** (Apple silicon and Intel): `Agentos-Office-<version>-mac-universal.dmg`. Open it and drag the app to
  Applications. The app isn't signed, so the first time **right-click it → Open → Open**.

On first start the office runs in **simulation mode** (free). To use real Claude agents, open **Settings** (gear
icon), paste your Claude API key and press **Go live**. The key stays on your computer.

## Updates

The Windows app checks this repository when it starts, downloads new versions in the background and installs them
the next time you quit. On macOS, download the new `.dmg` from the releases page (automatic updates on macOS need a
signed app).
