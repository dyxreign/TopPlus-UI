## TopUI Plus
idk, Someone asked for this, so I made a library. You can use it however you want, but please remember to give credits.

# Loadstring
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/dyxreign/TopPlus-UI/refs/heads/main/Source"))()
```

# Window
dont have others themes xddd

```lua
local Window = UI:CreateWindow({
    Title = "TopUIPlus",
    Author = "by nyx",
    Transparent = false,
    Theme = "Dark"
})
```

## Tab
```lua
local Tab = Window:Tab({
    Title = "Main",
    Icon = "home", 
    Height "250",
    Color = Color3.fromRGB(50, 150, 255)
})
```

## Button 
```lua
Tab:Button({
    Title = "Example",
    Desc = "desy",
    Callback = function()
        print("Hello World!")
    end
})
```

# Set a custom Font
```lua
UI:SetFont("rbxasset://...")
```

## Yes, I know there's almost nothing there, but I'll add more soon when I have time. You can create a modified version or something like that. I made this library quickly, So please excuse me if it looks bad.
