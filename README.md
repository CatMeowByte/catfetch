# CATFETCH

`catfetch` is yet another fetch-like written in shell. It uses 1-bit hand drawn graphics for the icon.

![screenshot](https://github.com/user-attachments/assets/892e62b9-d95a-44a3-9c9e-5f347942b14d)

## Installation

1. Make the script executable:

   ```sh
   chmod +x catfetch
   ```

2. Copy it to any directory in your `PATH`. The recommended location is `~/.local/bin`:

   ```sh
   cp catfetch ~/.local/bin/
   ```

3. Ensure the directory is in your `PATH`. If not, add the following to your shell configuration file:

   ```sh
   export PATH="$HOME/.local/bin:$PATH"
   ```

## Usage

Run:

```sh
catfetch
```

or put it in the last line of your shell configuration file.

## Configuration

to configure `catfetch`, you must edit the script file directly. all customization is done by changing variables defined at the top of the script.

the icon uses a 1-bit pixel drawing system: each character in the icon block represents a pixel. a space character means the pixel is **off**, and any other character means the pixel is **on**. this creates a grid-like layout where you can draw shapes by filling in pixels manually. the result is rendered as a monochrome icon in the terminal.

---

This project is licensed under [WTFPL](http://wtfpl.net "Do What the Fuck You Want to Public License").

This project follows the [HGG](https://catmeowbyte.github.io/heretic_git_guidelines "Heretic Git Guidelines").