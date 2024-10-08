# Shadow Library
```lua
local MobileLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/RFS-cmd/automatic-pancake/main/kinghenry.lua"))()

local Window = MobileLib:MakeWindow({
  Title = "shadow.cc free script",
  SubTitle = "",
  SaveFolder = ""
})
```
## Create Tab
```lua
local tab1 = Window:MakeTab({"Magnets", ""})
```
## Create Button
```lua
tab1:AddButton({"Button", function()
  print("test")
end})
```
## Create Toggle
```lua
local Toggle1 = tab1:AddToggle({
  Name = "Toggle 1",
  Description = "This is a <font color='rgb(88, 101, 242)'>Toggle</font> Example",
  Default = false
})
```
## Create Slider
```lua
tab1:AddSlider({
  Name = "Slider",
  Min = 1,
  Max = 10,
  Increase = 1,
  Default = 5,
  Callback = function(Value)
    
  end
})
```
## Create Dropdown
```lua
local Dropdown = Tab2:AddDropdown({
  Name = "Players List",
  Description = "Select the <font color='rgb(88, 101, 242)'>Number</font>",
  Options = {"one", "two", "three"},
  Default = "two",
  Flag = "dropdown teste",
  Callback = function(Value)
    
  end
})
```
## Create Paragraph
```lua
local Paragraph = tab1:AddParagraph({"Paragraph", "This is a Paragraph\nSecond Line"})
```
## Create Section
```lua
local sec1 = tab1:AddSection({"Section"})
```
