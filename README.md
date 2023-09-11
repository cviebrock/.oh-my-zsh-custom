# Custom Oh-My-ZSH agnoster-like theme

## Installation

1. Install [oh my zsh](http://ohmyz.sh/) as per their instructions.

2. Clone this repo whereever you want:
    
    ```sh
    git clone https://github.com/empathystorm/agnoster-custom.git
    
    ```
3. Move zsh-theme file from repo to oh-my-zsh directory:
    
    ```sh
    mv agnoster-custom/cviebrock.zsh-theme ~/.oh-my-zsh/themes
    ```

4. Edit the following entry in your `~/.zshrc` file:
    
    ```
    ZSH_THEME="cviebrock"
    ```

5. Restart shell
    ```sh
    source ~/.zshrc
    ```

6. Enjoy!

## Features of the fork

- changed color sceme
- fixed appearing user@host prompt when entering 'su' or 'ssh'
- now in directory prompt displayed current and previous directory