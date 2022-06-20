# zsh-pnpm

This plugin adds short aliases for the [`pnpm`](https://github.com/pnpm/pnpm) commands.

## Usage

Without typing full `pnpm` commands in console, like:

   ```zsh
   pnpm add --global some-package
   ```

there is more convenient alias:

   ```zsh
   pga some-package
   ```

## Installation

### Package

1. It is available on Homebrew. Run:

  ```
  brew install nekofar/tap/zsh-pnpm
  ```

2. Follow the post-install instructions logged to the terminal.


### Plugin
You can install it with a zsh plugin manager. Each has their own way of doing things. See your package manager's documentation.

#### zplug

1. Add the following to your `.zshrc`:

   ```zsh
   zplug "nekofar/zsh-pnpm"
   ```

2. Start a new terminal session.

#### Antigen

1. Add the following to your `.zshrc`:

   ```zsh
   antigen bundle nekofar/zsh-pnpm
   ```

2. Start a new terminal session.

#### Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

   ```zsh
   git clone https://github.com/nekofar/zsh-pnpm \
     ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-pnpm
   ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

   ```zsh
   plugins=( [plugins...] zsh-pnpm)
   ```

3. Start a new terminal session.

## Requirements

1. The pnpm tool has to be [installed](https://pnpm.io/installation) separately.
