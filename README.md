local Scriptispatched = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Closegui = Instance.new("TextButton")

Scriptispatched.Name = "Script is patched "
Scriptispatched.Parent = game.CoreGui
Scriptispatched.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Scriptispatched
Frame.BackgroundColor3 = Color3.fromRGB(61, 63, 63)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.329545438, 0, 0.33463034, 0)
Frame.Size = UDim2.new(0, 479, 0, 255)
Frame.Active = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.290187895, 0, 0.196078435, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "You are using a old version of the script join the discord server to get the newer one at"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.292275578, 0, 0.400000036, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "https://discord.gg/Txgm6P4q"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 14.000

Closegui.Name = "Close gui"
Closegui.Parent = Frame
Closegui.BackgroundColor3 = Color3.fromRGB(61, 63, 63)
Closegui.BorderSizePixel = 0
Closegui.Position = UDim2.new(0.895615876, 0, 0, 0)
Closegui.Size = UDim2.new(0, 50, 0, 50)
Closegui.Font = Enum.Font.SourceSans
Closegui.Text = "X"
Closegui.TextColor3 = Color3.fromRGB(0, 0, 0)
Closegui.TextSize = 14.000
Closegui.MouseButton1Down:connect (function()
	Frame.Visible = false
	print('Sorry')
end)
