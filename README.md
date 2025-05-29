Cactus-gg-libaryy
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
local NamegohereSection = Menu.Container("Main", "Test", "Left")

```

checkbox toggle:
```lua
Menu.CheckBox("Main", "Target Aim", "Enabled", functionhere, function(state)
    print(state)
end)
```

textbox Idk how figure it out:
```lua
Menu.TextBox("Main", "Target Aim", "X", "input", function(input)
    print(input)
end)
```
