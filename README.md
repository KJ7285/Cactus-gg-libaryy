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
Menu.CheckBox("Main", "Toggle, "Enabled", functionhere, function(state)
    print(state)
end)
```

textbox Idk how figure it out:
```lua
Menu.TextBox("Main", "textbox", "chnage here", "input", function(input)
    print(input)
end)
```

dropdown little broken:
```lua
local Settings = {
    SelectedHitPart = "Head"
}

local HitPartSection = Menu.Container("Main", "HitPart", "Left")

Menu.ComboBox(
    "Main",
    "HitPart",
    "BodyPart",
    "Body Part",
    {
        "Head", "UpperTorso", "LowerTorso", "HumanoidRootPart",
        "LeftUpperArm", "LeftLowerArm", "LeftHand",
        "RightUpperArm", "RightLowerArm", "RightHand",
        "LeftUpperLeg", "LeftLowerLeg", "LeftFoot",
        "RightUpperLeg", "RightLowerLeg", "RightFoot"
    },
    function(selection)
        Settings.SelectedHitPart = selection
    end
)
```
Slider:
```lua
Menu.Slider("HvH", "CSync", "Distance",
    0,
    20,
    0,
    1,
    function(namehere)
        print(namehere)
    end
)

--Note: You must create a tab for that slider and its container (aka section) 
```
