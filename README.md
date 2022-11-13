	local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Bido Skins V1.0", "DarkTheme")
local Tab = Window:NewTab("Mean")
local MeanSection = Tab:NewSection("Fly")

MeanSection:NewButton("Fly", "Makes u fly", function()
--ARCEUS X FLY V2 SCRIPT BY RobloxDupeYT
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
    print ("Clicked")
end)

local MeanSection = Tab:NewSection("Antifling")
MeanSection:NewButton("Antifling", "Makes someone cant fling u", function()
loadstring(game:HttpGet('https://pastebin.com/raw/hKfDWcJw'))();
    print("Clicked")
end) 

local MeanSection = Tab:NewSection("AntiKick")
MeanSection:NewButton("AntiKick", "Makes u cant get kicked in experience", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/Cesare0328/my-scripts/main/joke%20anticheat.lua'),true))()
    print("Clicked")
end)


local Tab1 = Window:NewTab("Admins")
local AdminsSection = Tab1:NewSection("Infinte Yield")

AdminsSection:NewButton("infinte Yield", "Admin commands", function()
defaultsettings = {
	prefix = ';';
	StayOpen = false;
	keepIY = true;
	logsEnabled = false;
	jLogsEnabled = false;
	aliases = {};
	binds = {};
	WayPoints = {};
	PluginsTable = {};
}

defaults = game:GetService("HttpService"):JSONEncode(defaultsettings)

writefile("IY_FE.iy",defaults)


loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    print("Clicked")
end)


local Tab2 = Window:NewTab("Hubs")
local HubsSection = Tab2:NewSection("Zen Hub")

HubsSection:NewButton("Zen Hub", "Has Scripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/KaiZen/main/GameHub", true))()
    print("Clicked")
end)

local HubsSection = Tab2:NewSection("Ez Hub")
HubsSection:NewButton("Ez Hub", "has Scripts", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug420/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
    print("Clicked")
end)

local HubsSection = Tab2:NewSection("Arosia Hub")
HubsSection:NewButton("Arosia Hub", "Arosia Hub", function()
loadstring(Game:GetObjects("rbxassetid://1255908305")[1].Source)()
    print("Clicked")
end) 

local HubsSection = Tab2:NewSection("Domain Hub")
HubsSection:NewButton("Domain Hub", "has Scripts", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexsoftworks/Domain/main/source'),true))()

--key = 2r0jfvlnjtq7
print ("Clicked")
end)

local HubsSection = Tab2:NewSection("Era Hub")
HubsSection:NewButton("Era Hub", "has Scripts", function()
loadstring(game:HttpGet('https://pastebin.com/raw/zRWQnNjS'))()
print("clicked") 
end)

local HubsSection = Tab2:NewSection("Syntax Hub")
HubsSection:NewButton("Syntax Hub Key SyntaxV3Free", "has Scripts", function()
-- V3 Key is SyntaxV3Free --
shared.colors = {
    Icons = Color3.fromRGB(0,255,149),
    Version = Color3.fromRGB(0,255,149),
    Text = Color3.fromRGB(255,255,255),
    Description = Color3.fromRGB(125,125,125),
    TabList = Color3.fromRGB(30,30,30),
    Scripts = Color3.fromRGB(30,30,30),
    Back = Color3.fromRGB(25,25,25),
    Glow = Color3.fromRGB(0,0,0),
}
shared.transparency = {
    Version = 0,
    Text = 0,
    Description = 0,
    Icons = 0,
    Back = 0,
    Glow = 0.5,
    TabList = 0,
    Scripts = 1,
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/Memeboiyot/Syntax-V3-Free/main/Syntax%20v3", true))()
print ("clicked") 
end)

local HubsSection = Tab2:NewSection("British Hub")
HubsSection:NewButton("British Hub", "has Scripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/BH%20v2%20Protecc"))()
print ("Clicked") 
end)

