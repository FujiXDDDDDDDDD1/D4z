local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("D4z Hub", "Synapse")

local Tab = Window:NewTab("general")
local Section = Tab:NewSection("Funky Friday")

Section:NewButton("Funky Friday Hack", "D4z Hub", function()
    local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/wally-rblx/funky-friday-autoplay/main/main.lua",true))()
 local message = Instance.new("Message", workspace)
        message.Text = "Loaded! If the script is not working, press 'F9' to check for any errors."
        wait(4.5)
        message:Destroy()
end)

local Section = Tab:NewSection("ควย")

Section:NewButton("กด", "Siuu", function()
    getgenv().mainKey = "nil" local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)

local Section = Tab:NewSection("Settings")

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.M, function()
	Library:ToggleUI()
end)
