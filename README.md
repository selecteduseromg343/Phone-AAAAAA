

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local slap = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local p = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")



ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
Main.Position = UDim2.new(0.619038045, 0, 0.474114716, 0)
Main.Size = UDim2.new(0, 235, 0, 262)
Main.Active = true
Main.Draggable = true

UICorner.Parent = Main

TextButton.Parent = UICorner
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.519464731, 0, 0.515873015, 0)
TextButton.Size = UDim2.new(0, 102, 0, 32)
TextButton.Font = Enum.Font.SourceSans
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
TextLabel.Position = UDim2.new(-0.00407325244, 0, -0.0036101595, 0)
TextLabel.Size = UDim2.new(0, 71, 0, 33)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Dark PhoneOs"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_2.Parent = TextLabel

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
TextLabel_2.Position = UDim2.new(0.920789421, 0, -0.00305407098, 0)
TextLabel_2.Size = UDim2.new(0, 17, 0, 15)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = ""
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

UICorner_3.Parent = TextLabel_2

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 101)
TextLabel_3.Position = UDim2.new(0.850923896, 0, -0.00305407122, 0)
TextLabel_3.Size = UDim2.new(0, 17, 0, 15)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = ""
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

UICorner_4.Parent = TextLabel_3

TextLabel_4.Parent = Main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(85, 170, 0)
TextLabel_4.Position = UDim2.new(0.77971673, 0, -0.00305407122, 0)
TextLabel_4.Size = UDim2.new(0, 17, 0, 15)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = ""
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000

UICorner_5.Parent = TextLabel_4

slap.Name = "slap"
slap.Parent = Main
slap.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
slap.Position = UDim2.new(0.0340425521, 0, 0.164122134, 0)
slap.Size = UDim2.new(0, 131, 0, 41)
slap.Font = Enum.Font.SourceSans
slap.Text = "SlapBattleGui"
slap.TextColor3 = Color3.fromRGB(0, 0, 0)
slap.TextSize = 14.000
slap.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

UICorner_6.Parent = slap

p.Name = "p"
p.Parent = Main
p.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
p.Position = UDim2.new(0.0340425521, 0, 0.419847339, 0)
p.Size = UDim2.new(0, 131, 0, 41)
p.Font = Enum.Font.SourceSans
p.Text = "print"
p.TextColor3 = Color3.fromRGB(0, 0, 0)
p.TextSize = 14.000
p.MouseButton1Down:connect(function()
	print("Loaded | Successfully! | darkhub Best!")
end)

UICorner_7.Parent = p
