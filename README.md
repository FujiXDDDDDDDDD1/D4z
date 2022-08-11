local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("D4z Hub", "Synapse")

local Tab = Window:NewTab("MAIN")
local Section = Tab:NewSection("My Hello Kitty Cafe")

Section:NewButton("My Hello Kitty Cafe Hack", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/MyHelloKittyCafe.lua"))()
end)

local Section = Tab:NewSection("Driving Empire")

Section:NewButton("Driving Empire Hack", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/WindyKung/WindyWare/main/MainScript/DrivingEmpire.lua"))()
end)

local Section = Tab:NewSection("Clicker Simulator")

Section:NewButton("Clicker Simulator Hack", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/acezx-programer/ToolWare/main/OpenBeta/clicksim.lua"))
end)

local Section = Tab:NewSection("Settings")

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
