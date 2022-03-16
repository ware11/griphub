-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner1 = Instance.new("UICorner")
local orange3 = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local TextLabel = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local UICorner = Instance.new("UICorner")
local orange3_2 = Instance.new("Frame")
local UIGradient_2 = Instance.new("UIGradient")
local TextButton = Instance.new("TextButton")
local orange3_3 = Instance.new("Frame")
local UIGradient_3 = Instance.new("UIGradient")
local UICorner_2 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = true

Frame.Parent = ScreenGui
Frame.Active = true
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
Frame.BorderColor3 = Color3.fromRGB(255, 145, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.5, 131, 0.564318538, -115)
Frame.Selectable = true
Frame.Draggable = true
Frame.Size = UDim2.new(0, 429, 0, 250)

UICorner1.Name = "UICorner1"
UICorner1.Parent = Frame

orange3.Name = "orange3"
orange3.Parent = Frame
orange3.Active = true
orange3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
orange3.BorderSizePixel = 0
orange3.ClipsDescendants = true
orange3.Selectable = true
orange3.Size = UDim2.new(0, 429, 0, 12)

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
UIGradient.Parent = orange3

TextLabel.Parent = orange3
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(0, 429, 0, 12)
TextLabel.Font = Enum.Font.Code
TextLabel.Text = "griphub_ss key system"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 19.000
TextLabel.TextWrapped = true

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
TextBox.Position = UDim2.new(0, 122, 0, 45)
TextBox.Size = UDim2.new(0, 200, 0, 50)
TextBox.Font = Enum.Font.Code
TextBox.Text = "key here {}"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 14.000

UICorner.CornerRadius = UDim.new(0, 3)
UICorner.Parent = TextBox

orange3_2.Name = "orange3"
orange3_2.Parent = TextBox
orange3_2.Active = true
orange3_2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
orange3_2.BorderSizePixel = 0
orange3_2.ClipsDescendants = true
orange3_2.Selectable = true
orange3_2.Size = UDim2.new(0, 200, 0, 2)

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
UIGradient_2.Parent = orange3_2

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
TextButton.Position = UDim2.new(0, 122, 0, 150)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.Code
TextButton.Text = "gain access"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

orange3_3.Name = "orange3"
orange3_3.Parent = TextButton
orange3_3.Active = true
orange3_3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
orange3_3.BorderSizePixel = 0
orange3_3.ClipsDescendants = true
orange3_3.Selectable = true
orange3_3.Size = UDim2.new(0, 200, 0, 2)

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
UIGradient_3.Parent = orange3_3

UICorner_2.CornerRadius = UDim.new(0, 3)
UICorner_2.Parent = TextButton

-- Scripts:

local function JKYNEI_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.TextBox.Text == "01101011-01100101-01111001" then
			script.Parent.Parent.Parent.Enabled = false
	
	
	
	
			-- Gui to Lua
			-- Version: 3.2
	
			-- Instances:
	
			local congui2 = Instance.new("ScreenGui")
			local Frame1 = Instance.new("Frame")
			local UICorner1 = Instance.new("UICorner")
			local UIGradient1 = Instance.new("UIGradient")
			local Fram2 = Instance.new("Frame")
			local UIGradient = Instance.new("UIGradient")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local TextLabel_3 = Instance.new("TextLabel")
			local TextButton = Instance.new("TextButton")
			local orange1 = Instance.new("Frame")
			local UIGradient_2 = Instance.new("UIGradient")
	
			--Properties:
	
			congui2.Name = "congui2"
			congui2.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
			congui2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
			congui2.ResetOnSpawn=true
	
			Frame1.Name = "Frame1"
			Frame1.Parent = congui2
			Frame1.Active = true
			Frame1.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
			Frame1.ClipsDescendants = true
			Frame1.Position = UDim2.new(0, 755, 0, 255)
			Frame1.Selectable = true
			Frame1.Draggable = true
			Frame1.Size = UDim2.new(0, 555, 0, 255)
	
			UICorner1.Name = "UICorner1"
			UICorner1.Parent = Frame1
	
			UIGradient1.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(134, 134, 134)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(134, 134, 134))}
			UIGradient1.Name = "UIGradient1"
			UIGradient1.Parent = Frame1
	
			Fram2.Name = "Fram2"
			Fram2.Parent = Frame1
			Fram2.Active = true
			Fram2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
			Fram2.BorderSizePixel = 0
			Fram2.ClipsDescendants = true
			Fram2.Selectable = true
			Fram2.Size = UDim2.new(0, 555, 0, 22)
	
			UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
			UIGradient.Parent = Fram2
	
			TextLabel.Parent = Frame1
			TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel.BackgroundTransparency = 1.000
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(0, 180, 0, -15)
			TextLabel.Size = UDim2.new(0, 200, 0, 50)
			TextLabel.Font = Enum.Font.RobotoMono
			TextLabel.Text = "griphub_ss loader [2]"
			TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel.TextSize = 19.000
			TextLabel.TextWrapped = true
	
			TextLabel_2.Parent = Frame1
			TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_2.BackgroundTransparency = 1.000
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(0, 180, 0, 25)
			TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
			TextLabel_2.Font = Enum.Font.RobotoMono
			TextLabel_2.Text = "click 'continue' to load griphub_ss "
			TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_2.TextSize = 20.000
			TextLabel_2.TextStrokeColor3 = Color3.fromRGB(255, 136, 0)
			TextLabel_2.TextWrapped = true
	
			TextLabel_3.Parent = Frame1
			TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_3.BackgroundTransparency = 1.000
			TextLabel_3.BorderSizePixel = 0
			TextLabel_3.Position = UDim2.new(0, 100, 0, 55)
			TextLabel_3.Size = UDim2.new(0, 355, 0, 99)
			TextLabel_3.Font = Enum.Font.RobotoMono
			TextLabel_3.Text = "VERSION: [2]"
			TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_3.TextSize = 25.000
			TextLabel_3.TextStrokeColor3 = Color3.fromRGB(255, 136, 0)
			TextLabel_3.TextWrapped = true
	
			TextButton.Parent = Frame1
			TextButton.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
			TextButton.Position = UDim2.new(0, 180, 0, 165)
			TextButton.Size = UDim2.new(0, 200, 0, 50)
			TextButton.Font = Enum.Font.RobotoMono
			TextButton.Text = "continue"
			TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextButton.TextSize = 52.000
			TextButton.TextWrapped = true
			TextButton.MouseButton1Down:connect(function()
	
				--
	
				-- Gui to Lua
				-- Version: 3.2
	
				-- Instances:
	
				local griphub_ss = Instance.new("ScreenGui")
				local mainframe = Instance.new("Frame")
				local UICorner1 = Instance.new("UICorner")
				local UIGradient1 = Instance.new("UIGradient")
				local orange1 = Instance.new("Frame")
				local UIGradient = Instance.new("UIGradient")
				local TextLabel = Instance.new("TextLabel")
				local grippos = Instance.new("Frame")
				local lowholds = Instance.new("TextButton")
				local UICorner2 = Instance.new("UICorner")
				local UIGradient2 = Instance.new("UIGradient")
				local Frame3 = Instance.new("Frame")
				local UIGradient3 = Instance.new("UIGradient")
				local lowholds_2 = Instance.new("TextButton")
				local UICorner2_2 = Instance.new("UICorner")
				local UIGradient2_2 = Instance.new("UIGradient")
				local Frame3_2 = Instance.new("Frame")
				local UIGradient3_2 = Instance.new("UIGradient")
				local guns = Instance.new("TextButton")
				local UICorner2_3 = Instance.new("UICorner")
				local UIGradient2_3 = Instance.new("UIGradient")
				local Frame3_3 = Instance.new("Frame")
				local UIGradient3_3 = Instance.new("UIGradient")
				local guns_2 = Instance.new("TextButton")
				local UICorner2_4 = Instance.new("UICorner")
				local UIGradient2_4 = Instance.new("UIGradient")
				local Frame3_4 = Instance.new("Frame")
				local UIGradient3_4 = Instance.new("UIGradient")
				local shoulders = Instance.new("TextButton")
				local UICorner2_5 = Instance.new("UICorner")
				local UIGradient2_5 = Instance.new("UIGradient")
				local Frame3_5 = Instance.new("Frame")
				local UIGradient3_5 = Instance.new("UIGradient")
				local shoulders_2 = Instance.new("TextButton")
				local UICorner2_6 = Instance.new("UICorner")
				local UIGradient2_6 = Instance.new("UIGradient")
				local Frame3_6 = Instance.new("Frame")
				local UIGradient3_6 = Instance.new("UIGradient")
				local cock = Instance.new("TextButton")
				local UICorner2_7 = Instance.new("UICorner")
				local UIGradient2_7 = Instance.new("UIGradient")
				local Frame3_7 = Instance.new("Frame")
				local UIGradient3_7 = Instance.new("UIGradient")
				local backpack = Instance.new("TextButton")
				local UICorner2_8 = Instance.new("UICorner")
				local UIGradient2_8 = Instance.new("UIGradient")
				local Frame3_8 = Instance.new("Frame")
				local UIGradient3_8 = Instance.new("UIGradient")
				local orange3 = Instance.new("Frame")
				local UIGradient_2 = Instance.new("UIGradient")
				local UICorner = Instance.new("UICorner")
				local TextLabel_2 = Instance.new("TextLabel")
				local orange2 = Instance.new("Frame")
				local UIGradient_3 = Instance.new("UIGradient")
				local UICorner_2 = Instance.new("UICorner")
				local TextLabel_3 = Instance.new("TextLabel")
				local others = Instance.new("Frame")
				local others_2 = Instance.new("TextButton")
				local UICorner2_9 = Instance.new("UICorner")
				local UIGradient2_9 = Instance.new("UIGradient")
				local Frame3_9 = Instance.new("Frame")
				local UIGradient3_9 = Instance.new("UIGradient")
				local others_3 = Instance.new("TextButton")
				local UICorner2_10 = Instance.new("UICorner")
				local UIGradient2_10 = Instance.new("UIGradient")
				local Frame3_10 = Instance.new("Frame")
				local UIGradient3_10 = Instance.new("UIGradient")
				local creditsandinfo = Instance.new("Frame")
				local UICorner_3 = Instance.new("UICorner")
				local TextLabel_4 = Instance.new("TextLabel")
				local UIGradient_4 = Instance.new("UIGradient")
				local creditsandinfo_2 = Instance.new("Frame")
				local orange2_2 = Instance.new("Frame")
				local UIGradient_5 = Instance.new("UIGradient")
				local UICorner_4 = Instance.new("UICorner")
				local TextLabel_5 = Instance.new("TextLabel")
				local TextLabel_6 = Instance.new("TextLabel")
				local TextLabel_7 = Instance.new("TextLabel")
				local TextLabel_8 = Instance.new("TextLabel")
				local TextLabel_9 = Instance.new("TextLabel")
	
				--Properties:
	
				griphub_ss.Name = "griphub_ss"
				griphub_ss.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
				griphub_ss.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
				griphub_ss.ResetOnSpawn=false
	
				mainframe.Name = "mainframe"
				mainframe.Parent = griphub_ss
				mainframe.Active = true
				mainframe.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				mainframe.ClipsDescendants = true
				mainframe.Position = UDim2.new(0, 299, 0, 199)
				mainframe.Selectable = true
				mainframe.Draggable = true
				mainframe.Size = UDim2.new(0, 999, 0, 400)
	
				UICorner1.Name = "UICorner1"
				UICorner1.Parent = mainframe
	
				UIGradient1.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(134, 134, 134)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(134, 134, 134))}
				UIGradient1.Name = "UIGradient1"
				UIGradient1.Parent = mainframe
	
				orange1.Name = "orange1"
				orange1.Parent = mainframe
				orange1.Active = true
				orange1.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				orange1.BorderSizePixel = 0
				orange1.ClipsDescendants = true
				orange1.Selectable = true
				orange1.Size = UDim2.new(0, 999, 0, 22)
	
				UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient.Parent = orange1
	
				TextLabel.Parent = mainframe
				TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel.BackgroundTransparency = 1.000
				TextLabel.BorderSizePixel = 0
				TextLabel.Position = UDim2.new(0, 400, 0, -15)
				TextLabel.Size = UDim2.new(0, 200, 0, 50)
				TextLabel.Font = Enum.Font.RobotoMono
				TextLabel.Text = "griphub_ss "
				TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel.TextSize = 22.000
	
				grippos.Name = "grippos"
				grippos.Parent = mainframe
				grippos.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				grippos.BackgroundTransparency = 1.000
				grippos.Position = UDim2.new(0, -66, 0, 15)
				grippos.Size = UDim2.new(0, 100, 0, 100)
	
				lowholds.Name = "lowholds"
				lowholds.Parent = grippos
				lowholds.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				lowholds.Position = UDim2.new(0, 99, 0, 39)
				lowholds.Size = UDim2.new(0, 200, 0, 50)
				lowholds.Font = Enum.Font.RobotoMono
				lowholds.Text = "lowhold {v1}"
				lowholds.TextColor3 = Color3.fromRGB(0, 0, 0)
				lowholds.TextScaled = true
				lowholds.TextSize = 51.000
				lowholds.TextWrapped = true
				lowholds.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0, -1, -0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.007, 0.737, 0.091)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.024, 0, 1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(1, -0, 0.024)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:Stop()
					end
				end)
	
				UICorner2.CornerRadius = UDim.new(0, 2)
				UICorner2.Name = "UICorner2"
				UICorner2.Parent = lowholds
	
				UIGradient2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2.Name = "UIGradient2"
				UIGradient2.Parent = lowholds
	
				Frame3.Name = "Frame3"
				Frame3.Parent = lowholds
				Frame3.Active = true
				Frame3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3.BorderSizePixel = 0
				Frame3.ClipsDescendants = true
				Frame3.Selectable = true
				Frame3.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3.Name = "UIGradient3"
				UIGradient3.Parent = Frame3
	
				lowholds_2.Name = "lowholds"
				lowholds_2.Parent = grippos
				lowholds_2.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				lowholds_2.Position = UDim2.new(0, 99, 0, 123)
				lowholds_2.Size = UDim2.new(0, 200, 0, 50)
				lowholds_2.Font = Enum.Font.RobotoMono
				lowholds_2.Text = "lowhold {v2}"
				lowholds_2.TextColor3 = Color3.fromRGB(0, 0, 0)
				lowholds_2.TextScaled = true
				lowholds_2.TextSize = 51.000
				lowholds_2.TextWrapped = true
				lowholds_2.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0, -1, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.007, 0.737, -0.091)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.024, 0, -1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, -0, -0.024)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:Stop()
					end
				end)
	
				UICorner2_2.CornerRadius = UDim.new(0, 2)
				UICorner2_2.Name = "UICorner2"
				UICorner2_2.Parent = lowholds_2
	
				UIGradient2_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_2.Name = "UIGradient2"
				UIGradient2_2.Parent = lowholds_2
	
				Frame3_2.Name = "Frame3"
				Frame3_2.Parent = lowholds_2
				Frame3_2.Active = true
				Frame3_2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_2.BorderSizePixel = 0
				Frame3_2.ClipsDescendants = true
				Frame3_2.Selectable = true
				Frame3_2.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_2.Name = "UIGradient3"
				UIGradient3_2.Parent = Frame3_2
	
				guns.Name = "guns"
				guns.Parent = grippos
				guns.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				guns.Position = UDim2.new(0, 99, 0, 220)
				guns.Size = UDim2.new(0, 200, 0, 50)
				guns.Font = Enum.Font.RobotoMono
				guns.Text = "gun {v1}"
				guns.TextColor3 = Color3.fromRGB(0, 0, 0)
				guns.TextScaled = true
				guns.TextSize = 51.000
				guns.TextWrapped = true
				guns.MouseButton1Down:connect(function()
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-1, -0, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.767, -0.793, 0.07)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0, -0.012, -1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0, 1, -0.012)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:play()
					end
				end)
	
				UICorner2_3.CornerRadius = UDim.new(0, 2)
				UICorner2_3.Name = "UICorner2"
				UICorner2_3.Parent = guns
	
				UIGradient2_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_3.Name = "UIGradient2"
				UIGradient2_3.Parent = guns
	
				Frame3_3.Name = "Frame3"
				Frame3_3.Parent = guns
				Frame3_3.Active = true
				Frame3_3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_3.BorderSizePixel = 0
				Frame3_3.ClipsDescendants = true
				Frame3_3.Selectable = true
				Frame3_3.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_3.Name = "UIGradient3"
				UIGradient3_3.Parent = Frame3_3
	
				guns_2.Name = "guns"
				guns_2.Parent = grippos
				guns_2.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				guns_2.Position = UDim2.new(0, 99, 0, 320)
				guns_2.Size = UDim2.new(0, 200, 0, 50)
				guns_2.Font = Enum.Font.RobotoMono
				guns_2.Text = "gun {v2}"
				guns_2.TextColor3 = Color3.fromRGB(0, 0, 0)
				guns_2.TextScaled = true
				guns_2.TextSize = 51.000
				guns_2.TextWrapped = true
				guns_2.MouseButton1Down:connect(function()
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-1, 0, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.767, -0.785, -0.111)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0, -0.605, -0.797)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0, 0.797, -0.605)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:play()
					end
				end)
				UICorner2_4.CornerRadius = UDim.new(0, 2)
				UICorner2_4.Name = "UICorner2"
				UICorner2_4.Parent = guns_2
	
				UIGradient2_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_4.Name = "UIGradient2"
				UIGradient2_4.Parent = guns_2
	
				Frame3_4.Name = "Frame3"
				Frame3_4.Parent = guns_2
				Frame3_4.Active = true
				Frame3_4.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_4.BorderSizePixel = 0
				Frame3_4.ClipsDescendants = true
				Frame3_4.Selectable = true
				Frame3_4.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_4.Name = "UIGradient3"
				UIGradient3_4.Parent = Frame3_4
	
				shoulders.Name = "shoulders"
				shoulders.Parent = grippos
				shoulders.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				shoulders.Position = UDim2.new(0, 315, 0, 39)
				shoulders.Size = UDim2.new(0, 200, 0, 50)
				shoulders.Font = Enum.Font.RobotoMono
				shoulders.Text = "shoulder"
				shoulders.TextColor3 = Color3.fromRGB(0, 0, 0)
				shoulders.TextScaled = true
				shoulders.TextSize = 51.000
				shoulders.TextWrapped = true
				shoulders.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0, -1, -0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.025, -2.86, 0.201)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.221, -0, 0.975)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.975, 0, -0.221)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:Stop()
					end
				end)
				UICorner2_5.CornerRadius = UDim.new(0, 2)
				UICorner2_5.Name = "UICorner2"
				UICorner2_5.Parent = shoulders
	
				UIGradient2_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_5.Name = "UIGradient2"
				UIGradient2_5.Parent = shoulders
	
				Frame3_5.Name = "Frame3"
				Frame3_5.Parent = shoulders
				Frame3_5.Active = true
				Frame3_5.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_5.BorderSizePixel = 0
				Frame3_5.ClipsDescendants = true
				Frame3_5.Selectable = true
				Frame3_5.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_5.Name = "UIGradient3"
				UIGradient3_5.Parent = Frame3_5
	
				shoulders_2.Name = "shoulders"
				shoulders_2.Parent = grippos
				shoulders_2.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				shoulders_2.Position = UDim2.new(0, 315, 0, 123)
				shoulders_2.Size = UDim2.new(0, 200, 0, 50)
				shoulders_2.Font = Enum.Font.RobotoMono
				shoulders_2.Text = "shoulder {v2}"
				shoulders_2.TextColor3 = Color3.fromRGB(0, 0, 0)
				shoulders_2.TextScaled = true
				shoulders_2.TextSize = 51.000
				shoulders_2.TextWrapped = true
				shoulders_2.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0, -1, -0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.026, -2.844, 0.091)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.028, -0, 1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(1, 0, -0.028)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:Stop()
					end
				end)
	
				UICorner2_6.CornerRadius = UDim.new(0, 2)
				UICorner2_6.Name = "UICorner2"
				UICorner2_6.Parent = shoulders_2
	
				UIGradient2_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_6.Name = "UIGradient2"
				UIGradient2_6.Parent = shoulders_2
	
				Frame3_6.Name = "Frame3"
				Frame3_6.Parent = shoulders_2
				Frame3_6.Active = true
				Frame3_6.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_6.BorderSizePixel = 0
				Frame3_6.ClipsDescendants = true
				Frame3_6.Selectable = true
				Frame3_6.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_6.Name = "UIGradient3"
				UIGradient3_6.Parent = Frame3_6
	
				cock.Name = "cock"
				cock.Parent = grippos
				cock.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				cock.Position = UDim2.new(0, 315, 0, 220)
				cock.Size = UDim2.new(0, 200, 0, 50)
				cock.Font = Enum.Font.RobotoMono
				cock.Text = "boner"
				cock.TextColor3 = Color3.fromRGB(0, 0, 0)
				cock.TextScaled = true
				cock.TextSize = 51.000
				cock.TextWrapped = true
				cock.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-1, 0, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.362, 1.16, -1.424)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0, -0.024, -1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0, 1, -0.024)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:play()
					end
				end)
				UICorner2_7.CornerRadius = UDim.new(0, 2)
				UICorner2_7.Name = "UICorner2"
				UICorner2_7.Parent = cock
	
				UIGradient2_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_7.Name = "UIGradient2"
				UIGradient2_7.Parent = cock
	
				Frame3_7.Name = "Frame3"
				Frame3_7.Parent = cock
				Frame3_7.Active = true
				Frame3_7.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_7.BorderSizePixel = 0
				Frame3_7.ClipsDescendants = true
				Frame3_7.Selectable = true
				Frame3_7.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_7.Name = "UIGradient3"
				UIGradient3_7.Parent = Frame3_7
	
				backpack.Name = "backpack"
				backpack.Parent = grippos
				backpack.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				backpack.Position = UDim2.new(0, 315, 0, 320)
				backpack.Size = UDim2.new(0, 200, 0, 50)
				backpack.Font = Enum.Font.RobotoMono
				backpack.Text = "backpack"
				backpack.TextColor3 = Color3.fromRGB(0, 0, 0)
				backpack.TextScaled = true
				backpack.TextSize = 51.000
				backpack.TextWrapped = true
				backpack.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.007, 0.01, 1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.93, 1.118, 2.347)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.779, 0.627, -0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.627, 0.779, -0.012)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:play()
					end
				end)
				UICorner2_8.CornerRadius = UDim.new(0, 2)
				UICorner2_8.Name = "UICorner2"
				UICorner2_8.Parent = backpack
	
				UIGradient2_8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_8.Name = "UIGradient2"
				UIGradient2_8.Parent = backpack
	
				Frame3_8.Name = "Frame3"
				Frame3_8.Parent = backpack
				Frame3_8.Active = true
				Frame3_8.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_8.BorderSizePixel = 0
				Frame3_8.ClipsDescendants = true
				Frame3_8.Selectable = true
				Frame3_8.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_8.Name = "UIGradient3"
				UIGradient3_8.Parent = Frame3_8
	
				orange3.Name = "orange3"
				orange3.Parent = mainframe
				orange3.Active = true
				orange3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				orange3.BorderSizePixel = 0
				orange3.ClipsDescendants = true
				orange3.Position = UDim2.new(0, 65, 0, 28)
				orange3.Selectable = true
				orange3.Size = UDim2.new(0, 350, 0, 20)
	
				UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient_2.Parent = orange3
	
				UICorner.CornerRadius = UDim.new(0, 3)
				UICorner.Parent = orange3
	
				TextLabel_2.Parent = orange3
				TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_2.BackgroundTransparency = 1.000
				TextLabel_2.Size = UDim2.new(0, 350, 0, 20)
				TextLabel_2.Font = Enum.Font.Code
				TextLabel_2.Text = "grips"
				TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_2.TextSize = 19.000
	
				orange2.Name = "orange2"
				orange2.Parent = mainframe
				orange2.Active = true
				orange2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				orange2.BorderSizePixel = 0
				orange2.ClipsDescendants = true
				orange2.Position = UDim2.new(0, 550, 0, 28)
				orange2.Selectable = true
				orange2.Size = UDim2.new(0, 350, 0, 20)
	
				UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient_3.Parent = orange2
	
				UICorner_2.CornerRadius = UDim.new(0, 3)
				UICorner_2.Parent = orange2
	
				TextLabel_3.Parent = orange2
				TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_3.BackgroundTransparency = 1.000
				TextLabel_3.Size = UDim2.new(0, 350, 0, 20)
				TextLabel_3.Font = Enum.Font.Code
				TextLabel_3.Text = "others"
				TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_3.TextSize = 19.000
	
				others.Name = "others"
				others.Parent = mainframe
				others.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				others.BackgroundTransparency = 1.000
				others.Position = UDim2.new(0, 315, 0, 15)
				others.Size = UDim2.new(0, 100, 0, 100)
	
				others_2.Name = "others"
				others_2.Parent = others
				others_2.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				others_2.Position = UDim2.new(0, 315, 0, 39)
				others_2.Size = UDim2.new(0, 200, 0, 50)
				others_2.Font = Enum.Font.RobotoMono
				others_2.Text = "demesh equipped tool(s)"
				others_2.TextColor3 = Color3.fromRGB(0, 0, 0)
				others_2.TextScaled = true
				others_2.TextSize = 51.000
				others_2.TextWrapped = true
				others_2.MouseButton1Down:connect(function()
	
					local tool = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
					tool.Handle.Mesh:Destroy()
					tool.Parent = game.Players.LocalPlayer.Backpack
					tool.Parent = game.Players.LocalPlayer.Character
	
				end)
				UICorner2_9.CornerRadius = UDim.new(0, 2)
				UICorner2_9.Name = "UICorner2"
				UICorner2_9.Parent = others_2
	
				UIGradient2_9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_9.Name = "UIGradient2"
				UIGradient2_9.Parent = others_2
	
				Frame3_9.Name = "Frame3"
				Frame3_9.Parent = others_2
				Frame3_9.Active = true
				Frame3_9.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_9.BorderSizePixel = 0
				Frame3_9.ClipsDescendants = true
				Frame3_9.Selectable = true
				Frame3_9.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_9.Name = "UIGradient3"
				UIGradient3_9.Parent = Frame3_9
	
				others_3.Name = "others"
				others_3.Parent = others
				others_3.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				others_3.Position = UDim2.new(0, 315, 0, 123)
				others_3.Size = UDim2.new(0, 200, 0, 50)
				others_3.Font = Enum.Font.RobotoMono
				others_3.Text = "reset grips [random]"
				others_3.TextColor3 = Color3.fromRGB(0, 0, 0)
				others_3.TextScaled = true
				others_3.TextSize = 51.000
				others_3.TextWrapped = true
				others_3.MouseButton1Down:connect(function()
	
					game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, 0, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1, -1.25, 0)
					game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0, 0, 1)
					game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0, 1, 0)
					wait(0.2)
					game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
					wait(0.2)
					h = game.Players.LocalPlayer.Character.Humanoid
					tracks = h:GetPlayingAnimationTracks()
					for _,x in pairs(tracks)
					do x:Play()
					end
	
				end)
	
				UICorner2_10.CornerRadius = UDim.new(0, 2)
				UICorner2_10.Name = "UICorner2"
				UICorner2_10.Parent = others_3
	
				UIGradient2_10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(211, 211, 211)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 211, 211))}
				UIGradient2_10.Name = "UIGradient2"
				UIGradient2_10.Parent = others_3
	
				Frame3_10.Name = "Frame3"
				Frame3_10.Parent = others_3
				Frame3_10.Active = true
				Frame3_10.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				Frame3_10.BorderSizePixel = 0
				Frame3_10.ClipsDescendants = true
				Frame3_10.Selectable = true
				Frame3_10.Size = UDim2.new(0, 200, 0, 3)
	
				UIGradient3_10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient3_10.Name = "UIGradient3"
				UIGradient3_10.Parent = Frame3_10
	
				creditsandinfo.Name = "credits and info"
				creditsandinfo.Parent = mainframe
				creditsandinfo.Active = true
				creditsandinfo.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				creditsandinfo.BorderSizePixel = 0
				creditsandinfo.ClipsDescendants = true
				creditsandinfo.Position = UDim2.new(0, 550, 0, 199)
				creditsandinfo.Selectable = true
				creditsandinfo.Size = UDim2.new(0, 350, 0, 20)
	
				UICorner_3.CornerRadius = UDim.new(0, 3)
				UICorner_3.Parent = creditsandinfo
	
				TextLabel_4.Parent = creditsandinfo
				TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_4.BackgroundTransparency = 1.000
				TextLabel_4.Size = UDim2.new(0, 350, 0, 20)
				TextLabel_4.Font = Enum.Font.Code
				TextLabel_4.Text = "credits and info"
				TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_4.TextSize = 19.000
	
				UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient_4.Parent = creditsandinfo
	
				creditsandinfo_2.Name = "credits and info"
				creditsandinfo_2.Parent = mainframe
				creditsandinfo_2.Active = true
				creditsandinfo_2.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
				creditsandinfo_2.BorderSizePixel = 0
				creditsandinfo_2.ClipsDescendants = true
				creditsandinfo_2.Position = UDim2.new(0, 550, 0, 250)
				creditsandinfo_2.Selectable = true
				creditsandinfo_2.Size = UDim2.new(0, 350, 0, 133)
	
				orange2_2.Name = "orange2"
				orange2_2.Parent = creditsandinfo_2
				orange2_2.Active = true
				orange2_2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
				orange2_2.BorderSizePixel = 0
				orange2_2.ClipsDescendants = true
				orange2_2.Selectable = true
				orange2_2.Size = UDim2.new(0, 350, 0, 5)
	
				UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
				UIGradient_5.Parent = orange2_2
	
				UICorner_4.CornerRadius = UDim.new(0, 3)
				UICorner_4.Parent = orange2_2
	
				TextLabel_5.Parent = creditsandinfo_2
				TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_5.BackgroundTransparency = 1.000
				TextLabel_5.Position = UDim2.new(0, 75, 0, 2)
				TextLabel_5.Size = UDim2.new(0, 200, 0, 50)
				TextLabel_5.Font = Enum.Font.Code
				TextLabel_5.Text = "credits: 1010mane(jackos_mate)"
				TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_5.TextSize = 14.000
	
				TextLabel_6.Parent = creditsandinfo_2
				TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_6.BackgroundTransparency = 1.000
				TextLabel_6.Position = UDim2.new(0, 75, 0, 22)
				TextLabel_6.Size = UDim2.new(0, 200, 0, 50)
				TextLabel_6.Font = Enum.Font.Code
				TextLabel_6.Text = "version: 3"
				TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_6.TextSize = 14.000
	
				TextLabel_7.Parent = creditsandinfo_2
				TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_7.BackgroundTransparency = 1.000
				TextLabel_7.Position = UDim2.new(0, 75, 0, 44)
				TextLabel_7.Size = UDim2.new(0, 200, 0, 50)
				TextLabel_7.Font = Enum.Font.Code
				TextLabel_7.Text = "say !cmds"
				TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_7.TextSize = 14.000
	
				TextLabel_8.Parent = creditsandinfo_2
				TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_8.BackgroundTransparency = 1.000
				TextLabel_8.Position = UDim2.new(0, 75, 0, 66)
				TextLabel_8.Size = UDim2.new(0, 200, 0, 50)
				TextLabel_8.Font = Enum.Font.Code
				TextLabel_8.Text = "do not leak if given."
				TextLabel_8.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_8.TextSize = 14.000
	
				TextLabel_9.Parent = creditsandinfo_2
				TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextLabel_9.BackgroundTransparency = 1.000
				TextLabel_9.Position = UDim2.new(0, 75, 0, 88)
				TextLabel_9.Size = UDim2.new(0, 200, 0, 50)
				TextLabel_9.Font = Enum.Font.Code
				TextLabel_9.Text = "enjoy."
				TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_9.TextSize = 14.000
	
				-- Scripts:
	
				local function OHDC_fake_script() -- griphub_ss.LocalScript 
					local script = Instance.new('LocalScript', griphub_ss)
	
					local HotKey = Enum.KeyCode.F1-- Key to open Gui --
					local UIS = game:GetService("UserInputService")
	
					UIS.InputBegan:Connect(function(Key)
						if Key.KeyCode == HotKey then
							script.Parent.Enabled = not script.Parent.Enabled
						end
					end)
				end
				coroutine.wrap(OHDC_fake_script)()
	
				local plr = game:GetService("Players").LocalPlayer
				local charr = game:GetService("Players").LocalPlayer.Character
				local players = game:GetService("Players"):GetPlayers()
				local gameid = game.PlaceId
	
				print("\nExecuted.")
	
				plr.Chatted:connect(function(message)
					if message:sub(1,5) == "!play" then
						id = message:sub(2)
						local args = message:split(" ")
	
						for _,v in pairs(plr.Backpack:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v.Parent = plr.Character end
						end
	
						wait(.1)
	
						local id = args[2]
	
						local zeros = 199950
						for _,v in pairs(plr.Character:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong", ("0"):rep(zeros)..id, 1, 0, 0) end
						end 
					end
	
					if message:sub(1,3) == "!bp" then
	
						id = message:sub(2)
	
						for _,v in pairs(plr.Backpack:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v.Parent = plr.Character end
						end
	
						for _,v in pairs(plr.Character:GetChildren()) do
							local zeros = 199950
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong", ("0"):rep(zeros)..id, 1, 0, 0) end
						end
	
						wait(.6)
	
						for _,v in pairs(plr.Character:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then plr.Character.Humanoid:UnequipTools() end
						end
	
						wait(.6)
	
						for _,v in pairs(plr.Backpack:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
								v.Handle.Sound.TimePosition = 0
								v.Handle.Sound.Playing = true
							end
						end
	
					end
					if message:sub(1,3) == "!rj" then
						game:GetService("TeleportService"):Teleport(gameid, plr);
					end

					if message:sub(1,3) == "!re" then
						charr:breakjoints()
					end
					
					if message:sub(1.5) == "!demesh" then					
						for _, tool in ipairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
							if tool:IsA("Tool") then
								tool.Handle.Mesh:Destroy()
								tool.Parent = game:GetService("Players").LocalPlayer.Character -- I didn't use Equip because the Equip function unequips any other tools in your character.
							end
						end					
					end
					
					if message:sub(1.5) == "!ufo" then
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end


						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.002, -0.025)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.387, -5.591, -1.532)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.025, 0.011, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.003, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.034, -0.002, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.448, -5.591, 1.474)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, 0.011, 0.034)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.002)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.689, -0.002, 0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.103, -5.591, 2.064)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.724, 0.011, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.01, 1, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.724, -0.002, 0.689)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.064, -5.591, -0.103)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.689, 0.011, -0.724)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 1, 0.01)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

					end
					
					if message:sub(1,7) == "!etools" then
						for _, tool in ipairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
							if tool:IsA("Tool") then	                    
								tool.Parent = game:GetService("Players").LocalPlayer.Character -- I didn't use Equip because the Equip function unequips any other tools in your character.
							end
						end
					end
					
					if message:sub(1,5) == "!line" then
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(4.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(7.602, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.011, -0.014, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.398, -6.613, -1.608)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(1, -0.011, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.011, 1, -0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
					end	
					
					if message:sub(1,5) == "!bone" then
							
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.011, -0.014, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.586, 1.558, 0.81)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-1, -0.011, 0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-2.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.011, -0.014, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.586, 1.558, 0.81)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-1, -0.011, 0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-2.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.011, -0.014, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.586, 1.558, 0.81)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-1, -0.011, 0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.011, 1, 0.014)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -0.014, -0.011)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-2.39, 1.158, 1.586)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.011, -0.011, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.014, 1, 0.011)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						end
					if message:sub(1,4) == "!hat" then
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.038, -0.998, -0.043)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.452, -1.664, 2.039)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.999, -0.038, -0.008)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.006, 0.043, -0.999)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.043, -0.998, -0.038)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-4.186, -1.664, 1.452)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.008, -0.038, 0.999)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.999, 0.043, -0.006)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
					end
					
					if message:sub(1,6) == "!wings" then
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.86, 0.384, 0.337)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(2.907, 0.586, 1.671)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.352, -0.035, 0.936)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.371, 0.923, -0.105)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.875, 0.384, -0.294)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(3.988, 0.586, 1.362)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.332, -0.035, 0.943)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.352, 0.923, 0.158)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.939, 0.067, 0.337)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(5.751, -1.07, 1.671)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.342, 0.088, 0.936)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.033, 0.994, -0.105)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.954, 0.062, -0.294)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(6.767, -1.439, 1.362)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.3, -0.146, 0.943)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.015, 0.987, 0.158)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.939, 0.067, 0.337)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(5.751, 0.13, 1.671)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.342, 0.088, 0.936)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.033, 0.994, -0.105)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.954, 0.062, -0.294)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(6.767, -0.439, 1.362)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.3, -0.146, 0.943)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.015, 0.987, 0.158)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
					end
					
					if message:sub(1,9) == "!backpack" then
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0.017, -0.012, 1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.249, 1.458, 2.422)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.024, 1, 0.013)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(1, 0.024, -0.017)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end
						
						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.017, -0.012, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.249, 1.458, -2.856)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.024, 1, -0.013)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, 0.024, 0.017)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.017, -0.012, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(1.857, 1.458, -2.606)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.024, 1, -0.013)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, 0.024, 0.017)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0.017, -0.012, -1)
						game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(3.895, 1.458, -2.606)
						game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.024, 1, -0.013)
						game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, 0.024, 0.017)
						wait(0.2)
						game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
						wait(0.2)
						h = game.Players.LocalPlayer.Character.Humanoid
						tracks = h:GetPlayingAnimationTracks()
						for _,x in pairs(tracks)
						do x:Play()
						end

						
					end
					
					if message:sub(1,4) == "!fly" then
						
						
						-- Gui to Lua
						-- Version: 3.2

						-- Instances:

						local ScreenGui = Instance.new("ScreenGui")
						local Frame = Instance.new("Frame")
						local UICorner1 = Instance.new("UICorner")
						local orange3 = Instance.new("Frame")
						local UIGradient = Instance.new("UIGradient")
						local TextLabel = Instance.new("TextLabel")
						local TextLabel_2 = Instance.new("TextLabel")
						local TextButton = Instance.new("TextButton")
						local UICorner = Instance.new("UICorner")
						local TextButton_2 = Instance.new("TextButton")
						local orange3_2 = Instance.new("Frame")
						local UIGradient_2 = Instance.new("UIGradient")
						local UICorner_2 = Instance.new("UICorner")

						--Properties:

						ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
						ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
						ScreenGui.ResetOnSpawn = true

						Frame.Parent = ScreenGui
						Frame.Active = true
						Frame.AnchorPoint = Vector2.new(0.5, 0.5)
						Frame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
						Frame.BorderColor3 = Color3.fromRGB(255, 145, 0)
						Frame.BorderSizePixel = 0
						Frame.Position = UDim2.new(0.5, 131, 0.564318538, -115)
						Frame.Selectable = true
						Frame.Draggable = true
						Frame.Size = UDim2.new(0, 429, 0, 125)

						UICorner1.Name = "UICorner1"
						UICorner1.Parent = Frame

						orange3.Name = "orange3"
						orange3.Parent = Frame
						orange3.Active = true
						orange3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
						orange3.BorderSizePixel = 0
						orange3.ClipsDescendants = true
						orange3.Selectable = true
						orange3.Size = UDim2.new(0, 429, 0, 12)

						UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
						UIGradient.Parent = orange3

						TextLabel.Parent = orange3
						TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel.BackgroundTransparency = 1.000
						TextLabel.Size = UDim2.new(0, 429, 0, 12)
						TextLabel.Font = Enum.Font.Code
						TextLabel.Text = "griphub_ss fly gui"
						TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel.TextScaled = true
						TextLabel.TextSize = 19.000
						TextLabel.TextWrapped = true

						TextLabel_2.Parent = Frame
						TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel_2.BackgroundTransparency = 1.000
						TextLabel_2.Position = UDim2.new(0, 120, 0, 5)
						TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
						TextLabel_2.Font = Enum.Font.Code
						TextLabel_2.Text = "click the button to enable fly"
						TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel_2.TextSize = 14.000

						TextButton.Parent = Frame
						TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
						TextButton.Position = UDim2.new(0, 415, 0, 1)
						TextButton.Size = UDim2.new(0, 10, 0, 10)
						TextButton.Font = Enum.Font.SourceSans
						TextButton.Text = ""
						TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextButton.TextSize = 14.000

						UICorner.CornerRadius = UDim.new(0, 3)
						UICorner.Parent = TextButton

						TextButton_2.Parent = Frame
						TextButton_2.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
						TextButton_2.Position = UDim2.new(0, 122, 0, 55)
						TextButton_2.Size = UDim2.new(0, 200, 0, 50)
						TextButton_2.Font = Enum.Font.Code
						TextButton_2.Text = "FLY [CTRL==E]"
						TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextButton_2.TextSize = 14.000
						TextButton_2.MouseButton1Down:Connect(function()
							ScreenGui.Enabled = false
						end)


						orange3_2.Name = "orange3"
						orange3_2.Parent = TextButton_2
						orange3_2.Active = true
						orange3_2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
						orange3_2.BorderSizePixel = 0
						orange3_2.ClipsDescendants = true
						orange3_2.Selectable = true
						orange3_2.Size = UDim2.new(0, 200, 0, 2)

						UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
						UIGradient_2.Parent = orange3_2

						UICorner_2.CornerRadius = UDim.new(0, 3)
						UICorner_2.Parent = TextButton_2

						-- Scripts:

						local function CJJH_fake_script() -- Frame.LocalScript 
							local script = Instance.new('LocalScript', Frame)

							local HotKey = Enum.KeyCode.Q-- Key to open Gui --
							local UIS = game:GetService("UserInputService")

							UIS.InputBegan:Connect(function(Key)
								if Key.KeyCode == HotKey then
									script.Parent.Visible = not script.Parent.Visible
								end
							end)
						end
						coroutine.wrap(CJJH_fake_script)()
						local function FDMAPR_fake_script() -- TextButton.LocalScript 
							local script = Instance.new('LocalScript', TextButton)

							script.Parent.MouseButton1Down:Connect(function()
								script.Parent.Parent.Parent.Enabled = false
							end)
						end
						coroutine.wrap(FDMAPR_fake_script)()
						local function QWTC_fake_script() -- TextButton_2.LocalScript 
							local script = Instance.new('LocalScript', TextButton_2)

							script.Parent.MouseButton1Down:Connect(function()

								repeat wait()
								until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
								local mouse = game.Players.LocalPlayer:GetMouse()
								repeat wait() until mouse
								local plr = game.Players.LocalPlayer
								local torso = plr.Character.Torso
								local flying = true
								local deb = true
								local ctrl = {f = 0, b = 0, l = 0, r = 0}
								local lastctrl = {f = 0, b = 0, l = 0, r = 0}
								local maxspeed = 50
								local speed = 0

								function Fly()
									local bg = Instance.new("BodyGyro", torso)
									bg.P = 9e4
									bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
									bg.cframe = torso.CFrame
									local bv = Instance.new("BodyVelocity", torso)
									bv.velocity = Vector3.new(0,0.1,0)
									bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
									repeat wait()
										plr.Character.Humanoid.PlatformStand = true
										if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
											speed = speed+.5+(speed/maxspeed)
											if speed > maxspeed then
												speed = maxspeed
											end
										elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
											speed = speed-1
											if speed < 0 then
												speed = 0
											end
										end
										if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
											bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
											lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
										elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
											bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
										else
											bv.velocity = Vector3.new(0,0.1,0)
										end
										bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
									until not flying
									ctrl = {f = 0, b = 0, l = 0, r = 0}
									lastctrl = {f = 0, b = 0, l = 0, r = 0}
									speed = 0
									bg:Destroy()
									bv:Destroy()
									plr.Character.Humanoid.PlatformStand = false
								end
								mouse.KeyDown:connect(function(key)
									if key:lower() == "e" then
										if flying then flying = false
										else
											flying = true
											Fly()
										end
									elseif key:lower() == "w" then
										ctrl.f = 1
									elseif key:lower() == "s" then
										ctrl.b = -1
									elseif key:lower() == "a" then
										ctrl.l = -1
									elseif key:lower() == "d" then
										ctrl.r = 1
									end
								end)
								mouse.KeyUp:connect(function(key)
									if key:lower() == "w" then
										ctrl.f = 0
									elseif key:lower() == "s" then
										ctrl.b = 0
									elseif key:lower() == "a" then
										ctrl.l = 0
									elseif key:lower() == "d" then
										ctrl.r = 0
									end
								end)
								Fly()
							end)
						end
						coroutine.wrap(QWTC_fake_script)()

						
						
					end
	
					if message:sub(1,3) == "!tp" then 
	
						local args = message:split(" ")
	
						for _,v in pairs(plr.Character:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
								v.Handle.Sound.TimePosition = args[2]
							end
						end
	
						for _,v in pairs(plr.Backpack:GetChildren()) do
							if v:IsA("Tool") and string.lower(v.Name) == "boombox" then
								v.Handle.Sound.TimePosition = args[2]
							end
						end
	
						if message:sub(1,4) == "!tpp" then
	
							local args = message:split(" ")
	
							for _,v in pairs(game.Players:GetPlayers()) do
	
								if v.Name ~= plr.Name then
									for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
										if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then 
											v2.Handle.Sound.TimePosition = args[2] end
									end
									for _,v2 in pairs(v.Backpack:GetChildren()) do
										if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then 
											v2.Handle.Sound.TimePosition = args[2] end
									end
								end
							end
						end
	
					end
					if message:sub(1,5) == "!cmds" then
						-- Gui to Lua
						-- Version: 3.2
	
						-- Instances:
	
						local congui2 = Instance.new("ScreenGui")
						local Frame1 = Instance.new("Frame")
						local UICorner1 = Instance.new("UICorner")
						local UIGradient1 = Instance.new("UIGradient")
						local Fram2 = Instance.new("Frame")
						local UIGradient = Instance.new("UIGradient")
						local TextButton = Instance.new("TextButton")
						local UICorner1_2 = Instance.new("UICorner")
						local TextLabel = Instance.new("TextLabel")
						local TextLabel_2 = Instance.new("TextLabel")
						local ScrollingFrame = Instance.new("ScrollingFrame")
						local TextLabel_3 = Instance.new("TextLabel")
						local UIListLayout = Instance.new("UIListLayout")
						local TextBox = Instance.new("TextBox")
						local orange1 = Instance.new("Frame")
						local UIGradient_2 = Instance.new("UIGradient")
	
						--Properties:
	
						congui2.Name = "congui2"
						congui2.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
						congui2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
	
						Frame1.Name = "Frame1"
						Frame1.Parent = congui2
						Frame1.Active = true
						Frame1.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
						Frame1.ClipsDescendants = true
						Frame1.Position = UDim2.new(0, 755, 0, 255)
						Frame1.Selectable = true
						Frame1.Draggable = true
						Frame1.Size = UDim2.new(0, 555, 0, 255)
	
						UICorner1.Name = "UICorner1"
						UICorner1.Parent = Frame1
	
						UIGradient1.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(134, 134, 134)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(134, 134, 134))}
						UIGradient1.Name = "UIGradient1"
						UIGradient1.Parent = Frame1
	
						Fram2.Name = "Fram2"
						Fram2.Parent = Frame1
						Fram2.Active = true
						Fram2.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
						Fram2.BorderSizePixel = 0
						Fram2.ClipsDescendants = true
						Fram2.Selectable = true
						Fram2.Size = UDim2.new(0, 555, 0, 22)
	
						UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
						UIGradient.Parent = Fram2
	
						TextButton.Parent = Fram2
						TextButton.BackgroundColor3 = Color3.fromRGB(255, 8, 0)
						TextButton.BorderSizePixel = 0
						TextButton.Position = UDim2.new(0, 525, 0, 3)
						TextButton.Size = UDim2.new(0, 15, 0, 15)
						TextButton.Font = Enum.Font.SourceSans
						TextButton.Text = ""
						TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextButton.TextSize = 14.000
						TextButton.MouseButton1Click:Connect(function()
							congui2.Enabled = false
						end)
	
						UICorner1_2.CornerRadius = UDim.new(0, 3)
						UICorner1_2.Name = "UICorner1"
						UICorner1_2.Parent = TextButton
	
						TextLabel.Parent = Frame1
						TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel.BackgroundTransparency = 1.000
						TextLabel.BorderSizePixel = 0
						TextLabel.Position = UDim2.new(0, 180, 0, -15)
						TextLabel.Size = UDim2.new(0, 200, 0, 50)
						TextLabel.Font = Enum.Font.RobotoMono
						TextLabel.Text = "COMMANDS"
						TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel.TextSize = 19.000
						TextLabel.TextWrapped = true
	
						TextLabel_2.Parent = Frame1
						TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel_2.BackgroundTransparency = 1.000
						TextLabel_2.BorderSizePixel = 0
						TextLabel_2.Position = UDim2.new(0, 180, 0, 25)
						TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
						TextLabel_2.Font = Enum.Font.RobotoMono
						TextLabel_2.Text = "CMDS:"
						TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel_2.TextSize = 20.000
						TextLabel_2.TextStrokeColor3 = Color3.fromRGB(255, 136, 0)
						TextLabel_2.TextWrapped = true
	
						ScrollingFrame.Parent = Frame1
						ScrollingFrame.Active = true
						ScrollingFrame.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
						ScrollingFrame.Position = UDim2.new(0, 180, 0, 75)
						ScrollingFrame.Size = UDim2.new(0, 200, 0, 80)
	
						TextLabel_3.Parent = ScrollingFrame
						TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel_3.BackgroundTransparency = 1.000
						TextLabel_3.Size = UDim2.new(0, 200, 0, 145)
						TextLabel_3.Font = Enum.Font.Code
						TextLabel_3.Text = " !play . !mute . !steal . !mute . !off . !duper . !tpp . !tp . !bp . !rj . !tpp . !demesh . !line . !ufo . !bone . !wings . !re . !fly . !etools . !backpack " 
						TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel_3.TextSize = 14.000
						TextLabel_3.TextWrapped = true
	
						UIListLayout.Parent = ScrollingFrame
						UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
	
						TextBox.Parent = Frame1
						TextBox.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
						TextBox.Position = UDim2.new(0, 180, 0, 165)
						TextBox.Size = UDim2.new(0, 200, 0, 50)
						TextBox.Font = Enum.Font.Code
						TextBox.Text = "PREFIX IS ' ! ' "
						TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextBox.TextSize = 14.000
	
						orange1.Name = "orange1"
						orange1.Parent = TextBox
						orange1.Active = true
						orange1.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
						orange1.BorderSizePixel = 0
						orange1.ClipsDescendants = true
						orange1.Selectable = true
						orange1.Size = UDim2.new(0, 200, 0, 3)
	
						UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
						UIGradient_2.Parent = orange1
	
						-- Scripts:
	
						local function LEMYHDB_fake_script() -- Frame1.LocalScript 
							local script = Instance.new('LocalScript', Frame1)
	
							local HotKey = Enum.KeyCode.F3-- Key to open Gui --
							local UIS = game:GetService("UserInputService")
	
							UIS.InputBegan:Connect(function(Key)
								if Key.KeyCode == HotKey then
									script.Parent.Visible = not script.Parent.Visible
								end
							end)
						end
						coroutine.wrap(LEMYHDB_fake_script)()
					end
					if message:sub(1,6) == "!duper" then
						-- Gui to Lua
						-- Version: 3.2
	
						-- Instances:
	
						local ScreenGui = Instance.new("ScreenGui")
						local Frame = Instance.new("Frame")
						local Amount = Instance.new("TextBox")
						local UICorner = Instance.new("UICorner")
						local Dupe = Instance.new("TextButton")
						local UICorner_2 = Instance.new("UICorner")
						local UICorner1 = Instance.new("UICorner")
						local orange3 = Instance.new("Frame")
						local UIGradient = Instance.new("UIGradient")
						local TextLabel = Instance.new("TextLabel")
						local TextLabel_2 = Instance.new("TextLabel")
						local TextButton = Instance.new("TextButton")
						local UICorner_3 = Instance.new("UICorner")
	
						--Properties:
	
						ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
						ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
						ScreenGui.ResetOnSpawn = false
	
						Frame.Parent = ScreenGui
						Frame.Active = true
						Frame.AnchorPoint = Vector2.new(0.5, 0.5)
						Frame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
						Frame.BorderColor3 = Color3.fromRGB(255, 145, 0)
						Frame.BorderSizePixel = 0
						Frame.Position = UDim2.new(0.5, 131, 0.564318538, -115)
						Frame.Selectable = true
						Frame.Draggable = true
						Frame.Size = UDim2.new(0, 429, 0, 250)
	
						Amount.Name = "Amount"
						Amount.Parent = Frame
						Amount.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
						Amount.BorderColor3 = Color3.fromRGB(54, 54, 54)
						Amount.Position = UDim2.new(0, 19, 0.202999994, 0)
						Amount.Size = UDim2.new(0, 125, 0, 175)
						Amount.Font = Enum.Font.Code
						Amount.PlaceholderColor3 = Color3.fromRGB(112, 112, 112)
						Amount.PlaceholderText = "Amount"
						Amount.Text = ""
						Amount.TextColor3 = Color3.fromRGB(255, 255, 255111)
						Amount.TextSize = 14.000
	
						UICorner.CornerRadius = UDim.new(0, 3)
						UICorner.Parent = Amount
	
						Dupe.Name = "Dupe"
						Dupe.Parent = Frame
						Dupe.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
						Dupe.BorderColor3 = Color3.fromRGB(54, 54, 54)
						Dupe.Position = UDim2.new(0.345004708, 0, 0.202760756, 0)
						Dupe.Size = UDim2.new(0, 265, 0, 175)
						Dupe.Font = Enum.Font.Code
						Dupe.Text = "Dupe Amount"
						Dupe.TextColor3 = Color3.fromRGB(112, 112, 112)
						Dupe.TextSize = 14.000
	
						UICorner_2.CornerRadius = UDim.new(0, 3)
						UICorner_2.Parent = Dupe
	
						UICorner1.Name = "UICorner1"
						UICorner1.Parent = Frame
	
						orange3.Name = "orange3"
						orange3.Parent = Frame
						orange3.Active = true
						orange3.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
						orange3.BorderSizePixel = 0
						orange3.ClipsDescendants = true
						orange3.Selectable = true
						orange3.Size = UDim2.new(0, 429, 0, 12)
	
						UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
						UIGradient.Parent = orange3
	
						TextLabel.Parent = orange3
						TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel.BackgroundTransparency = 1.000
						TextLabel.Size = UDim2.new(0, 429, 0, 12)
						TextLabel.Font = Enum.Font.Code
						TextLabel.Text = "griphub_ss duper"
						TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel.TextScaled = true
						TextLabel.TextSize = 19.000
						TextLabel.TextWrapped = true
	
						TextLabel_2.Parent = Frame
						TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
						TextLabel_2.BackgroundTransparency = 1.000
						TextLabel_2.Position = UDim2.new(0, 120, 0, 5)
						TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
						TextLabel_2.Font = Enum.Font.Code
						TextLabel_2.Text = "put any amount you want to dupe."
						TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextLabel_2.TextSize = 14.000
	
						TextButton.Parent = Frame
						TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
						TextButton.Position = UDim2.new(0, 415, 0, 1)
						TextButton.Size = UDim2.new(0, 10, 0, 10)
						TextButton.Font = Enum.Font.SourceSans
						TextButton.Text = ""
						TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
						TextButton.TextSize = 14.000
	
						UICorner_3.CornerRadius = UDim.new(0, 3)
						UICorner_3.Parent = TextButton
	
						-- Scripts:
	
						local function BWIKKAP_fake_script() -- Dupe.LocalScript 
							local script = Instance.new('LocalScript', Dupe)
	
							script.Parent.MouseButton1Click:Connect(function()
								for i=1,tonumber(script.Parent.Parent.Amount.Text) or 1 do
									char=game.Players.LocalPlayer.Character
									game.Players.LocalPlayer.Character=nil
									game.Players.LocalPlayer.Character=char
									char.Animate:Destroy()
									char.HumanoidRootPart.CFrame=CFrame.new(0,9999,0)
									wait(.1)
									char.HumanoidRootPart.Anchored=true
									for i,v in pairs(char:GetChildren()) do
										if v:IsA("Tool") then
											v.Parent=game.Players.LocalPlayer.Backpack
										end
									end
									wait(game.Players.RespawnTime-0.3)
									local t = {}
									for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
										v.Parent=char
										v.Parent=workspace
										t[i]=v
									end
									char.Humanoid:Destroy()
									game.Players.LocalPlayer.Character=nil
									game.Players.LocalPlayer.CharacterAdded:Wait()
									char=game.Players.LocalPlayer.Character
									char:WaitForChild("Humanoid")
									wait(.1)
									for i,v in pairs(t) do
										char.Humanoid:EquipTool(v)
									end
									wait(.3)
								end	
							end)
	
						end
						coroutine.wrap(BWIKKAP_fake_script)()
						local function EOXBKXZ_fake_script() -- Frame.LocalScript 
							local script = Instance.new('LocalScript', Frame)
	
							local HotKey = Enum.KeyCode.Q-- Key to open Gui --
							local UIS = game:GetService("UserInputService")
	
							UIS.InputBegan:Connect(function(Key)
								if Key.KeyCode == HotKey then
									script.Parent.Visible = not script.Parent.Visible
								end
							end)
						end
						coroutine.wrap(EOXBKXZ_fake_script)()
						local function WCSNGH_fake_script() -- TextButton.LocalScript 
							local script = Instance.new('LocalScript', TextButton)
	
							script.Parent.MouseButton1Down:Connect(function()
								script.Parent.Parent.Parent.Enabled = false
							end)
						end
						coroutine.wrap(WCSNGH_fake_script)()
					end
	
					if message:sub(1,4) == "!off" then
						for _,v in pairs(game.Players:GetPlayers()) do
							if v.Name ~= plr.Name then
								-- Character
								for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
									if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.Playing = false; end
								end
	
								-- Backpack
								for _,v2 in pairs(v.Backpack:GetChildren()) do
									if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.Playing = false; end
								end
							end
						end
					end
	
					if message:sub(1,5) == "!mute" then
						while wait(.03) do
							for _,v in pairs(game.Players:GetPlayers()) do
								if v.Name ~= plr.Name then
									-- Character
									for _,v2 in pairs(game.Workspace[v.Name]:GetChildren()) do
										if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.TimePosition = 0 end
									end
	
									-- Backpack
									for _,v2 in pairs(v.Backpack:GetChildren()) do
										if v2:IsA("Tool") and string.lower(v2.Name) == "boombox" then v2.Handle.Sound.TimePosition = 0 end
									end
								end
							end
						end
					end
	
					if message:sub(1,7) == "!steal" then 
						for _,v in pairs(game.workspace:GetChildren()) do
							if v:IsA("Tool") then
								v.Handle.CFrame = plr.Character.Head.CFrame
							end
						end
					end
				end)
	
	
				--
	
				congui2.Enabled=false
			end)
	
			orange1.Name = "orange1"
			orange1.Parent = TextButton
			orange1.Active = true
			orange1.BackgroundColor3 = Color3.fromRGB(255, 128, 0)
			orange1.BorderSizePixel = 0
			orange1.ClipsDescendants = true
			orange1.Selectable = true
			orange1.Size = UDim2.new(0, 200, 0, 3)
	
			UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 247, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 247, 0))}
			UIGradient_2.Parent = orange1
	
	
		end
	end)
end
coroutine.wrap(JKYNEI_fake_script)()
