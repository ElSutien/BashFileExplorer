# BashFileExplorer

TUI Bash application for making your Linux terminal into a file explorer for selecting files.

It can be useful for helping other applications when prompt the user to choose a file from filesystem, with a friendly user inteface that can be managed using arrows from the keyboard.


## Requirements

- Linux XTerm-compatible terminal emulator (or TTY)
- Bash shell >=4
- GNU coreutils


## Usage

- Use **up/down arrows** to move between files on the actual page.
- Use **left/right arrows** to change pages of the actual directory.
- **Enter** will open a directory or choose the selected file.
- **Backspace** will go to back directory.
- **Escape** will close the file explorer and return.
- **Spacebar** will print information about the selected file.


## ToDos

There are several ToDos that will be implemented.

- Possibility to select multiple files.
- Ask the user for exit when Esc is pressed.
- Show a help message then 'H' char is pressed.
- GoTo directory action.


## License
BashFileExplorer is licensed under the [MIT License](LICENSE.md)