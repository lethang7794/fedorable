# Fedora Setup

## OS Settings

### Turn on Touchpad Tap to Click

Settings > Mouse & Touchpad > Touchpad > Clicking > Tap to Click > On

## Terminal

### Alacrity

### kitty

### Tmux

```shell
# ~/.tmux.conf
set -g mouse on
```

## Shell

### bash

### zsh

#### antidote: Install with brew

### fish

## Prompt

### starship

## CLI tools

```shell
DNF_PACKAGES=$(cat dnf-packages.txt | grep --invert-match "^\s*#")
sudo dnf install $DNF_PACKAGES
```

Check `dnf-packages.txt`

## Brew

```shell
BREW_PACKAGES=$(cat brew-packages.txt | grep --invert-match "^\s*#")
brew install $BREW_PACKAGES
```

## Volta

```
curl https://get.volta.sh | bash
```

Install with volta

```
node
pnpm
prettier
npkill
```
