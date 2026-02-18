# my-dotfiles

My own dotfiles that I am using (EndeavourOS, Microsoft Surface Laptop 2)

Still figuring things out as I go.

I use [chezmoi](https://www.chezmoi.io/) to manage my dotfiles.

## Configuration

What I am using so far:

- **WM**: [niri](https://github.com/niri-wm/niri)
- **Desktop Shell**: [Noctalia](https://github.com/noctalia-dev/noctalia-shell)
  - I use [Hypridle](https://github.com/hyprwm/hypridle) to handle idle state
- **Editor**: [LazyVim](https://github.com/LazyVim/LazyVim) / Vim
- **File Manager**: [Yazi](https://github.com/sxyazi/yazi)
- **Terminal Emulator**: [Ghostty](https://github.com/ghostty-org/ghostty)
  - **Shell Prompt**: [oh-my-posh](https://github.com/jandedobbeleer/oh-my-posh) (using builtin config `[montys](https://ohmyposh.dev/docs/themes#montys)`)

## Setup

```sh
chezmoi init --apply git@github.com:echeng-git/my-dotfiles.git
```
