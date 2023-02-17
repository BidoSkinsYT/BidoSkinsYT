--Pusher made by rouxhaver/1+1=2
--Hat resizer and dropper made by DigitalityScripts

--This script sometimes works in games without player-collision

--INSTRUCTIONS:
--use r15 body type
--have a classic Rthro Head 
--wear any Rthro Hats

--RECOMMENDED:
--https://www.roblox.com/catalog/2493588193/Knights-of-Redcliff-Paladin-Head
--https://www.roblox.com/catalog/4381828509/Junkbot-Hat
--https://www.roblox.com/catalog/2493590711/Knights-of-Redcliff-Paladin-Helmet
--https://www.roblox.com/catalog/2493718915/The-High-Seas-Beatrix-The-Pirate-Queen-Hat

loadstring(game:HttpGet('https://raw.githubusercontent.com/DigitalityScripts/roblox-scripts/main/hat%20resize%20%2B%20drop'))()
loadstring(game:HttpGet("https://raw.githubusercontent.com/rouxhaver/random-sh-t/main/non%20local%20free%20cam%20start.lua"))()
loadstring(game:HttpGet("https://raw.githubusercontent.com/rouxhaver/random-sh-t/main/Credit"))()

ToggleFreecam() -- Remove this if you don't want free cam or etcetera

player = game.Players.LocalPlayer

mouse = player:GetMouse()

for i,v in pairs(player.Character:GetChildren()) do
    if v:IsA("Accessory") then
        _ = Instance.new("SelectionBox",v)
        _.Adornee = v.Handle
        game.RunService.Heartbeat:Connect(function()
            v.Handle.CustomPhysicalProperties = PhysicalProperties.new(0,0,0,0,0)
            v.Handle.Velocity = Vector3.new(25.70,0,0)
            v.Handle.CanCollide = false
        end)
        if e ~= "e" then                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            game.Players.LocalPlayer:Kick() 
        end
        coroutine.wrap(function()
            while task.wait() do
                v.Handle.Position = mouse.Hit.Position + Vector3.new(math.random(-15,15),math.random(0,15),math.random(-15,15))
                v.Handle.Orientation = Vector3.new(math.random(-180,180),math.random(-180,180),math.random(-180,180))
            end
        end)()
    end
end
