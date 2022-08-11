local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("TITLE", "DarkTheme")

local Tab = Window:NewTab("MAIN")
local Section = Tab:NewSection("Driving Simulator")

Section:NewButton("My Hello Kitty Cafe", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/MyHelloKittyCafe.lua"))()
end)

local Section = Tab:NewSection("Driving Empire")

Section:NewButton("My Hello Kitty Cafe", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/WindyKung/WindyWare/main/MainScript/DrivingEmpire.lua"))()
end)

local Section = Tab:NewSection("Clicker Simulator")

Section:NewButton("My Hello Kitty Cafe", "D4z", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/acezx-programer/ToolWare/main/OpenBeta/clicksim.lua"))
end)

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
