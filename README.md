# Installation & usage

install:

```lua
lvim.plugins = {
  "LunarVim/lvim-themes",
}
```

call setup anywhere in your config.lua:

```lua
require("lvim-themes").setup {
  theme = "flat",
}
```

config options are different for each theme:

```lua
-- options for 'flat' theme
local flat = {
  telescope = { set_highlights = true },
}
```

# Available themes and screenshots

<details>
<summary>flat</summary>

- lsp
- telescope
- whichkey

</details>
