[img/lucide-logo]: repo-assets/lucide-logo.svg
[license]: https://github.com/latte-soft/lucide-roblox/blob/master/LICENSE.md

# [![Lucide Logo][img/lucide-logo]](https://lucide.dev) Lucide Icons Library for Roblox (Reborn)

Library to Use the Lucide Icon Set (<https://lucide.dev>) in Roblox.

This is reborn of old lucide-roblox by latte-soft

For now it's **uncompleted** and has only 1300/1694 icons

Built on Lucide v1.7

## If you want you can add support for it:

```lua
local Lucide = loadstring(game:HttpGet("https://raw.githubusercontent.com/Misharuz/lucide-roblox-reborn/refs/heads/main/lib.lua"))()
```

### How to use it:

There's two functions:

1. ```Lucide.GetIcon("name")```

Returns icon data as ```{IconName = "name", Id = 12345, Url = "rbxthumb://type=Asset&id=12345&w=420&h=420"}```

2. ```Lucide.Icon("name", size, overrides)```

Returns instance of ImageLabel, that is fully ready to use in your UI

## If you know any issue, please create [issue](https://lucide.dev](https://github.com/Misharuz/lucide-roblox-reborn/issues/new), this will help me so much
