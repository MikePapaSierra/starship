# Starship Configuration

![Made with Starship](https://img.shields.io/badge/Made%20with-Starship-7D4CDB?logo=starship&logoColor=white)
![Theme: Catppuccin](https://img.shields.io/badge/Theme-Catppuccin-FFC0CB)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
![Config only](https://img.shields.io/badge/Configuration-Personal-informational)

This repository contains my personal configuration for [Starship](https://starship.rs/), a minimal, blazing-fast, and extremely customizable prompt.

It is used together with my [Fish shell configuration](https://github.com/MikePapaSierra/fish).

## Purpose

This setup is customized for my preferences and daily work.
The repository is public to serve as inspiration — feel free to **fork** and **adjust** it to your liking!

> **Note:** Contributions are not accepted, as this is a personal configuration.

## Installation

1. Install Starship:

    - **MacOS** (Homebrew):
    
      ```bash
      brew install starship
      ```
    - **Linux** (Debian/Ubuntu):
    
      ```bash
      sudo apt install starship
      ```
    - **Linux** (Arch):
    
      ```bash
      sudo pacman -S starship
      ```
    - **General** (via script):

      ```bash
      curl -sS https://starship.rs/install.sh | sh
      ```

2. Copy or symlink the `starship.toml` file into your `$HOME/.config/` directory:

    ```bash
    mkdir -p ~/.config
    cp starship.toml ~/.config/starship.toml
    ```

3. Ensure your shell config (`config.fish` or others) sources Starship:

    ```fish
    starship init fish | source
    ```

4. Customize the prompt via `starship.toml`.

## Structure

- `starship.toml` — main configuration file for Starship prompt.

## License

This project is shared under the [MIT License](LICENSE), but primarily for reference. Fork freely!
