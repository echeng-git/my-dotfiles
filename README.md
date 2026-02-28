# my-dotfiles

> [!NOTE]
> Setup uses EndeavourOS on a Microsoft Surface Laptop 2 using the [linux-surface](https://github.com/linux-surface/linux-surface) kernel, but I am pretty sure that it shouldn't matter between distros.

My dotfiles that I'm constantly running (and changing as I go). I use [chezmoi](https://www.chezmoi.io/) to manage my dotfiles.

## Configuration

What I am using so far:

- **WM**: [niri](https://github.com/niri-wm/niri)
- **Desktop Shell**: [Noctalia](https://github.com/noctalia-dev/noctalia-shell)
  - I use [Hypridle](https://github.com/hyprwm/hypridle) to handle idle state
- **Editor**: [LazyVim](https://github.com/LazyVim/LazyVim) / Vim
- **File Manager**: [Yazi](https://github.com/sxyazi/yazi)
- **Terminal Emulator**: [Ghostty](https://github.com/ghostty-org/ghostty)
  - **Shell Prompt**: [oh-my-posh](https://github.com/jandedobbeleer/oh-my-posh) (using builtin config [`montys`](https://ohmyposh.dev/docs/themes#montys))
  - **Shader:** `cursor-warp` from [sahaj-b](https://github.com/sahaj-b/ghostty-cursor-shaders)
- **Font**:
  - **Monospace**: IosevkaTerm NerdFont Mono
  - **Regular**: Adwaita Sans

## Setup

```sh
chezmoi init --apply git@github.com:echeng-git/my-dotfiles.git
```

## Screenshots

![Desktop Setup](assets/example_screenshot.png) 
