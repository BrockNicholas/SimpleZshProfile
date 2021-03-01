# SimpleZshProfile
A very simple Zsh profile that sets the prompt to the current directory's name and demos some simple formatting.

### Directions
- Add `PROMPT='%F{240}%1~$%F{white} '` to ~/.zshrc file


#### Comments
- `%F{240}` and `%F{white}` set the gray and white colors
- `%1~` lists the current directory
- The remaining whitespace is a buffer. Feel free to swap it out for additional symbols or prompt expansion
