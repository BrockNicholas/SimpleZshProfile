# SimpleZshProfile
A very simple Zsh profile that sets the prompt to the current directory's name.

### Directions
- Download brock.zsh-theme to ~/.oh-my-zsh/themes
- (Optional) Change the file name to [whatever-you-want].zsh-theme
- Open ~/.zshrc file and change ZSH_THEME to ZSH_THEME="brock" (or [whatever-you-want])
- Open your Zsh terminal application, and ta-dah!


#### Comments
- $fg[cyan] sets the color of the prompt
- %1~ lists the current directory. Remove the 1 to show the full PWD
- $fg[white] sets the color back to white for whatever you type
- The remaining whitespace is a buffer. Feel free to swap it out for a more traditional $ symbol, or chain additional symbols or prompt expansion
