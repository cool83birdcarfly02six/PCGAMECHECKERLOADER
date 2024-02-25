-- Gui to Lua
-- Version: 3.2

-- Instances:

local loader123 = Instance.new("ScreenGui")
local Frame = Instance.new("ImageButton")
local ImageLabel = Instance.new("ImageLabel")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local Executions = Instance.new("Frame")
local ImageLabel_2 = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Showcases = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local ImageLabel_3 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Prems = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local ImageLabel_4 = Instance.new("ImageLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local Members = Instance.new("Frame")
local UICorner_5 = Instance.new("UICorner")
local ImageLabel_5 = Instance.new("ImageLabel")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local LoadingImage = Instance.new("ImageLabel")
local tick = Instance.new("ImageLabel")
local eror = Instance.new("ImageLabel")
local CheckingGame = Instance.new("TextLabel")
local keepthis = Instance.new("Frame")

--Properties:

loader123.Name = "loader123"
loader123.Parent = game.CoreGui
loader123.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Name = "Frame"
Frame.Parent = loader123
Frame.Active = false
Frame.BackgroundColor3 = Color3.fromRGB(11, 19, 31)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.451473653, 0, 0.427715003, 0)
Frame.Selectable = false
Frame.Size = UDim2.new(0, 148, 0, 101)

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(-0.404402435, 0, -0.551472604, 0)
ImageLabel.Size = UDim2.new(0, 314, 0, 240)
ImageLabel.Image = "http://www.roblox.com/asset/?id=15229583503"
ImageLabel.ScaleType = Enum.ScaleType.Crop

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = ImageLabel
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow.Size = UDim2.new(1, 47, 1, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6015897843"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = ImageLabel

Executions.Name = "Executions"
Executions.Parent = ImageLabel
Executions.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Executions.BorderColor3 = Color3.fromRGB(0, 0, 0)
Executions.BorderSizePixel = 0
Executions.Position = UDim2.new(0.0541401282, 0, 0.518627405, 0)
Executions.Size = UDim2.new(0, 135, 0, 49)

ImageLabel_2.Parent = Executions
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Position = UDim2.new(0.0416666679, 0, 0.128044277, 0)
ImageLabel_2.Size = UDim2.new(0, 36, 0, 36)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=15230360934"
ImageLabel_2.ImageColor3 = Color3.fromRGB(85, 170, 255)

TextLabel.Parent = Executions
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.308333337, 0, 0.128044277, 0)
TextLabel.Size = UDim2.new(0, 92, 0, 18)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "Executions"
TextLabel.TextColor3 = Color3.fromRGB(152, 152, 152)
TextLabel.TextSize = 13.000
TextLabel.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_2.Parent = Executions
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.308333337, 0, 0.49539122, 0)
TextLabel_2.Size = UDim2.new(0, 92, 0, 18)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "100k+"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 16.000
TextLabel_2.TextYAlignment = Enum.TextYAlignment.Top

UICorner_2.CornerRadius = UDim.new(0, 5)
UICorner_2.Parent = Executions

Showcases.Name = "Showcases"
Showcases.Parent = ImageLabel
Showcases.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Showcases.BorderColor3 = Color3.fromRGB(0, 0, 0)
Showcases.BorderSizePixel = 0
Showcases.Position = UDim2.new(0.512738824, 0, 0.518627405, 0)
Showcases.Size = UDim2.new(0, 135, 0, 49)

UICorner_3.CornerRadius = UDim.new(0, 5)
UICorner_3.Parent = Showcases

ImageLabel_3.Parent = Showcases
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_3.BackgroundTransparency = 1.000
ImageLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_3.BorderSizePixel = 0
ImageLabel_3.Position = UDim2.new(0.0416666679, 0, 0.128044277, 0)
ImageLabel_3.Size = UDim2.new(0, 36, 0, 36)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=15230413419"
ImageLabel_3.ImageColor3 = Color3.fromRGB(85, 170, 255)

TextLabel_3.Parent = Showcases
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.308333337, 0, 0.128044277, 0)
TextLabel_3.Size = UDim2.new(0, 92, 0, 18)
TextLabel_3.Font = Enum.Font.SourceSansBold
TextLabel_3.Text = "Showcases"
TextLabel_3.TextColor3 = Color3.fromRGB(152, 152, 152)
TextLabel_3.TextSize = 13.000
TextLabel_3.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_4.Parent = Showcases
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.308333337, 0, 0.49539122, 0)
TextLabel_4.Size = UDim2.new(0, 92, 0, 18)
TextLabel_4.Font = Enum.Font.SourceSansBold
TextLabel_4.Text = "300+"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 16.000
TextLabel_4.TextYAlignment = Enum.TextYAlignment.Top

Prems.Name = "Prems"
Prems.Parent = ImageLabel
Prems.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Prems.BorderColor3 = Color3.fromRGB(0, 0, 0)
Prems.BorderSizePixel = 0
Prems.Position = UDim2.new(0.512738824, 0, 0.751225531, 0)
Prems.Size = UDim2.new(0, 135, 0, 49)

UICorner_4.CornerRadius = UDim.new(0, 5)
UICorner_4.Parent = Prems

ImageLabel_4.Parent = Prems
ImageLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_4.BackgroundTransparency = 1.000
ImageLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_4.BorderSizePixel = 0
ImageLabel_4.Position = UDim2.new(0.0416666679, 0, 0.128044277, 0)
ImageLabel_4.Size = UDim2.new(0, 36, 0, 36)
ImageLabel_4.Image = "http://www.roblox.com/asset/?id=15590537734"
ImageLabel_4.ImageColor3 = Color3.fromRGB(85, 170, 255)

TextLabel_5.Parent = Prems
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.308333337, 0, 0.128044277, 0)
TextLabel_5.Size = UDim2.new(0, 92, 0, 18)
TextLabel_5.Font = Enum.Font.SourceSansBold
TextLabel_5.Text = "Premiums"
TextLabel_5.TextColor3 = Color3.fromRGB(152, 152, 152)
TextLabel_5.TextSize = 13.000
TextLabel_5.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_6.Parent = Prems
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.BorderSizePixel = 0
TextLabel_6.Position = UDim2.new(0.308333337, 0, 0.49539122, 0)
TextLabel_6.Size = UDim2.new(0, 92, 0, 18)
TextLabel_6.Font = Enum.Font.SourceSansBold
TextLabel_6.Text = "10+"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextSize = 16.000
TextLabel_6.TextYAlignment = Enum.TextYAlignment.Top

Members.Name = "Members"
Members.Parent = ImageLabel
Members.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Members.BorderColor3 = Color3.fromRGB(0, 0, 0)
Members.BorderSizePixel = 0
Members.Position = UDim2.new(0.0541401282, 0, 0.751225531, 0)
Members.Size = UDim2.new(0, 135, 0, 49)

UICorner_5.CornerRadius = UDim.new(0, 5)
UICorner_5.Parent = Members

ImageLabel_5.Parent = Members
ImageLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_5.BackgroundTransparency = 1.000
ImageLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_5.BorderSizePixel = 0
ImageLabel_5.Position = UDim2.new(0.0416666679, 0, 0.128044277, 0)
ImageLabel_5.Size = UDim2.new(0, 36, 0, 36)
ImageLabel_5.Image = "http://www.roblox.com/asset/?id=15230425309"
ImageLabel_5.ImageColor3 = Color3.fromRGB(85, 170, 255)

TextLabel_7.Parent = Members
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.BorderSizePixel = 0
TextLabel_7.Position = UDim2.new(0.308333337, 0, 0.128044277, 0)
TextLabel_7.Size = UDim2.new(0, 92, 0, 18)
TextLabel_7.Font = Enum.Font.SourceSansBold
TextLabel_7.Text = "Members"
TextLabel_7.TextColor3 = Color3.fromRGB(152, 152, 152)
TextLabel_7.TextSize = 13.000
TextLabel_7.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_8.Parent = Members
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_8.BorderSizePixel = 0
TextLabel_8.Position = UDim2.new(0.308333337, 0, 0.49539122, 0)
TextLabel_8.Size = UDim2.new(0, 92, 0, 18)
TextLabel_8.Font = Enum.Font.SourceSansBold
TextLabel_8.Text = "25k+"
TextLabel_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.TextSize = 16.000
TextLabel_8.TextYAlignment = Enum.TextYAlignment.Top

LoadingImage.Name = "LoadingImage"
LoadingImage.Parent = ImageLabel
LoadingImage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LoadingImage.BackgroundTransparency = 1.000
LoadingImage.Position = UDim2.new(0.428899109, 0, 0.0831687897, 0)
LoadingImage.Size = UDim2.new(0, 44, 0, 44)
LoadingImage.ZIndex = 3
LoadingImage.Image = "http://www.roblox.com/asset/?id=12072026346"
LoadingImage.ImageColor3 = Color3.fromRGB(0, 136, 255)

tick.Name = "tick"
tick.Parent = ImageLabel
tick.BackgroundColor3 = Color3.fromRGB(0, 136, 255)
tick.BackgroundTransparency = 1.000
tick.Position = UDim2.new(0.42899999, 0, 0.0829999968, 0)
tick.Size = UDim2.new(0, 44, 0, 44)
tick.Visible = false
tick.ZIndex = 2
tick.Image = "http://www.roblox.com/asset/?id=12072072258"
tick.ImageColor3 = Color3.fromRGB(0, 136, 255)

eror.Name = "eror"
eror.Parent = ImageLabel
eror.BackgroundColor3 = Color3.fromRGB(0, 136, 255)
eror.BackgroundTransparency = 1.000
eror.Position = UDim2.new(0.42899999, 0, 0.0829999968, 0)
eror.Size = UDim2.new(0, 44, 0, 44)
eror.Visible = false
eror.ZIndex = 2
eror.Image = "http://www.roblox.com/asset/?id=12072094876"
eror.ImageColor3 = Color3.fromRGB(0, 136, 255)

CheckingGame.Name = "CheckingGame"
CheckingGame.Parent = ImageLabel
CheckingGame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CheckingGame.BackgroundTransparency = 1.000
CheckingGame.Position = UDim2.new(0.148752198, 0, 0.321965545, 0)
CheckingGame.Size = UDim2.new(0, 219, 0, 27)
CheckingGame.ZIndex = 3
CheckingGame.Font = Enum.Font.SourceSansBold
CheckingGame.Text = "Checking Game"
CheckingGame.TextColor3 = Color3.fromRGB(255, 255, 255)
CheckingGame.TextSize = 20.000

keepthis.Name = "keepthis"
keepthis.Parent = Frame
keepthis.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
keepthis.Visible = false

-- Scripts:

local function FKLHG_fake_script() -- LoadingImage.LocalScript 
	local script = Instance.new('LocalScript', LoadingImage)

	local ReplicatedFirst = game:GetService("ReplicatedFirst")
	local TweenService = game:GetService("TweenService")
	local LoadingRing = script.Parent



	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.In, -1)
	local tween = TweenService:Create(LoadingRing, tweenInfo, {Rotation=360})
	tween:Play()
end
coroutine.wrap(FKLHG_fake_script)()
local function JCMZ_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)


	wait(3)


	--loadstring
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/Action/main/README.md'),true))()
	---

	if game.CoreGui.loader123.Frame.keepthis.BackgroundTransparency == 1 then
		script.Parent.ImageLabel.CheckingGame.Text = "Game supported"


		wait(1.5)
		script.Parent.ImageLabel.CheckingGame.Text = "Loading script"

		wait(1)

		script.Parent.ImageLabel.LoadingImage.Visible = false

		script.Parent.ImageLabel.tick.Visible = true

		wait(1)

		loader123:Destroy()

		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/GAMESUPDATE/main/README.md'),true))()

	else
		script.Parent.ImageLabel.CheckingGame.Text = "Game unsupported"
		script.Parent.ImageLabel.LoadingImage.Visible = false
		script.Parent.ImageLabel.eror.Visible = true
		wait(3)
		script.Parent.Parent:Destroy()
	end
end
coroutine.wrap(JCMZ_fake_script)()
