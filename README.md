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
  telescope = { set_highlights = true }
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
  
  ![image](https://user-images.githubusercontent.com/110467150/208163876-8fb9a377-dab8-4abc-bd72-649507ac6625.png)
  ![image](https://user-images.githubusercontent.com/110467150/208164060-78c77efb-85fa-42a8-8f21-a72518b5f1b7.png)

</details>
