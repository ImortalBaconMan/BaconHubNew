-- Gui to Lua
-- Version: 3.2

-- Instances:

local BaconHub = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Name = Instance.new("TextLabel")
local JailBreak = Instance.new("TextButton")
local AdoptMe = Instance.new("TextButton")
local BloxBurg = Instance.new("TextButton")
local SaberSim = Instance.new("TextButton")
local Mm2 = Instance.new("TextButton")
local SoulShatters = Instance.new("TextButton")
local RagdollEngine = Instance.new("TextButton")

--Properties:

BaconHub.Name = "BaconHub"
BaconHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
BaconHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = BaconHub
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(64, 170, 112)
Main.Position = UDim2.new(0.772874057, 0, 0.311023623, 0)
Main.Size = UDim2.new(0, 138, 0, 448)
Main.Draggable = true

Name.Name = "Name"
Name.Parent = Main
Name.BackgroundColor3 = Color3.fromRGB(64, 170, 112)
Name.Size = UDim2.new(0, 138, 0, 50)
Name.Font = Enum.Font.SourceSans
Name.Text = "Bacon Hub"
Name.TextColor3 = Color3.fromRGB(0, 0, 0)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true

JailBreak.Name = "JailBreak"
JailBreak.Parent = Main
JailBreak.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JailBreak.Position = UDim2.new(0.0507246368, 0, 0.178362548, 0)
JailBreak.Size = UDim2.new(0, 120, 0, 37)
JailBreak.Font = Enum.Font.SourceSans
JailBreak.Text = "JailBreak"
JailBreak.TextColor3 = Color3.fromRGB(0, 0, 0)
JailBreak.TextScaled = true
JailBreak.TextSize = 14.000
JailBreak.TextWrapped = true

AdoptMe.Name = "Adopt Me"
AdoptMe.Parent = Main
AdoptMe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AdoptMe.Position = UDim2.new(0.0652173907, 0, 0.303645372, 0)
AdoptMe.Size = UDim2.new(0, 120, 0, 38)
AdoptMe.Font = Enum.Font.SourceSans
AdoptMe.Text = "Adopt Me"
AdoptMe.TextColor3 = Color3.fromRGB(0, 0, 0)
AdoptMe.TextScaled = true
AdoptMe.TextSize = 14.000
AdoptMe.TextWrapped = true
AdoptMe.MouseButton1Down:connect(function()
loadstring(game:HttpGet("http://stockerperso.me/scripts/haxxme.lua", true))()
end)

BloxBurg.Name = "BloxBurg"
BloxBurg.Parent = Main
BloxBurg.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BloxBurg.Position = UDim2.new(0.0507246368, 0, 0.429909945, 0)
BloxBurg.Size = UDim2.new(0, 120, 0, 36)
BloxBurg.Font = Enum.Font.SourceSans
BloxBurg.Text = "BloxBurg"
BloxBurg.TextColor3 = Color3.fromRGB(0, 0, 0)
BloxBurg.TextScaled = true
BloxBurg.TextSize = 14.000
BloxBurg.TextWrapped = true
BloxBurg.MouseButton1Down:connect(function()
loadstring(game:HttpGet(('https://pastebin.com/raw/WzARP6mL'),true))()
end)

SaberSim.Name = "Saber Sim"
SaberSim.Parent = Main
SaberSim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SaberSim.Position = UDim2.new(0.0507246368, 0, 0.547893465, 0)
SaberSim.Size = UDim2.new(0, 120, 0, 38)
SaberSim.Font = Enum.Font.SourceSans
SaberSim.Text = "Saber Sim"
SaberSim.TextColor3 = Color3.fromRGB(0, 0, 0)
SaberSim.TextScaled = true
SaberSim.TextSize = 14.000
SaberSim.TextWrapped = true
BUTTONNAMEHERE.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/JQPzcZH4"))()
end)

Mm2.Name = "Mm2"
Mm2.Parent = Main
Mm2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Mm2.Position = UDim2.new(0.0652173907, 0, 0.666837454, 0)
Mm2.Size = UDim2.new(0, 120, 0, 39)
Mm2.Font = Enum.Font.SourceSans
Mm2.Text = "Mm2"
Mm2.TextColor3 = Color3.fromRGB(0, 0, 0)
Mm2.TextScaled = true
Mm2.TextSize = 14.000
Mm2.TextWrapped = true
Mm2.MouseButton1Down:connect(function()
loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

SoulShatters.Name = "SoulShatters"
SoulShatters.Parent = Main
SoulShatters.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SoulShatters.Position = UDim2.new(0.0785868764, 0, 0.782623887, 0)
SoulShatters.Size = UDim2.new(0, 118, 0, 41)
SoulShatters.Font = Enum.Font.SourceSans
SoulShatters.Text = "SoulShatters"
SoulShatters.TextColor3 = Color3.fromRGB(0, 0, 0)
SoulShatters.TextScaled = true
SoulShatters.TextSize = 14.000
SoulShatters.TextWrapped = true

RagdollEngine.Name = "Ragdoll Engine"
RagdollEngine.Parent = Main
RagdollEngine.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RagdollEngine.Position = UDim2.new(0.0823465958, 0, 0.903661191, 0)
RagdollEngine.Size = UDim2.new(0, 117, 0, 37)
RagdollEngine.Font = Enum.Font.SourceSans
RagdollEngine.Text = "Ragdoll Engine"
RagdollEngine.TextColor3 = Color3.fromRGB(0, 0, 0)
RagdollEngine.TextScaled = true
RagdollEngine.TextSize = 14.000
RagdollEngine.TextWrapped = true
RagdollEngine.MouseButton1Down:connect(function()
loadstring(game:HttpGet(('https://pastebin.com/raw/T7weKqag'),true))()
end)
