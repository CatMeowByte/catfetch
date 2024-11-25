# catfetch

`catfetch` is a minimal system information tool written in pure shell script. It provides basic system details without any arguments or options. There are no ASCII graphics.

![screenshot](https://github.com/user-attachments/assets/2b92c4ed-e15a-4c56-856d-0b88832076e6)

## Installation

1. Make the script executable:

   ```bash
   chmod +x catfetch
   ```

2. Copy it to any directory in your `PATH`. The recommended location is `~/.local/bin`:

   ```bash
   cp catfetch ~/.local/bin/
   ```

3. Ensure the directory is in your `PATH`. If not, add the following to your shell configuration file:

   ```bash
   export PATH="$HOME/.local/bin:$PATH"
   ```

## Usage

Run:

```bash
catfetch
```

---

This project is licensed under [WTFPL](http://wtfpl.net "Do What the Fuck You Want to Public License").

This project follows the [HGG](https://catmeowbyte.github.io/heretic_git_guidelines "Heretic Git Guidelines").