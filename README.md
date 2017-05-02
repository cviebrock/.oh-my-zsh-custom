# Custom Oh-My-ZSH configuration and theme

This is a personal project to make it easy for me to set up my super-fancy
[oh my zsh](http://ohmyz.sh/) theme on any new server I deploy.


## Installation

1. Install [oh my zsh](http://ohmyz.sh/) as per their instructions.

2. Clone this repo into your home directory:

    ```sh
    cd ~
    git clone https://github.com/cviebrock/.oh-my-zsh-custom.git
    ```

3. Edit the following entries in your `~/.zshrc` file:

    ```
    ZSH_THEME="cviebrock"
    ZSH_CUSTOM=$HOME/.oh-my-zsh-custom
    ```

4. Log out and in again.

5. Enjoy!
