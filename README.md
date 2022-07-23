-- By erm#3134

local Novline = Instance.new("ScreenGui")
local GUI = Instance.new("Frame")
local Main = Instance.new("Frame")
local Combat = Instance.new("Frame")
local ButtonText = Instance.new("TextButton")
local Plus = Instance.new("TextButton")
local Blatant = Instance.new("Frame")
local ButtonText_2 = Instance.new("TextButton")
local Plus_2 = Instance.new("TextButton")
local World = Instance.new("Frame")
local ButtonText_3 = Instance.new("TextButton")
local Plus_3 = Instance.new("TextButton")
local Render = Instance.new("Frame")
local ButtonText_4 = Instance.new("TextButton")
local Plus_4 = Instance.new("TextButton")
local ImageButton = Instance.new("ImageButton")
local Top = Instance.new("Frame")
local Text = Instance.new("TextLabel")
local Blatant_2 = Instance.new("Frame")
local Main_2 = Instance.new("Frame")
local Top_2 = Instance.new("Frame")
local Blatant_3 = Instance.new("TextLabel")
local Combat_2 = Instance.new("Frame")
local Main_3 = Instance.new("Frame")
local Top_3 = Instance.new("Frame")
local Combat_3 = Instance.new("TextLabel")
local World_2 = Instance.new("Frame")
local Main_4 = Instance.new("Frame")
local Top_4 = Instance.new("Frame")
local World_3 = Instance.new("TextLabel")
local Render_2 = Instance.new("Frame")
local Main_5 = Instance.new("Frame")
local Top_5 = Instance.new("Frame")
local Render_3 = Instance.new("TextLabel")

--Properties:

Novline.Name = "Novline"
Novline.Parent = game.CoreGui
Novline.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Novline.Active = true
Novline.Draggable = true
GUI.Name = "GUI"
GUI.Parent = Novline
GUI.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GUI.BackgroundTransparency = 1.000
GUI.Position = UDim2.new(0.0120772943, 0, 0.0366088599, 0)
GUI.Size = UDim2.new(0, 156, 0, 278)

Main.Name = "Main"
Main.Parent = GUI
Main.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.0149572324, 0, 0.00679916283, 0)
Main.Size = UDim2.new(0, 156, 0, 300)

Combat.Name = "Combat"
Combat.Parent = Main
Combat.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Combat.BorderSizePixel = 0
Combat.Position = UDim2.new(0, 0, 0.19916068, 0)
Combat.Size = UDim2.new(0, 156, 0, 29)

ButtonText.Name = "Button/Text"
ButtonText.Parent = Combat
ButtonText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonText.BackgroundTransparency = 1.000
ButtonText.Size = UDim2.new(0, 143, 0, 29)
ButtonText.Font = Enum.Font.GothamBold
ButtonText.Text = "Combat"
ButtonText.TextColor3 = Color3.fromRGB(255, 255, 255)
ButtonText.TextScaled = true
ButtonText.TextSize = 14.000
ButtonText.TextWrapped = true

Plus.Name = "Plus"
Plus.Parent = Combat
Plus.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Plus.BackgroundTransparency = 1.000
Plus.Position = UDim2.new(0.858974338, 0, 0, 0)
Plus.Size = UDim2.new(0, 22, 0, 29)
Plus.Font = Enum.Font.GothamBold
Plus.Text = "+"
Plus.TextColor3 = Color3.fromRGB(255, 255, 255)
Plus.TextScaled = true
Plus.TextSize = 14.000
Plus.TextWrapped = true

Blatant.Name = "Blatant"
Blatant.Parent = Main
Blatant.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Blatant.BorderSizePixel = 0
Blatant.Position = UDim2.new(0, 0, 0.373141497, 0)
Blatant.Size = UDim2.new(0, 156, 0, 29)

ButtonText_2.Name = "Button/Text"
ButtonText_2.Parent = Blatant
ButtonText_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_2.BackgroundTransparency = 1.000
ButtonText_2.Size = UDim2.new(0, 143, 0, 29)
ButtonText_2.Font = Enum.Font.GothamBold
ButtonText_2.Text = "Blatant"
ButtonText_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_2.TextScaled = true
ButtonText_2.TextSize = 14.000
ButtonText_2.TextWrapped = true

Plus_2.Name = "Plus"
Plus_2.Parent = Blatant
Plus_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Plus_2.BackgroundTransparency = 1.000
Plus_2.Position = UDim2.new(0.858974338, 0, 0, 0)
Plus_2.Size = UDim2.new(0, 22, 0, 29)
Plus_2.Font = Enum.Font.GothamBold
Plus_2.Text = "+"
Plus_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Plus_2.TextScaled = true
Plus_2.TextSize = 14.000
Plus_2.TextWrapped = true

World.Name = "World"
World.Parent = Main
World.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
World.BorderSizePixel = 0
World.Position = UDim2.new(0, 0, 0.53791368, 0)
World.Size = UDim2.new(0, 156, 0, 29)

ButtonText_3.Name = "Button/Text"
ButtonText_3.Parent = World
ButtonText_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_3.BackgroundTransparency = 1.000
ButtonText_3.Size = UDim2.new(0, 143, 0, 29)
ButtonText_3.Font = Enum.Font.GothamBold
ButtonText_3.Text = "World"
ButtonText_3.TextColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_3.TextScaled = true
ButtonText_3.TextSize = 14.000
ButtonText_3.TextWrapped = true

Plus_3.Name = "Plus"
Plus_3.Parent = World
Plus_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Plus_3.BackgroundTransparency = 1.000
Plus_3.Position = UDim2.new(0.858974338, 0, 0, 0)
Plus_3.Size = UDim2.new(0, 22, 0, 29)
Plus_3.Font = Enum.Font.GothamBold
Plus_3.Text = "+"
Plus_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Plus_3.TextScaled = true
Plus_3.TextSize = 14.000
Plus_3.TextWrapped = true

Render.Name = "Render"
Render.Parent = Main
Render.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Render.BorderSizePixel = 0
Render.Position = UDim2.new(0, 0, 0.712422013, 0)
Render.Size = UDim2.new(0, 156, 0, 29)

ButtonText_4.Name = "Button/Text"
ButtonText_4.Parent = Render
ButtonText_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_4.BackgroundTransparency = 1.000
ButtonText_4.Size = UDim2.new(0, 143, 0, 29)
ButtonText_4.Font = Enum.Font.GothamBold
ButtonText_4.Text = "Render"
ButtonText_4.TextColor3 = Color3.fromRGB(255, 255, 255)
ButtonText_4.TextScaled = true
ButtonText_4.TextSize = 14.000
ButtonText_4.TextWrapped = true

Plus_4.Name = "Plus"
Plus_4.Parent = Render
Plus_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Plus_4.BackgroundTransparency = 1.000
Plus_4.Position = UDim2.new(0.858974338, 0, 0, 0)
Plus_4.Size = UDim2.new(0, 22, 0, 29)
Plus_4.Font = Enum.Font.GothamBold
Plus_4.Text = "+"
Plus_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Plus_4.TextScaled = true
Plus_4.TextSize = 14.000
Plus_4.TextWrapped = true

ImageButton.Parent = Main
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.858974338, 0, 0.926666558, 0)
ImageButton.Size = UDim2.new(0, 22, 0, 22)
ImageButton.Image = "rbxassetid://9753762469"

Top.Name = "Top"
Top.Parent = GUI
Top.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Top.BorderSizePixel = 0
Top.Position = UDim2.new(0.0149572603, 0, 0.00679918379, 0)
Top.Size = UDim2.new(0, 156, 0, 34)

Text.Name = "Text"
Text.Parent = Top
Text.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Text.BackgroundTransparency = 1.000
Text.Position = UDim2.new(0, 0, 0.117647059, 0)
Text.Size = UDim2.new(0, 156, 0, 28)
Text.Font = Enum.Font.GothamBold
Text.Text = "Novline"
Text.TextColor3 = Color3.fromRGB(255, 255, 255)
Text.TextScaled = true
Text.TextSize = 14.000
Text.TextWrapped = true

Blatant_2.Name = "Blatant"
Blatant_2.Parent = Novline
Blatant_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Blatant_2.BackgroundTransparency = 1.000
Blatant_2.Position = UDim2.new(0.423913032, 0, 0.0385356471, 0)
Blatant_2.Size = UDim2.new(0, 156, 0, 351)

Main_2.Name = "Main"
Main_2.Parent = Blatant_2
Main_2.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Main_2.BorderSizePixel = 0
Main_2.Position = UDim2.new(0.0149571346, 0, 0.00679916283, 0)
Main_2.Size = UDim2.new(0, 156, 0, 349)

Top_2.Name = "Top"
Top_2.Parent = Blatant_2
Top_2.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Top_2.BorderSizePixel = 0
Top_2.Position = UDim2.new(0.0149572603, 0, 0.00679918379, 0)
Top_2.Size = UDim2.new(0, 156, 0, 34)

Blatant_3.Name = "Blatant"
Blatant_3.Parent = Top_2
Blatant_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Blatant_3.BackgroundTransparency = 1.000
Blatant_3.Position = UDim2.new(0, 0, 0.117647059, 0)
Blatant_3.Size = UDim2.new(0, 156, 0, 28)
Blatant_3.Font = Enum.Font.GothamBold
Blatant_3.Text = "Blatant"
Blatant_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Blatant_3.TextScaled = true
Blatant_3.TextSize = 14.000
Blatant_3.TextWrapped = true

Combat_2.Name = "Combat"
Combat_2.Parent = Novline
Combat_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Combat_2.BackgroundTransparency = 1.000
Combat_2.Position = UDim2.new(0.219806761, 0, 0.0404624268, 0)
Combat_2.Size = UDim2.new(0, 156, 0, 148)

Main_3.Name = "Main"
Main_3.Parent = Combat_2
Main_3.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Main_3.BorderSizePixel = 0
Main_3.Position = UDim2.new(0.0149571346, 0, 0.00679916283, 0)
Main_3.Size = UDim2.new(0, 156, 0, 147)

Top_3.Name = "Top"
Top_3.Parent = Combat_2
Top_3.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Top_3.BorderSizePixel = 0
Top_3.Position = UDim2.new(0.0149572603, 0, 0.00679918379, 0)
Top_3.Size = UDim2.new(0, 156, 0, 34)

Combat_3.Name = "Combat"
Combat_3.Parent = Top_3
Combat_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Combat_3.BackgroundTransparency = 1.000
Combat_3.Position = UDim2.new(0, 0, 0.117647059, 0)
Combat_3.Size = UDim2.new(0, 156, 0, 28)
Combat_3.Font = Enum.Font.GothamBold
Combat_3.Text = "Combat"
Combat_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Combat_3.TextScaled = true
Combat_3.TextSize = 14.000
Combat_3.TextWrapped = true

World_2.Name = "World"
World_2.Parent = Novline
World_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
World_2.BackgroundTransparency = 1.000
World_2.Position = UDim2.new(0.628089368, 0, 0.0385356471, 0)
World_2.Size = UDim2.new(0, 156, 0, 201)

Main_4.Name = "Main"
Main_4.Parent = World_2
Main_4.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Main_4.BorderSizePixel = 0
Main_4.Position = UDim2.new(0.0149571346, 0, 0.00677104993, 0)
Main_4.Size = UDim2.new(0, 156, 0, 200)

Top_4.Name = "Top"
Top_4.Parent = World_2
Top_4.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Top_4.BorderSizePixel = 0
Top_4.Position = UDim2.new(0.0149572603, 0, 0.00679918379, 0)
Top_4.Size = UDim2.new(0, 156, 0, 34)

World_3.Name = "World"
World_3.Parent = Top_4
World_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
World_3.BackgroundTransparency = 1.000
World_3.Position = UDim2.new(0, 0, 0.117647059, 0)
World_3.Size = UDim2.new(0, 156, 0, 28)
World_3.Font = Enum.Font.GothamBold
World_3.Text = "World"
World_3.TextColor3 = Color3.fromRGB(255, 255, 255)
World_3.TextScaled = true
World_3.TextSize = 14.000
World_3.TextWrapped = true

Render_2.Name = "Render"
Render_2.Parent = Novline
Render_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Render_2.BackgroundTransparency = 1.000
Render_2.Position = UDim2.new(0.832937956, 0, 0.050096333, 0)
Render_2.Size = UDim2.new(0, 156, 0, 183)

Main_5.Name = "Main"
Main_5.Parent = Render_2
Main_5.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Main_5.BorderSizePixel = 0
Main_5.Position = UDim2.new(0.0149571346, 0, 0.00677095493, 0)
Main_5.Size = UDim2.new(0, 156, 0, 183)

Top_5.Name = "Top"
Top_5.Parent = Render_2
Top_5.BackgroundColor3 = Color3.fromRGB(157, 92, 255)
Top_5.BorderSizePixel = 0
Top_5.Position = UDim2.new(0.0149572603, 0, 0.00679918379, 0)
Top_5.Size = UDim2.new(0, 156, 0, 34)

Render_3.Name = "Render"
Render_3.Parent = Top_5
Render_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Render_3.BackgroundTransparency = 1.000
Render_3.Position = UDim2.new(0, 0, 0.117647059, 0)
Render_3.Size = UDim2.new(0, 156, 0, 28)
Render_3.Font = Enum.Font.GothamBold
Render_3.Text = "Render"
Render_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Render_3.TextScaled = true
Render_3.TextSize = 14.000
Render_3.TextWrapped = true

-- Scripts:

local function KBJL_fake_script() -- Novline.LocalScript 
	local script = Instance.new('LocalScript', Novline)

	local button = script.Parent
	local blureffect = game.StarterGui.Novline.Blur
	
	blureffect.Enabled = true 
end
coroutine.wrap(KBJL_fake_script)()
