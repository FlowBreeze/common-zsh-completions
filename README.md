common-zsh-completions
=============

**[zsh-completions](https://github.com/zsh-users/zsh-completions) with extra completion definitions.**

## Extra completions

- salt
- kubectl
- helm
- just
- [nb](https://github.com/xwmx/nb)

## Usage

### Using zsh frameworks

#### [zinit](https://github.com/zdharma-continuum/zinit)

Add below command to your `~/.zshrc`.
```
zinit wait lucid for \
    depth"1" \
    FlowBreeze/common-zsh-completions
```