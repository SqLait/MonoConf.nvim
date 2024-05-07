# MonoConf.nvim

![Logo](img/MonoConf.png)

MonoConf.nvim is a minimalist Neovim configuration designed to get you up and running quickly with essential plugins using [Lazy.nvim](https://github.com/folke/lazy.nvim) and a simple file structure. With MonoConf.nvim, you don't have to worry about setting up directories or managing plugins manually. It provides a basic foundation for your Neovim setup so you can focus on coding and adding plugins you would use.

## Features

- **Lazy Vim Integration**: MonoConf.nvim utilizes Lazy Vim, a plugin manager for Neovim, to handle plugin installation and management seamlessly.
- **Simple File Structure**: The configuration comes with a straightforward file structure, making it easy to navigate and customize according to your preferences.
- **Extremely bare bones**: No bullsh*t, just a package manager and a file structure, your config your rules!

## Getting Started

### Prerequisites

- Neovim >= 0.9.0 (needs to be built with LuaJIT)
- Git >= 2.19.0 (for partial clones support)
- a Nerd Font (optional, but needed to display some icons)
- a C compiler for nvim-treesitter and luasnip (preferably Gcc or MinGW)

### Installation

1. Clone MonoConf.nvim repository to your Neovim configuration directory (usually `~/.config/nvim`):
   
   Linux and Mac:
   ```bash
   git clone https://github.com/SqLait/MonoConf.nvim.git ~/.config/nvim
   ```
   Windows:
   ```bash
   git clone https://github.com/Sqlait/MonoConf.nvim $env:LOCALAPPDATA\nvim
   ```

3. Launch Neovim:

   ```bash
   nvim
   ```

4. Enjoy coding with MonoConf.nvim!

## File Structure

Here's a brief overview of the file structure of MonoConf.nvim:

```
.
└── nvim/           # Neovim configuration directory
    ├── init.lua    # Neovim file for referencing core and plugins
    └── lua/        # Lua configuration files
        └── mono/           # Mono configuration
            ├── core/           # Core functionality
            │   ├── init.lua    # Core initialization Lua file
            │   ├── keymaps.lua # Keymaps configuration Lua file
            │   └── options.lua # Options configuration Lua file
            └── plugins/        # Plugins configuration
                └── init.lua    # Plugins initialization Lua file
```

## Customization

Feel free to customize MonoConf.nvim to suit your preferences. You can add or remove plugins, tweak settings, and modify configurations according to your needs.

## Contributing

If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request. Your contributions are highly appreciated!

## License

MonoConf.nvim is licensed under the [Apache 2.0 license](LICENSE).
