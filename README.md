local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("D4z Hub", "Synapse")

local Tab = Window:NewTab("general")
local Section = Tab:NewSection("Blox Fruits")

Section:NewButton("Blox Fruits Hack", "MUKURO", function()
    _G.Color = Color3.fromRGB(0, 255, 255)
_G.Toggle = Enum.KeyCode.RightControl
loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

Section:NewButton("Blox Fruits Get Chest Hack", "POWER X HUB", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/PowerxCANDYYY/NaMo/main/KingL.lua"), true))();
end)

local Section = Tab:NewSection("King Legacy")

Section:NewButton("King Legacy Hack", "MUKURO X QUARTYZ", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)

local Section = Tab:NewSection("All Star Tower Defense")

Section:NewButton("All Star Tower Defense Hack", "RIVER HUB", function()
    pcall(function()
        loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
     end)
end)

local Section = Tab:NewSection("Grand Piece Online")

Section:NewButton("Grand Piece Online Hack", "CFA HUB", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CFA-HUB/CFA-HUB/main/cfahubfree.lua"))()
end)

local Section = Tab:NewSection("Your Bizarre Adventure")

Section:NewButton("Your Bizarre Adventure Hack", "BITCH BOY V1", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/zakater5/LuaRepo/main/YBA/MainGui.lua"))()
end)

local Section = Tab:NewSection("Da Hood")

Section:NewButton("Da Hood Hack", "NOOB HUB", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NOOBHUBX/Da-hood/main/NOOB%20HUB.Lua'))()
end)

local Section = Tab:NewSection("Phantom Forces")

Section:NewButton("Phantom Forces Hack", "STRAWHOOK", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/VoidMasterX/strawhook/main/script.lua", true))()
end)

local Section = Tab:NewSection("Arsenal")

Section:NewButton("Arsenal Hack", "V.G HUB", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

local Section = Tab:NewSection("Mad City")

Section:NewButton("Mad City Hack", "Auto Farm", function()
    getgenv().doclub = false -- set to true if u wanna rob the club (can be buggy)
loadstring(game:HttpGet('https://raw.githubusercontent.com/Brizzy9999/scripts/main/madcityfarm.lua'))()
end)

Section:NewButton("Key : Frost_3596368", "Fu Kang", function()
end)

local Section = Tab:NewSection("Vehicle Legends")

Section:NewButton("Vehicle Legends Hack", "WHEEL HUB", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AaronS69420/WheelHub/main/MainFile", true))()
end)

Section:NewButton("Key : ohjxkfgcufuyfuytduyd", "Fu Kang", function()
end)

local Tab = Window:NewTab("Other")
local Section = Tab:NewSection("Natural Disaster Survival")

Section:NewButton("Natural Disaster Survival Teleport 1", "Fu Kang", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-284.619812, 194.09996, 326.953094, 0.452830076, -8.86669866e-08, -0.891596854, 3.79251155e-08, 1, -8.01857354e-08, 0.891596854, 2.49660137e-09, 0.452830076)
end)

Section:NewButton("Natural Disaster Survival Teleport 2", "Fu Kang", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-79.550827, 47.4999924, -0.644881904, 0.16489394, -1.1451017e-08, -0.986311316, 1.06218234e-08, 1, -9.83415926e-09, 0.986311316, -8.85483153e-09, 0.16489394)
end)

local Section = Tab:NewSection("JOJO kaoThapGG")

local Section = Tab:NewSection("City BanNa")

Section:NewButton("City BanNa Teleport 1", "Fu Kang", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-357.945129, 92.1009216, 528.69635, -0.999244392, -7.86113077e-08, -0.0388671644, -7.85326506e-08, 1, -3.5505725e-09, 0.0388671644, -4.9554838e-10, -0.999244392)
end)

Section:NewButton("City BanNa Teleport 2", "Fu Kang", function()
    local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(15, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(128.639404, 62.6451263, 805.712219, 0.912762284, -3.72950488e-08, -0.408491105, 5.50215624e-08, 1, 3.16446496e-08, 0.408491105, -5.13598621e-08, 0.912762284)}):Play()
end)

local Section = Tab:NewSection("Settings")

Section:NewKeybind("Hide UI", "D4z Hub", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
