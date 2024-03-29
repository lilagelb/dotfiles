# Dotfiles

A collection of my dotfiles so I can easily access them from anywhere.

# Prerequisites

This section lists any dependencies these configs may have, through things they require the system
to have at its disposal.

All configs, when applied together, require the following dependencies (beyond having the software they
configure installed):
- Cargo packages
  - sccache (`sccache`)
  - Starship prompt (`starship`)
- Misc
  - A Nerd Font installed in the terminal

Note that these are merely what the configs *actively* require beyond that of a basic install of the
software itself.

## Per-Config

### `bacon.toml`

Configures: `bacon`

Note that this has to be included in the directory of each individual project using Bacon as a testrunner.

### `.cargo/config.toml`

Configures: Cargo

Requires:
- `sccache` (via Cargo)

### `.config/helix/`

Configures: Helix editor

### `.config/neofetch/config.conf`

Configures: `neofetch`

### `.config/nushell/`

Configures: Nushell

Requires:
- Starship prompt (via cargo)

### `.config/starship.toml`

Configures: Starship prompt

Requires:
- An installed Nerd Font