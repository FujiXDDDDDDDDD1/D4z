local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("D4z Hub", "Synapse")

local Tab = Window:NewTab("general")

local Section = Tab:NewSection("Settings")

Section:NewKeybind("Hide UI", "D4z Hub", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
