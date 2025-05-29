to# Cactus-gg-libaryy
libary:

```lua
local Menu = loadstring(game:HttpGet("https://raw.githubusercontent.com/khenn791/library/refs/heads/main/cuh.txt",true))()
```



Set size of window:
```lua
Menu:SetSize(500, 400)
```
Tab:
```lua
local YournamehereTab = Menu.Tab("Main")
```
section:
```lua
local yournameofsectiongohereSection = Menu.Container("Main", "Target Aim", "Left"
```

checkbox toggle:
```lua
Menu.CheckBox("Main", "Target Aim", "Enabled", TargetAimEnabled, function(state)
    print(state)
end)
```
