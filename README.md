# Work in progress

The plugin is working but expect breaking changes

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
  telescope = { set_highlights = true },
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

- telescope

  | horizontal                                                                                                       | vertical                                                                                                         |
  | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
  | ![image](https://user-images.githubusercontent.com/110467150/208234877-3732c2ea-4dd8-458f-9606-f4ae8074df76.png) | ![image](https://user-images.githubusercontent.com/110467150/208234896-50bdf098-c051-4fe8-93be-cd8a49042da1.png) |

</details>
