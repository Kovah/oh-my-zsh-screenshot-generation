# Oh My ZSH Theme Screenshot Generation

This repository contains test files and the macOS Automator app to generate the [screenshots for all Oh my ZSH themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes).

## Requirements

* macOS (Automator app was built for it, otherwise build your own automation to generate screenshots)
* Fira Code font

## Setup

1. Clone the repo to your home directory.
2. Open the built-in Terminal app of macOS and set the default theme to `Basic`. Also, set `Fira Code` as the standard font with a size of `13pt`.
3. Switch into the `oh-my-zsh-theme-test` folder.
4. Either run the `prepare.sh` script or run the following commands within your Terminal:
    ```
    touch app/app.js
    touch app/styles.scss
    git add app/app.js
    ```
5. Run the ZSH Themes app, which will then guide you through the screenshot generation.
