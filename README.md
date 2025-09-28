# Firefox .deb Builder for LudusOS 13 (Gladius) - Debian

This repository contains a GitHub Actions workflow that automatically builds the latest stable version of Mozilla Firefox.

The workflow compiles it into a `.deb` package named **`firefox-ludus`**, built on Debian 13 to ensure maximum compatibility. The process runs on a daily schedule, checking for new Firefox versions and publishing them to the Releases page if an update is found.

## Usage

1.  Go to the [**Releases page**](../../releases).
2.  Download the `.deb` file from the latest release asset.
3.  Install it via the terminal with `apt`:

    ```bash
    sudo apt install ./firefox-ludus_*.deb
    ```
