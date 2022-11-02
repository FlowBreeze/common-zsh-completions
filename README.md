common-zsh-completions
=============

**[zsh-completions](https://github.com/zsh-users/zsh-completions) with extra completion definitions.**

## Extra completions

## Usage

### Using zsh frameworks

#### [zinit](https://github.com/zdharma-continuum/zinit)

Add below command to your `~/.zshrc`.
```
zinit wait lucid for \
    atpull'zinit creinstall -q .' \
    depth"1" \
    FlowBreeze/common-zsh-completions
```