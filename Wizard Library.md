# This is Wizard Ui Library 

## Booting the library
```lua
local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()
```

## Create Window
```lua
local Window = Library:NewWindow("Name")
```

## Create Tab
```lua
local Tab = Window:NewSection("My Tab")
```

## Create Button
```lua
Tab:CreateButton("Button", function()

print("hello")

end)
```

## Create Textbox
```lua
Tab:CreateTextbox("TextBox", function(text)

        print(text)

end)
```

## Create Dropdown
```lua
Tab:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)

print(text)

end)
```

## Create Slider
```lua
Tab:CreateSlider("Slider", 0, 100, 15, false, function(value)

print(value)

 end)
```

## Create Color Picker
```lua
Tab:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)

print(value)

end)
```

## Create Toggle
```lua
Tab:CreateToggle("Toggle", function(value)

print(value)

end)
```

# Thank You For Using Wizard Ui Library!
