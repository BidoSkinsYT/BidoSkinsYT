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

local Tab3 = Window:NewTab("Games")
local GamesSection = Tab3:NewSection("Games")
GamesSection:NewButton("Lumber tycoon 2", "has Scripts", function()
--Made by noob_army discord https://discord.gg/WBqAUTXnvp
loadstring(game:HttpGet("https://raw.githubusercontent.com/NOOBARMYSCRIPTER/NOOBARMYSCRIPTER/main/AXE%20LOOP%20SCRIPT", true))();
print ("Clicked")
end)

GamesSection:NewButton("Build aboat for Treasure", "has Scripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()
print ("Clicked")
end)

GamesSection:NewButton("Lucky Blocks Battlegrounds", "has Scripts", function()
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
    vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    wait(1)
    vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
 
game.StarterGui:SetCore("SendNotification", {
    Title = "LUCKY BLOCKS Battlegrounds";
    Text = "Made by MaGiXx"; -- what the text says (ofc)
    Duration = 5;
})
wait(1)
game.StarterGui:SetCore("SendNotification", {
    Title = "Anti-Afk";
    Text = "Enabled!"; -- what the text says (ofc)
    Duration = 5;
})
 
local LuckyBlock = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local title = Instance.new("TextLabel")
local Frame_HUB = Instance.new("ImageLabel")
local HUB = Instance.new("TextLabel")
local Main = Instance.new("Frame")
local LuckyBlock_2 = Instance.new("TextButton")
local SuperBlock = Instance.new("TextButton")
local GalaxyBlock = Instance.new("TextButton")
local RainbowBlock = Instance.new("TextButton")
local DiamondBlock = Instance.new("TextButton")
local CopyDiscordServer = Instance.new("TextButton")
local DiscordServer_box = Instance.new("TextBox")
local lable_discord = Instance.new("TextLabel")
local open_box = Instance.new("TextBox")
local toBox = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local close = Instance.new("ImageButton")
 
--Properties:
 
LuckyBlock.Name = "LuckyBlock"
LuckyBlock.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
LuckyBlock.ResetOnSpawn = false
 
Frame.Name = "Frame"
Frame.Parent = LuckyBlock
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.ClipsDescendants = true
Frame.Position = UDim2.new(0.304542094, 0, 0.326781332, 0)
Frame.Size = UDim2.new(0, 525, 0, 300)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(0, 0, 0)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120
Frame.Active = true
Frame.Draggable = true
 
title.Name = "title"
title.Parent = Frame
title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
title.BackgroundTransparency = 1.000
title.Size = UDim2.new(0, 439, 0, 51)
title.Font = Enum.Font.SourceSans
title.Text = "LuckyBlock"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextSize = 28.000
 
Frame_HUB.Name = "Frame_HUB"
Frame_HUB.Parent = Frame
Frame_HUB.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_HUB.BackgroundTransparency = 1.000
Frame_HUB.BorderColor3 = Color3.fromRGB(255, 255, 255)
Frame_HUB.Position = UDim2.new(0.531428576, 0, 0.0277550742, 0)
Frame_HUB.Size = UDim2.new(0, 81, 0, 33)
Frame_HUB.Image = "rbxassetid://3570695787"
Frame_HUB.ImageColor3 = Color3.fromRGB(255, 170, 0)
Frame_HUB.ScaleType = Enum.ScaleType.Slice
Frame_HUB.SliceCenter = Rect.new(100, 100, 100, 100)
Frame_HUB.SliceScale = 0.120
 
HUB.Name = "HUB"
HUB.Parent = Frame_HUB
HUB.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HUB.BackgroundTransparency = 1.000
HUB.Position = UDim2.new(0, 0, -0.00494801067, 0)
HUB.Size = UDim2.new(0, 81, 0, 33)
HUB.Font = Enum.Font.SourceSans
HUB.Text = "HUB"
HUB.TextColor3 = Color3.fromRGB(0, 0, 0)
HUB.TextScaled = true
HUB.TextSize = 14.000
HUB.TextWrapped = true
 
Main.Name = "Main"
Main.Parent = Frame
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BorderColor3 = Color3.fromRGB(255, 255, 255)
Main.Position = UDim2.new(-0.034285713, 0, 0.170000002, 0)
Main.Size = UDim2.new(0, 559, 0, 0)
 
LuckyBlock_2.Name = "LuckyBlock"
LuckyBlock_2.Parent = Frame
LuckyBlock_2.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
LuckyBlock_2.BorderSizePixel = 0
LuckyBlock_2.Position = UDim2.new(0.0552380905, 0, 0.223333329, 0)
LuckyBlock_2.Selectable = false
LuckyBlock_2.Size = UDim2.new(0, 150, 0, 35)
LuckyBlock_2.AutoButtonColor = false
LuckyBlock_2.Font = Enum.Font.SourceSans
LuckyBlock_2.Text = "LuckyBlock"
LuckyBlock_2.TextColor3 = Color3.fromRGB(255, 255, 255)
LuckyBlock_2.TextSize = 28.000
 
SuperBlock.Name = "SuperBlock"
SuperBlock.Parent = Frame
SuperBlock.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SuperBlock.BorderSizePixel = 0
SuperBlock.Position = UDim2.new(0.0552381277, 0, 0.383333325, 0)
SuperBlock.Selectable = false
SuperBlock.Size = UDim2.new(0, 150, 0, 35)
SuperBlock.AutoButtonColor = false
SuperBlock.Font = Enum.Font.SourceSans
SuperBlock.Text = "SuperBlock"
SuperBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
SuperBlock.TextSize = 28.000
 
GalaxyBlock.Name = "GalaxyBlock"
GalaxyBlock.Parent = Frame
GalaxyBlock.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
GalaxyBlock.BorderSizePixel = 0
GalaxyBlock.Position = UDim2.new(0.0552381277, 0, 0.826666653, 0)
GalaxyBlock.Selectable = false
GalaxyBlock.Size = UDim2.new(0, 150, 0, 35)
GalaxyBlock.AutoButtonColor = false
GalaxyBlock.Font = Enum.Font.SourceSans
GalaxyBlock.Text = "GalaxyBlock"
GalaxyBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
GalaxyBlock.TextSize = 28.000
 
RainbowBlock.Name = "RainbowBlock"
RainbowBlock.Parent = Frame
RainbowBlock.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
RainbowBlock.BorderSizePixel = 0
RainbowBlock.Position = UDim2.new(0.0552381277, 0, 0.679999948, 0)
RainbowBlock.Selectable = false
RainbowBlock.Size = UDim2.new(0, 150, 0, 35)
RainbowBlock.AutoButtonColor = false
RainbowBlock.Font = Enum.Font.SourceSans
RainbowBlock.Text = "RainbowBlock"
RainbowBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
RainbowBlock.TextSize = 28.000
 
DiamondBlock.Name = "DiamondBlock"
DiamondBlock.Parent = Frame
DiamondBlock.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
DiamondBlock.BorderSizePixel = 0
DiamondBlock.Position = UDim2.new(0.0552381277, 0, 0.533333302, 0)
DiamondBlock.Selectable = false
DiamondBlock.Size = UDim2.new(0, 150, 0, 35)
DiamondBlock.AutoButtonColor = false
DiamondBlock.Font = Enum.Font.SourceSans
DiamondBlock.Text = "DiamondBlock"
DiamondBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
DiamondBlock.TextSize = 28.000
 
CopyDiscordServer.Name = "CopyDiscordServer"
CopyDiscordServer.Parent = Frame
CopyDiscordServer.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
CopyDiscordServer.BorderSizePixel = 0
CopyDiscordServer.Position = UDim2.new(0.531428576, 0, 0.826666713, 0)
CopyDiscordServer.Selectable = false
CopyDiscordServer.Size = UDim2.new(0, 194, 0, 35)
CopyDiscordServer.AutoButtonColor = false
CopyDiscordServer.Font = Enum.Font.SourceSans
CopyDiscordServer.Text = "CopyDiscordServer"
CopyDiscordServer.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyDiscordServer.TextSize = 28.000
 
DiscordServer_box.Name = "DiscordServer_box"
DiscordServer_box.Parent = Frame
DiscordServer_box.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
DiscordServer_box.BorderSizePixel = 0
DiscordServer_box.Position = UDim2.new(0.531428576, 0, 0.709999979, 0)
DiscordServer_box.Size = UDim2.new(0, 194, 0, 35)
DiscordServer_box.ClearTextOnFocus = false
DiscordServer_box.Font = Enum.Font.SourceSans
DiscordServer_box.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
DiscordServer_box.PlaceholderText = "https://discord.gg/TyUzMpMMUE"
DiscordServer_box.Text = "https://discord.gg/TyUzMpMMUE"
DiscordServer_box.TextColor3 = Color3.fromRGB(255, 255, 255)
DiscordServer_box.TextSize = 14.000
 
lable_discord.Name = "lable_discord"
lable_discord.Parent = Frame
lable_discord.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
lable_discord.BackgroundTransparency = 1.000
lable_discord.Position = UDim2.new(0.531428576, 0, 0.533333361, 0)
lable_discord.Size = UDim2.new(0, 194, 0, 53)
lable_discord.Font = Enum.Font.SourceSans
lable_discord.Text = "--You will find many other scripts in this discord server."
lable_discord.TextColor3 = Color3.fromRGB(0, 170, 0)
lable_discord.TextScaled = true
lable_discord.TextSize = 28.000
lable_discord.TextWrapped = true
 
open_box.Name = "open_box"
open_box.Parent = Frame
open_box.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
open_box.BorderSizePixel = 0
open_box.Position = UDim2.new(0.750476241, 0, 0.313333333, 0)
open_box.Size = UDim2.new(0, 56, 0, 35)
open_box.ClearTextOnFocus = false
open_box.Font = Enum.Font.SourceSans
open_box.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
open_box.PlaceholderText = "Value"
open_box.Text = "1"
open_box.TextColor3 = Color3.fromRGB(255, 255, 255)
open_box.TextSize = 28.000
open_box.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
 
toBox.Name = "toBox"
toBox.Parent = Frame
toBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
toBox.BackgroundTransparency = 1.000
toBox.Position = UDim2.new(0.531428635, 0, 0.286666691, 0)
toBox.Size = UDim2.new(0, 194, 0, 50)
toBox.Font = Enum.Font.SourceSans
toBox.Text = "0 to "
toBox.TextColor3 = Color3.fromRGB(255, 255, 255)
toBox.TextSize = 28.000
 
Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.Position = UDim2.new(0.400000006, 0, 0.170000002, 0)
Frame_2.Size = UDim2.new(0, 0, 0, 292)
 
close.Name = "close"
close.Parent = Frame
close.BackgroundTransparency = 1.000
close.Position = UDim2.new(0.90054822, 0, 0.00678133965, 0)
close.Size = UDim2.new(0, 45, 0, 45)
close.ZIndex = 2
close.Image = "rbxassetid://3926305904"
close.ImageRectOffset = Vector2.new(284, 4)
close.ImageRectSize = Vector2.new(24, 24)
 
 
----------------------------------------------------------------
 
close.MouseButton1Click:connect(function()
    Frame.Visible = false
end)
 
LuckyBlock_2.MouseButton1Click:connect(function()
    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)
        game.ReplicatedStorage.SpawnLuckyBlock:FireServer()
    end
end)
 
DiamondBlock.MouseButton1Click:connect(function()
    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)
        game.ReplicatedStorage.SpawnDiamondBlock:FireServer()
    end
end)
 
SuperBlock.MouseButton1Click:connect(function()
    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)
        game.ReplicatedStorage.SpawnSuperBlock:FireServer()
    end
end)
 
RainbowBlock.MouseButton1Click:connect(function()
    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)
        game.ReplicatedStorage.SpawnRainbowBlock:FireServer()
    end
end)
 
GalaxyBlock.MouseButton1Click:connect(function()
    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)
        game.ReplicatedStorage.SpawnGalaxyBlock:FireServer()
    end
end)
 
CopyDiscordServer.MouseButton1Down:connect(function()
    setclipboard("https://discord.gg/TyUzMpMMUE")
    wait(1)
    game.StarterGui:SetCore("SendNotification", {
        Title = "Success!";
        Text = "Copy Discord: https://discord.gg/TyUzMpMMUE"; -- what the text says (ofc)
        Duration = 5;
    })
end)
print ("Clicked")
end)

GamesSection:NewButton("Ro Ghoul", "has Scripts", function()
loadstring(game:HttpGet(("https://aizen.ml/weis/RoGhoul.lua")))()
print ("Clicked")
end)

GamesSection:NewButton("Brookhaven", "has Scripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
print ("Clicked")
end)
