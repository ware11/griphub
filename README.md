-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Frame_3 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local Frame_4 = Instance.new("Frame")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local TextLabel_9 = Instance.new("TextLabel")
local TextLabel_10 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.Active = true
Frame.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame.BorderColor3 = Color3.fromRGB(255, 140, 0)
Frame.Position = UDim2.new(0.195707068, 0, 0.159392789, 0)
Frame.Selectable = true
Frame.Draggable = true
Frame.Size = UDim2.new(0, 623, 0, 308)

Frame_2.Parent = Frame
Frame_2.Active = true
Frame_2.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame_2.BorderColor3 = Color3.fromRGB(255, 140, 0)
Frame_2.Position = UDim2.new(-0.186195821, 0, 1.05194807, 0)
Frame_2.Selectable = true
Frame_2.Size = UDim2.new(0, 712, 0, 66)

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.0969101116, 0, -0.272727251, 0)
TextLabel.Size = UDim2.new(0, 373, 0, 101)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "VERSION: V:1.5(2)"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 38.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(42, 42, 42)
TextLabel.TextStrokeTransparency = 0.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.193820223, 0, -0.378787875, 0)
TextLabel_2.Size = UDim2.new(0, 393, 0, 115)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "GRIPHUB-X"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 38.000
TextLabel_2.TextStrokeColor3 = Color3.fromRGB(54, 54, 54)
TextLabel_2.TextStrokeTransparency = 0.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = Frame_2
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.217696622, 0, -0.378787875, 0)
TextLabel_3.Size = UDim2.new(0, 421, 0, 115)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "HUB-X"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 179, 0)
TextLabel_3.TextSize = 38.000
TextLabel_3.TextStrokeColor3 = Color3.fromRGB(54, 54, 54)
TextLabel_3.TextStrokeTransparency = 0.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = Frame_2
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.521067441, 0, -0.378787875, 0)
TextLabel_4.Size = UDim2.new(0, 421, 0, 115)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "V.V: BETA"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 179, 0)
TextLabel_4.TextSize = 63.000
TextLabel_4.TextStrokeTransparency = 0.000
TextLabel_4.TextWrapped = true

Frame_3.Parent = Frame
Frame_3.Active = true
Frame_3.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame_3.BorderColor3 = Color3.fromRGB(255, 140, 0)
Frame_3.Position = UDim2.new(0, 0, -0.224025905, 0)
Frame_3.Selectable = true
Frame_3.Size = UDim2.new(0, 255, 0, 55)

ImageLabel.Parent = Frame_3
ImageLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.694446266, 0, 0, 0)
ImageLabel.Size = UDim2.new(0, 57, 0, 49)
ImageLabel.Image = "http://www.roblox.com/asset/?id=90072531"
ImageLabel.ImageColor3 = Color3.fromRGB(0, 0, 0)

TextLabel_5.Parent = Frame_3
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.344212353, 0, 0, 0)
TextLabel_5.Size = UDim2.new(0, 106, 0, 55)
TextLabel_5.Font = Enum.Font.GothamBold
TextLabel_5.Text = "HUB"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 183, 0)
TextLabel_5.TextSize = 29.000
TextLabel_5.TextStrokeColor3 = Color3.fromRGB(57, 57, 57)
TextLabel_5.TextStrokeTransparency = 0.000

TextLabel_6.Parent = Frame_3
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.0781186223, 0, 0, 0)
TextLabel_6.Size = UDim2.new(0, 106, 0, 55)
TextLabel_6.Font = Enum.Font.GothamBold
TextLabel_6.Text = "GRIP"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextSize = 29.000
TextLabel_6.TextStrokeColor3 = Color3.fromRGB(57, 57, 57)
TextLabel_6.TextStrokeTransparency = 0.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton.BorderColor3 = Color3.fromRGB(47, 47, 47)
TextButton.Position = UDim2.new(0.0690208673, 0, 0.288961023, 0)
TextButton.Size = UDim2.new(0, 237, 0, 64)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "EXECUTE GRIPHUB DUPE GUI"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton.TextStrokeTransparency = 0.000
TextButton.TextWrapped = true

TextButton.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ware11/dupe1/main/DUPE.GRIPS"))();
end)

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton_2.BorderColor3 = Color3.fromRGB(47, 47, 47)
TextButton_2.Position = UDim2.new(0.0706260055, 0, 0.058441557, 0)
TextButton_2.Size = UDim2.new(0, 237, 0, 64)
TextButton_2.Font = Enum.Font.GothamBold
TextButton_2.Text = "DEMESH TOOL(S)"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_2.TextStrokeTransparency = 0.000
TextButton_2.TextWrapped = true
TextButton_2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ware11/demesh1/main/README.md"))();
end)
ScrollingFrame.Parent = Frame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
ScrollingFrame.BorderColor3 = Color3.fromRGB(255, 140, 0)
ScrollingFrame.Position = UDim2.new(0.560759544, 0, 0.0357142873, 0)
ScrollingFrame.Size = UDim2.new(0, 197, 0, 288)

TextButton_3.Parent = ScrollingFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton_3.BorderColor3 = Color3.fromRGB(255, 140, 0)
TextButton_3.Position = UDim2.new(0.0253807101, 0, 0.03125, 0)
TextButton_3.Size = UDim2.new(0, 172, 0, 50)
TextButton_3.Font = Enum.Font.GothamBold
TextButton_3.Text = "LOWHOLD [1]"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000
TextButton_3.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_3.TextStrokeTransparency = 0.000
TextButton_3.TextWrapped = true
TextButton_3.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(1, -1, 0)
	game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0, 0.855, 0)
	game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.1, 0, 2)
	game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(1, 0, 0)
	wait(0.2)
	game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
	wait(0.2)
	h = game.Players.LocalPlayer.Character.Humanoid
	tracks = h:GetPlayingAnimationTracks()
	for _,x in pairs(tracks)
	do x:Stop()
	end	

end)
TextButton_4.Parent = ScrollingFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton_4.BorderColor3 = Color3.fromRGB(255, 140, 0)
TextButton_4.Position = UDim2.new(0.0253807101, 0, 0.12702921, 0)
TextButton_4.Size = UDim2.new(0, 172, 0, 50)
TextButton_4.Font = Enum.Font.GothamBold
TextButton_4.Text = "LOWHOLD [2]"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000
TextButton_4.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_4.TextStrokeTransparency = 0.000
TextButton_4.TextWrapped = true
TextButton_4.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(0, -1, -0)
	game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(0.04, 0.811, -0.092)
	game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-0.006, 0, -1)
	game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-1, -0, 0.006)
	wait(0.2)
	game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
	wait(0.2)
	h = game.Players.LocalPlayer.Character.Humanoid
	tracks = h:GetPlayingAnimationTracks()
	for _,x in pairs(tracks)
	do x:Stop()
	end

end)
TextButton_5.Parent = ScrollingFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton_5.BorderColor3 = Color3.fromRGB(255, 140, 0)
TextButton_5.Position = UDim2.new(0.0253807101, 0, 0.224431813, 0)
TextButton_5.Size = UDim2.new(0, 172, 0, 50)
TextButton_5.Font = Enum.Font.GothamBold
TextButton_5.Text = "MOUNT ON BACK"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000
TextButton_5.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_5.TextStrokeTransparency = 0.000
TextButton_5.TextWrapped = true
TextButton_5.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0, -0.013, 1)
	game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-1.504, 0.426, 2.242)
	game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(-1, -0.015, -0)
	game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(-0.015, 1, 0.013)
	wait(0.2)
	game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
	wait(0.2)
	h = game.Players.LocalPlayer.Character.Humanoid
	tracks = h:GetPlayingAnimationTracks()
	for _,x in pairs(tracks)
	do x:Play()
	end

end)
TextButton_6.Parent = ScrollingFrame
TextButton_6.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton_6.BorderColor3 = Color3.fromRGB(255, 140, 0)
TextButton_6.Position = UDim2.new(0.0304568522, 0, 0.318587661, 0)
TextButton_6.Size = UDim2.new(0, 172, 0, 50)
TextButton_6.Font = Enum.Font.GothamBold
TextButton_6.Text = "MOUNT ON SHOULDER"
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 14.000
TextButton_6.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_6.TextStrokeTransparency = 0.000
TextButton_6.TextWrapped = true
TextButton_6.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Backpack.BoomBox.GripForward =  Vector3.new(-0, -1, 0)
	game.Players.LocalPlayer.Backpack.BoomBox.GripPos =  Vector3.new(-0.033, -2.839, 0.396)
	game.Players.LocalPlayer.Backpack.BoomBox.GripRight =  Vector3.new(0.174, 0, 0.985)
	game.Players.LocalPlayer.Backpack.BoomBox.GripUp =  Vector3.new(0.985, -0, -0.174)
	wait(0.2)
	game.Players.LocalPlayer:findFirstChildOfClass('Backpack')['BoomBox'].Parent = game.Players.LocalPlayer.Character
	wait(0.2)
	h = game.Players.LocalPlayer.Character.Humanoid
	tracks = h:GetPlayingAnimationTracks()
	for _,x in pairs(tracks)
	do x:Stop()
	end

end)

TextButton_7.Parent = ScrollingFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton_7.BorderColor3 = Color3.fromRGB(255, 140, 0)
TextButton_7.Position = UDim2.new(0.0253807101, 0, 0.411120117, 0)
TextButton_7.Size = UDim2.new(0, 172, 0, 50)
TextButton_7.Font = Enum.Font.GothamBold
TextButton_7.Text = "NORMAL HOLD"
TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.TextSize = 14.000
TextButton_7.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextButton_7.TextStrokeTransparency = 0.000
TextButton_7.TextWrapped = true
TextButton_7.MouseButton1Down:connect(function()

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
Frame_4.Parent = Frame
Frame_4.Active = true
Frame_4.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame_4.BorderColor3 = Color3.fromRGB(255, 140, 0)
Frame_4.Position = UDim2.new(-0.186195821, 0, 0, 0)
Frame_4.Selectable = true
Frame_4.Size = UDim2.new(0, 100, 0, 308)

TextLabel_7.Parent = Frame_4
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(-0.119999997, 0, -0.0649350658, 0)
TextLabel_7.Size = UDim2.new(0, 124, 0, 100)
TextLabel_7.Font = Enum.Font.GothamBold
TextLabel_7.Text = "Only Works in DOLLHOUSE ROLEPLAY"
TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.TextSize = 14.000
TextLabel_7.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextLabel_7.TextStrokeTransparency = 0.000
TextLabel_7.TextWrapped = true

TextLabel_8.Parent = Frame_4
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.Position = UDim2.new(-0.119999997, 0, 0.129870117, 0)
TextLabel_8.Size = UDim2.new(0, 124, 0, 100)
TextLabel_8.Font = Enum.Font.GothamBold
TextLabel_8.Text = "CREDITS: 1010Mane"
TextLabel_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_8.TextSize = 14.000
TextLabel_8.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextLabel_8.TextStrokeTransparency = 0.000
TextLabel_8.TextWrapped = true

TextLabel_9.Parent = Frame_4
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.Position = UDim2.new(0, 0, 0.227272734, 0)
TextLabel_9.Size = UDim2.new(0, 101, 0, 180)
TextLabel_9.Font = Enum.Font.GothamBold
TextLabel_9.Text = "letoka is W"
TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_9.TextSize = 14.000
TextLabel_9.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextLabel_9.TextStrokeTransparency = 0.000
TextLabel_9.TextWrapped = true

TextLabel_10.Parent = Frame_4
TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.BackgroundTransparency = 1.000
TextLabel_10.Position = UDim2.new(-0.0400000066, 0, 0.454545438, 0)
TextLabel_10.Size = UDim2.new(0, 104, 0, 222)
TextLabel_10.Font = Enum.Font.GothamBold
TextLabel_10.Text = "ALL PLANNED IN 2021 @GRIPHUBCOMMUNITY"
TextLabel_10.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_10.TextSize = 14.000
TextLabel_10.TextStrokeColor3 = Color3.fromRGB(44, 44, 44)
TextLabel_10.TextStrokeTransparency = 0.000
TextLabel_10.TextWrapped = true

local plr = game:GetService("Players").LocalPlayer
local charr = game:GetService("Players").LocalPlayer.Character
local players = game:GetService("Players"):GetPlayers()
local gameid = game.PlaceId

print("\nExecuted.")

plr.Chatted:connect(function(message)
	if message:sub(1,3) == "$id" then
		id = message:sub(5)
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

	if message:sub(1,3) == "$bp" then

		id = message:sub(5)

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
	if message:sub(1,3) == "$rj" then
		game:GetService("TeleportService"):Teleport(gameid, plr);
	end

	if message:sub(1,3) == "$tp" then 

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

	end
	if message:sub(1,4) == "$tpa" then

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

	if message:sub(1,3) == "$re" then
		charr:BreakJoints()
	end

	if message:sub(1,4) == "$off" then
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

	if message:sub(1,5) == "$mute" then
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

	if message:sub(1,7) == "$steal" then 
		for _,v in pairs(game.workspace:GetChildren()) do
			if v:IsA("Tool") then
				v.Handle.CFrame = plr.Character.Head.CFrame
			end
		end
	end

	if message:sub(1,8) == "$lowhold" then
		if plr.Character:FindFirstChild("Animate").Disabled == true then return end
		plr.Character.Humanoid:UnequipTools()

		plr.Character:FindFirstChild("Animate"):FindFirstChild("toolnone"):FindFirstChild("ToolNoneAnim").AnimationId = "nil"		
		plr.Character.Humanoid:UnequipTools()

		for _,t in pairs(plr.Backpack:GetChildren()) do
			if t:IsA("Tool") and t:FindFirstChild("Handle") and t:FindFirstChild("Handle"):FindFirstChild("Sound") then
				t.GripForward = Vector3.new(1, -1, 0)
				t.GripPos = Vector3.new(-0, 0.855, 0)
				t.GripRight = Vector3.new(0.1, 0, 2)
				t.GripUp = Vector3.new(1, 0, 0)
				t.Handle.Massless = true
				t.Parent = plr.Character
			end
		end	
	end
end)
