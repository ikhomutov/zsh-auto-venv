# zsh-auto-venv
Automatically activate venv when enter the project folder

## Installation

### [antigen](https://github.com/zsh-users/antigen)

1. Add the following to your `.zshrc`:

    ```sh
    antigen bundle ikhomutov/zsh-auto-venv
    ```

2. Start a new terminal session.

### [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh)

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/ikhomutov/zsh-auto-venv ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-auto-venv
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=(
      ...
      zsh-auto-venv
    )
    ```

3. Start a new terminal session.

### Manual (Git Clone)

1. Clone this repository somewhere on your machine. This guide will assume `~/.zsh/zsh-autosuggestions`.

    ```sh
    git clone https://github.com/ikhomutov/zsh-auto-venv ~/.zsh/zsh-auto-venv
    ```

2. Add the following to your `.zshrc`:

    ```sh
    source ~/.zsh/zsh-auto-venv/zsh-auto-venv.zsh
    ```

3. Start a new terminal session.
