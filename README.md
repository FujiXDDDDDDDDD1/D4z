local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("D4z Hub", "Synapse")

local Tab = Window:NewTab("general")
local Section = Tab:NewSection("Build A Boat For Treasure")

Section:NewButton("Build A Boat For Treasure Hack", "D4z Hub", function()
    print("Siuu")
end)

local Section = Tab:NewSection("Settings")

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
