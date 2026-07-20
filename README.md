# yazi-config

This repository syncs personal [Yazi](https://yazi-rs.github.io/) file manager configurations.

## XDG Base Directory

Yazi follows the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/).
Configuration files are stored under `$XDG_CONFIG_HOME`, which defaults to `~/.config` when not explicitly set.

Yazi's local config path is therefore:

```
~/.config/yazi/
```

## Repository Structure

```
yazi-config/
├── yazi.toml       # General behavior settings
├── keymap.toml     # Key-binding overrides
└── theme.toml      # Color theme settings
```

### Files

| Path | Description |
|------|-------------|
| `yazi.toml` | General behavior settings used under `~/.config/yazi` |
| `keymap.toml` | Key-binding overrides used under `~/.config/yazi` |
| `theme.toml` | Color theme settings used under `~/.config/yazi` |

## Setup

```sh
# Clone the repo
git clone https://github.com/alexxyjiang/yazi-config.git ~/.config/yazi
```
