--Aegis Version 0.8.2


local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Home = Instance.new("Frame")
local speed = Instance.new("Folder")
local SliderBar = Instance.new("Frame")
local SliderHandle = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local Name = Instance.new("TextLabel")
local jump = Instance.new("Folder")
local SliderBar_2 = Instance.new("Frame")
local SliderHandle_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextBox_2 = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")
local UICorner_6 = Instance.new("UICorner")
local Name_2 = Instance.new("TextLabel")
local ToggleFLight = Instance.new("Folder")
local TextButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Name_3 = Instance.new("TextLabel")
local ToggleNoclip = Instance.new("Folder")
local TextButton_2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local Name_4 = Instance.new("TextLabel")
local Info = Instance.new("Folder")
local Frame = Instance.new("Frame")
local Hr12 = Instance.new("TextButton")
local Hr24 = Instance.new("TextButton")
local Sec = Instance.new("TextButton")
local Date = Instance.new("TextLabel")
local Time = Instance.new("TextLabel")
local UserProfile = Instance.new("ImageLabel")
local UICorner_9 = Instance.new("UICorner")
local Name_5 = Instance.new("TextLabel")
local Name_6 = Instance.new("TextLabel")
local UICorner_10 = Instance.new("UICorner")
local UICorner_11 = Instance.new("UICorner")
local Name_7 = Instance.new("TextLabel")
local Info_2 = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local PressLeftAlt = Instance.new("TextLabel")
local credits = Instance.new("TextLabel")
local Version = Instance.new("TextLabel")
local HomeButton = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local MainButton = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local OtherButton = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local InfoButton = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Other = Instance.new("Frame")
local UICorner_17 = Instance.new("UICorner")
local Killgui = Instance.new("Folder")
local KillUI = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local Theme = Instance.new("Folder")
local ChangeTheme = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local ThemeLabel = Instance.new("TextLabel")
local Name_8 = Instance.new("TextLabel")
local Main = Instance.new("Frame")
local csfe = Instance.new("Frame")
local CSB = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local FEB = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local CS = Instance.new("Frame")
local CS_2 = Instance.new("ScrollingFrame")
local ShadowRunner = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local Name_9 = Instance.new("TextLabel")
local NightVision = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local Name_10 = Instance.new("TextLabel")
local HighMode = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local Name_11 = Instance.new("TextLabel")
local FE = Instance.new("Frame")
local FE_2 = Instance.new("ScrollingFrame")
local Astronaut = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local Name_12 = Instance.new("TextLabel")
local UICorner_26 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.fromRGB(150, 150, 150)
MainFrame.BackgroundTransparency = 0.235
MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.162562802, 0, 0.224743411, 0)
MainFrame.Size = UDim2.new(0, 425, 0, 258)

Home.Name = "Home"
Home.Parent = MainFrame
Home.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
Home.BackgroundTransparency = 0.700
Home.BorderColor3 = Color3.fromRGB(0, 0, 0)
Home.BorderSizePixel = 0
Home.Position = UDim2.new(0.214891866, 0, 0.0232558139, 0)
Home.Size = UDim2.new(0, 327, 0, 245)

speed.Name = "speed"
speed.Parent = Home

SliderBar.Name = "SliderBar"
SliderBar.Parent = speed
SliderBar.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
SliderBar.BackgroundTransparency = 0.500
SliderBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
SliderBar.BorderSizePixel = 0
SliderBar.Position = UDim2.new(0.344036698, -100, 0.0632653087, 0)
SliderBar.Size = UDim2.new(0, 131, 0, 10)

SliderHandle.Name = "SliderHandle"
SliderHandle.Parent = SliderBar
SliderHandle.BackgroundColor3 = Color3.fromRGB(139, 141, 146)
SliderHandle.BorderColor3 = Color3.fromRGB(0, 0, 0)
SliderHandle.BorderSizePixel = 0
SliderHandle.Position = UDim2.new(0, 0, 0.5, -7)
SliderHandle.Size = UDim2.new(0, 15, 0, 15)
SliderHandle.Font = Enum.Font.SourceSans
SliderHandle.Text = ""
SliderHandle.TextColor3 = Color3.fromRGB(0, 0, 0)
SliderHandle.TextSize = 14.000

UICorner.Parent = SliderHandle

TextBox.Parent = SliderBar
TextBox.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
TextBox.BackgroundTransparency = 0.500
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(1.17557251, 0, 0, 0)
TextBox.Size = UDim2.new(0, 44, 0, 10)
TextBox.Font = Enum.Font.Unknown
TextBox.PlaceholderText = "AnySpeed"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 3)
UICorner_2.Parent = TextBox

UICorner_3.Parent = SliderBar

Name.Name = "Name"
Name.Parent = speed
Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name.BackgroundTransparency = 1.000
Name.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name.BorderSizePixel = 0
Name.Position = UDim2.new(0, 228, 0, 15)
Name.Size = UDim2.new(0, 91, 0, 13)
Name.Font = Enum.Font.SourceSans
Name.Text = "Change Walkspeed"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextScaled = true
Name.TextSize = 13.000
Name.TextWrapped = true
Name.TextXAlignment = Enum.TextXAlignment.Left

jump.Name = "jump"
jump.Parent = Home

SliderBar_2.Name = "SliderBar"
SliderBar_2.Parent = jump
SliderBar_2.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
SliderBar_2.BackgroundTransparency = 0.500
SliderBar_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SliderBar_2.BorderSizePixel = 0
SliderBar_2.Position = UDim2.new(0.344036698, -100, 0.18571429, 0)
SliderBar_2.Size = UDim2.new(0, 131, 0, 10)

SliderHandle_2.Name = "SliderHandle"
SliderHandle_2.Parent = SliderBar_2
SliderHandle_2.BackgroundColor3 = Color3.fromRGB(139, 141, 146)
SliderHandle_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SliderHandle_2.BorderSizePixel = 0
SliderHandle_2.Position = UDim2.new(0, 0, 0.5, -7)
SliderHandle_2.Size = UDim2.new(0, 15, 0, 15)
SliderHandle_2.Font = Enum.Font.SourceSans
SliderHandle_2.Text = ""
SliderHandle_2.TextColor3 = Color3.fromRGB(0, 0, 0)
SliderHandle_2.TextSize = 14.000

UICorner_4.Parent = SliderHandle_2

TextBox_2.Parent = SliderBar_2
TextBox_2.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
TextBox_2.BackgroundTransparency = 0.500
TextBox_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.BorderSizePixel = 0
TextBox_2.Position = UDim2.new(1.17557251, 0, 0, 0)
TextBox_2.Size = UDim2.new(0, 44, 0, 10)
TextBox_2.Font = Enum.Font.Unknown
TextBox_2.PlaceholderText = "AnyHeight"
TextBox_2.Text = ""
TextBox_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_2.TextScaled = true
TextBox_2.TextSize = 14.000
TextBox_2.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 3)
UICorner_5.Parent = TextBox_2

UICorner_6.Parent = SliderBar_2

Name_2.Name = "Name"
Name_2.Parent = jump
Name_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_2.BackgroundTransparency = 1.000
Name_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_2.BorderSizePixel = 0
Name_2.Position = UDim2.new(0, 228, 0, 44)
Name_2.Size = UDim2.new(0, 91, 0, 13)
Name_2.Font = Enum.Font.SourceSans
Name_2.Text = "Change JumpHight"
Name_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_2.TextScaled = true
Name_2.TextSize = 13.000
Name_2.TextWrapped = true
Name_2.TextXAlignment = Enum.TextXAlignment.Left

ToggleFLight.Name = "Toggle FLight"
ToggleFLight.Parent = Home

TextButton.Parent = ToggleFLight
TextButton.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
TextButton.BackgroundTransparency = 0.500
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0519877672, 0, 0.306122452, 0)
TextButton.Size = UDim2.new(0, 122, 0, 36)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Off"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_7.Parent = TextButton

Name_3.Name = "Name"
Name_3.Parent = ToggleFLight
Name_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_3.BackgroundTransparency = 1.000
Name_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_3.BorderSizePixel = 0
Name_3.Position = UDim2.new(0, 157, 0, 80)
Name_3.Size = UDim2.new(0, 153, 0, 25)
Name_3.Font = Enum.Font.SourceSans
Name_3.Text = "Toggle F to Fly"
Name_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_3.TextScaled = true
Name_3.TextSize = 13.000
Name_3.TextWrapped = true
Name_3.TextXAlignment = Enum.TextXAlignment.Left

ToggleNoclip.Name = "Toggle Noclip"
ToggleNoclip.Parent = Home

TextButton_2.Parent = ToggleNoclip
TextButton_2.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
TextButton_2.BackgroundTransparency = 0.500
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0519877672, 0, 0.534693897, 0)
TextButton_2.Size = UDim2.new(0, 122, 0, 36)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Off"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

UICorner_8.Parent = TextButton_2

Name_4.Name = "Name"
Name_4.Parent = ToggleNoclip
Name_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_4.BackgroundTransparency = 1.000
Name_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_4.BorderSizePixel = 0
Name_4.Position = UDim2.new(0, 157, 0, 136)
Name_4.Size = UDim2.new(0, 153, 0, 25)
Name_4.Font = Enum.Font.SourceSans
Name_4.Text = "Toggle N for Noclip"
Name_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_4.TextScaled = true
Name_4.TextSize = 13.000
Name_4.TextWrapped = true
Name_4.TextXAlignment = Enum.TextXAlignment.Left

Info.Name = "Info"
Info.Parent = Home

Frame.Parent = Info
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.860419214, -125, 0.707468987, 20)
Frame.Size = UDim2.new(0, 153, 0, 32)

Hr12.Name = "Hr12"
Hr12.Parent = Frame
Hr12.BackgroundTransparency = 1.000
Hr12.BorderColor3 = Color3.fromRGB(27, 42, 53)
Hr12.BorderSizePixel = 0
Hr12.Position = UDim2.new(0, 0, 1, 10)
Hr12.Size = UDim2.new(0.25, 0, 0, 20)
Hr12.AutoButtonColor = false
Hr12.Font = Enum.Font.ArialBold
Hr12.Text = "12 Hr"
Hr12.TextColor3 = Color3.fromRGB(255, 255, 255)
Hr12.TextSize = 12.000
Hr12.TextTransparency = 1.000

Hr24.Name = "Hr24"
Hr24.Parent = Frame
Hr24.BackgroundTransparency = 1.000
Hr24.BorderColor3 = Color3.fromRGB(27, 42, 53)
Hr24.BorderSizePixel = 0
Hr24.Position = UDim2.new(0.25, 0, 1, 10)
Hr24.Size = UDim2.new(0.25, 0, 0, 20)
Hr24.AutoButtonColor = false
Hr24.Font = Enum.Font.ArialBold
Hr24.Text = "24 Hr"
Hr24.TextColor3 = Color3.fromRGB(255, 255, 255)
Hr24.TextSize = 12.000
Hr24.TextTransparency = 1.000

Sec.Name = "Sec"
Sec.Parent = Frame
Sec.BackgroundTransparency = 1.000
Sec.BorderColor3 = Color3.fromRGB(27, 42, 53)
Sec.BorderSizePixel = 0
Sec.Position = UDim2.new(0.75, 0, 1, 10)
Sec.Size = UDim2.new(0.25, 0, 0, 20)
Sec.AutoButtonColor = false
Sec.Font = Enum.Font.ArialBold
Sec.Text = "Seconds"
Sec.TextColor3 = Color3.fromRGB(255, 255, 255)
Sec.TextSize = 12.000
Sec.TextTransparency = 1.000

Date.Name = "Date"
Date.Parent = Frame
Date.BackgroundTransparency = 1.000
Date.BorderColor3 = Color3.fromRGB(27, 42, 53)
Date.Position = UDim2.new(0.5, 0, 0.899999976, 0)
Date.Font = Enum.Font.SourceSansBold
Date.Text = "January 1, 1970"
Date.TextColor3 = Color3.fromRGB(255, 255, 255)
Date.TextSize = 14.000
Date.TextTransparency = 1.000

Time.Name = "Time"
Time.Parent = Frame
Time.BackgroundTransparency = 1.000
Time.BorderColor3 = Color3.fromRGB(27, 42, 53)
Time.Position = UDim2.new(0.5, 0, 0.25, 0)
Time.Font = Enum.Font.SourceSansBold
Time.Text = "12:00:00 AM"
Time.TextColor3 = Color3.fromRGB(255, 255, 255)
Time.TextSize = 36.000
Time.TextTransparency = 1.000

UserProfile.Name = "UserProfile"
UserProfile.Parent = Info
UserProfile.BackgroundColor3 = Color3.fromRGB(154, 154, 154)
UserProfile.BackgroundTransparency = 0.700
UserProfile.BorderColor3 = Color3.fromRGB(0, 0, 0)
UserProfile.BorderSizePixel = 2
UserProfile.Position = UDim2.new(0.0219999999, 0, 0.748000026, 0)
UserProfile.Selectable = true
UserProfile.Size = UDim2.new(0.163766101, 0, 0.220151067, 0)
UserProfile.ScaleType = Enum.ScaleType.Fit

UICorner_9.Parent = UserProfile

Name_5.Name = "Name"
Name_5.Parent = Info
Name_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_5.BackgroundTransparency = 1.000
Name_5.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_5.BorderSizePixel = 0
Name_5.Position = UDim2.new(0, 69, 0, 204)
Name_5.Size = UDim2.new(0, 142, 0, 31)
Name_5.Font = Enum.Font.SourceSans
Name_5.Text = "Player"
Name_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_5.TextSize = 20.000
Name_5.TextWrapped = true
Name_5.TextXAlignment = Enum.TextXAlignment.Left

Name_6.Name = "Name"
Name_6.Parent = Name_5
Name_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_6.BackgroundTransparency = 1.000
Name_6.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_6.BorderSizePixel = 0
Name_6.Position = UDim2.new(0, 0, 0, -22)
Name_6.Size = UDim2.new(0, 88, 0, 31)
Name_6.Font = Enum.Font.SourceSans
Name_6.Text = "Welcome,"
Name_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_6.TextSize = 20.000
Name_6.TextWrapped = true
Name_6.TextXAlignment = Enum.TextXAlignment.Left

UICorner_10.Parent = Home

UICorner_11.Parent = MainFrame

Name_7.Name = "Name"
Name_7.Parent = MainFrame
Name_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_7.BackgroundTransparency = 1.000
Name_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Name_7.BorderSizePixel = 0
Name_7.Position = UDim2.new(0.0179947447, 0, 0.0183720551, 0)
Name_7.Size = UDim2.new(0, 57, 0, 26)
Name_7.Font = Enum.Font.SourceSans
Name_7.Text = "AEGIS"
Name_7.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_7.TextSize = 22.000
Name_7.TextWrapped = true

Info_2.Name = "Info"
Info_2.Parent = MainFrame
Info_2.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
Info_2.BackgroundTransparency = 0.700
Info_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Info_2.BorderSizePixel = 0
Info_2.Position = UDim2.new(0.214891866, 0, 0.0232558139, 0)
Info_2.Size = UDim2.new(0, 327, 0, 245)
Info_2.Visible = false

UICorner_12.Parent = Info_2

PressLeftAlt.Name = "Press  LeftAlt"
PressLeftAlt.Parent = Info_2
PressLeftAlt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PressLeftAlt.BackgroundTransparency = 1.000
PressLeftAlt.BorderColor3 = Color3.fromRGB(0, 0, 0)
PressLeftAlt.BorderSizePixel = 0
PressLeftAlt.Position = UDim2.new(0.0395059846, 0, 0.00692935847, 0)
PressLeftAlt.Size = UDim2.new(0, 178, 0, 19)
PressLeftAlt.Font = Enum.Font.SourceSans
PressLeftAlt.Text = "Press LeftAlt  to open / close"
PressLeftAlt.TextColor3 = Color3.fromRGB(255, 255, 255)
PressLeftAlt.TextSize = 15.000
PressLeftAlt.TextWrapped = true
PressLeftAlt.TextXAlignment = Enum.TextXAlignment.Left

credits.Name = "credits"
credits.Parent = Info_2
credits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
credits.BackgroundTransparency = 1.000
credits.BorderColor3 = Color3.fromRGB(0, 0, 0)
credits.BorderSizePixel = 0
credits.Position = UDim2.new(0.728122175, 0, 0.00692923414, 0)
credits.Size = UDim2.new(0, 106, 0, 19)
credits.Font = Enum.Font.SourceSans
credits.Text = "@sypcer on dc"
credits.TextColor3 = Color3.fromRGB(255, 255, 255)
credits.TextSize = 15.000
credits.TextWrapped = true
credits.TextXAlignment = Enum.TextXAlignment.Left

Version.Name = "Version"
Version.Parent = Info_2
Version.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Version.BackgroundTransparency = 1.000
Version.BorderColor3 = Color3.fromRGB(0, 0, 0)
Version.BorderSizePixel = 0
Version.Position = UDim2.new(0.899999976, 0, 0.899999976, 0)
Version.Size = UDim2.new(0, 27, 0, 17)
Version.Font = Enum.Font.SourceSans
Version.Text = "V0.8.3"
Version.TextColor3 = Color3.fromRGB(255, 255, 255)
Version.TextScaled = true
Version.TextSize = 26.000
Version.TextWrapped = true
Version.TextXAlignment = Enum.TextXAlignment.Left

HomeButton.Name = "HomeButton"
HomeButton.Parent = MainFrame
HomeButton.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
HomeButton.BackgroundTransparency = 0.600
HomeButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
HomeButton.BorderSizePixel = 0
HomeButton.Position = UDim2.new(0.0179948583, 0, 0.124031007, 0)
HomeButton.Size = UDim2.new(0, 77, 0, 49)
HomeButton.Font = Enum.Font.SourceSans
HomeButton.Text = "Home"
HomeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
HomeButton.TextSize = 19.000

UICorner_13.Parent = HomeButton

MainButton.Name = "MainButton"
MainButton.Parent = MainFrame
MainButton.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
MainButton.BackgroundTransparency = 0.600
MainButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainButton.BorderSizePixel = 0
MainButton.Position = UDim2.new(0.0179948583, 0, 0.342803478, 0)
MainButton.Size = UDim2.new(0, 77, 0, 49)
MainButton.Font = Enum.Font.SourceSans
MainButton.Text = "Main"
MainButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MainButton.TextSize = 19.000

UICorner_14.Parent = MainButton

OtherButton.Name = "OtherButton"
OtherButton.Parent = MainFrame
OtherButton.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
OtherButton.BackgroundTransparency = 0.600
OtherButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
OtherButton.BorderSizePixel = 0
OtherButton.Position = UDim2.new(0.0179948583, 0, 0.561575949, 0)
OtherButton.Size = UDim2.new(0, 77, 0, 49)
OtherButton.Font = Enum.Font.SourceSans
OtherButton.Text = "Other"
OtherButton.TextColor3 = Color3.fromRGB(255, 255, 255)
OtherButton.TextSize = 19.000

UICorner_15.Parent = OtherButton

InfoButton.Name = "InfoButton"
InfoButton.Parent = MainFrame
InfoButton.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
InfoButton.BackgroundTransparency = 0.600
InfoButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
InfoButton.BorderSizePixel = 0
InfoButton.Position = UDim2.new(0.0179948583, 0, 0.78034842, 0)
InfoButton.Size = UDim2.new(0, 77, 0, 49)
InfoButton.Font = Enum.Font.SourceSans
InfoButton.Text = "Info"
InfoButton.TextColor3 = Color3.fromRGB(255, 255, 255)
InfoButton.TextSize = 19.000

UICorner_16.Parent = InfoButton

Other.Name = "Other"
Other.Parent = MainFrame
Other.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
Other.BackgroundTransparency = 0.700
Other.BorderColor3 = Color3.fromRGB(0, 0, 0)
Other.BorderSizePixel = 0
Other.Position = UDim2.new(0.214891866, 0, 0.0232558139, 0)
Other.Size = UDim2.new(0, 327, 0, 245)
Other.Visible = false

UICorner_17.Parent = Other

Killgui.Name = "Kill gui"
Killgui.Parent = Other

KillUI.Name = "KillUI"
KillUI.Parent = Killgui
KillUI.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
KillUI.BackgroundTransparency = 0.500
KillUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
KillUI.BorderSizePixel = 0
KillUI.Position = UDim2.new(0.663254678, 0, 0.765657663, 0)
KillUI.Size = UDim2.new(0, 98, 0, 49)
KillUI.Font = Enum.Font.SourceSans
KillUI.Text = "KillUI"
KillUI.TextColor3 = Color3.fromRGB(255, 255, 255)
KillUI.TextSize = 19.000

UICorner_18.Parent = KillUI

Theme.Name = "Theme"
Theme.Parent = Other

ChangeTheme.Name = "ChangeTheme"
ChangeTheme.Parent = Theme
ChangeTheme.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
ChangeTheme.BackgroundTransparency = 0.500
ChangeTheme.BorderColor3 = Color3.fromRGB(0, 0, 0)
ChangeTheme.BorderSizePixel = 0
ChangeTheme.Position = UDim2.new(0.0241109394, 0, 0.030963758, 0)
ChangeTheme.Size = UDim2.new(0, 194, 0, 49)
ChangeTheme.Font = Enum.Font.SourceSans
ChangeTheme.Text = "Change Theme"
ChangeTheme.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeTheme.TextSize = 19.000

UICorner_19.Parent = ChangeTheme

ThemeLabel.Name = "ThemeLabel"
ThemeLabel.Parent = Theme
ThemeLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ThemeLabel.BackgroundTransparency = 1.000
ThemeLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ThemeLabel.BorderSizePixel = 0
ThemeLabel.Position = UDim2.new(0.647292197, 0, 0.0763171166, 0)
ThemeLabel.Size = UDim2.new(0, 104, 0, 28)
ThemeLabel.Font = Enum.Font.SourceSans
ThemeLabel.Text = "ThemeLabel"
ThemeLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
ThemeLabel.TextScaled = true
ThemeLabel.TextSize = 26.000
ThemeLabel.TextWrapped = true

Name_8.Name = "Name"
Name_8.Parent = MainFrame
Name_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_8.BackgroundTransparency = 1.000
Name_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Name_8.BorderSizePixel = 0
Name_8.Position = UDim2.new(0.130999997, 0, 0.0299999993, 0)
Name_8.Size = UDim2.new(0, 30, 0, 13)
Name_8.Font = Enum.Font.SourceSans
Name_8.Text = "beta"
Name_8.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_8.TextScaled = true
Name_8.TextSize = 22.000
Name_8.TextWrapped = true

Main.Name = "Main"
Main.Parent = MainFrame
Main.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
Main.BackgroundTransparency = 1.000
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.215000004, 0, 0.023, 0)
Main.Size = UDim2.new(0, 327, 0, 245)
Main.Visible = false

csfe.Name = "csfe"
csfe.Parent = Main
csfe.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
csfe.BackgroundTransparency = 1.000
csfe.BorderColor3 = Color3.fromRGB(0, 0, 0)
csfe.BorderSizePixel = 0
csfe.Position = UDim2.new(-0.00223347615, 0, -0.00531553943, 0)
csfe.Size = UDim2.new(0, 327, 0, 245)

CSB.Name = "CSB"
CSB.Parent = csfe
CSB.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
CSB.BackgroundTransparency = 0.600
CSB.BorderColor3 = Color3.fromRGB(0, 0, 0)
CSB.BorderSizePixel = 0
CSB.Position = UDim2.new(0.018635368, 0, 0.0469676107, 0)
CSB.Size = UDim2.new(0, 142, 0, 25)
CSB.Font = Enum.Font.SourceSans
CSB.Text = "Client"
CSB.TextColor3 = Color3.fromRGB(255, 255, 255)
CSB.TextSize = 19.000

UICorner_20.Parent = CSB

FEB.Name = "FEB"
FEB.Parent = csfe
FEB.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
FEB.BackgroundTransparency = 0.600
FEB.BorderColor3 = Color3.fromRGB(0, 0, 0)
FEB.BorderSizePixel = 0
FEB.Position = UDim2.new(0.47262004, 0, 0.0469676107, 0)
FEB.Size = UDim2.new(0, 146, 0, 25)
FEB.Font = Enum.Font.SourceSans
FEB.Text = "FE"
FEB.TextColor3 = Color3.fromRGB(255, 255, 255)
FEB.TextSize = 19.000

UICorner_21.Parent = FEB

CS.Name = "CS"
CS.Parent = csfe
CS.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
CS.BackgroundTransparency = 1.000
CS.BorderColor3 = Color3.fromRGB(0, 0, 0)
CS.BorderSizePixel = 0
CS.Size = UDim2.new(0, 327, 0, 245)

CS_2.Name = "CS"
CS_2.Parent = CS
CS_2.Active = true
CS_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CS_2.BackgroundTransparency = 1.000
CS_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
CS_2.BorderSizePixel = 0
CS_2.Position = UDim2.new(0.0244648326, 0, 0.0244897958, 0)
CS_2.Size = UDim2.new(0, 313, 0, 231)

ShadowRunner.Name = "Shadow Runner"
ShadowRunner.Parent = CS_2
ShadowRunner.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
ShadowRunner.BackgroundTransparency = 0.500
ShadowRunner.BorderColor3 = Color3.fromRGB(0, 0, 0)
ShadowRunner.BorderSizePixel = 0
ShadowRunner.Position = UDim2.new(-0.00144817121, 0, 0.0769123584, 0)
ShadowRunner.Size = UDim2.new(0, 141, 0, 49)
ShadowRunner.Font = Enum.Font.SourceSans
ShadowRunner.Text = "Shadow Runner"
ShadowRunner.TextColor3 = Color3.fromRGB(255, 255, 255)
ShadowRunner.TextSize = 19.000

UICorner_22.Parent = ShadowRunner

Name_9.Name = "Name"
Name_9.Parent = ShadowRunner
Name_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_9.BackgroundTransparency = 1.000
Name_9.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_9.BorderSizePixel = 0
Name_9.Position = UDim2.new(0, 147, 0, 5)
Name_9.Size = UDim2.new(0, 147, 0, 44)
Name_9.Font = Enum.Font.SourceSans
Name_9.Text = "R to set point and tp back - can be combined with speed "
Name_9.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_9.TextScaled = true
Name_9.TextSize = 13.000
Name_9.TextWrapped = true
Name_9.TextXAlignment = Enum.TextXAlignment.Left

NightVision.Name = "Night Vision"
NightVision.Parent = CS_2
NightVision.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
NightVision.BackgroundTransparency = 0.500
NightVision.BorderColor3 = Color3.fromRGB(0, 0, 0)
NightVision.BorderSizePixel = 0
NightVision.Position = UDim2.new(-0.00144817121, 0, 0.21509549, 0)
NightVision.Size = UDim2.new(0, 141, 0, 49)
NightVision.Font = Enum.Font.SourceSans
NightVision.Text = "Night Vision"
NightVision.TextColor3 = Color3.fromRGB(255, 255, 255)
NightVision.TextSize = 19.000

UICorner_23.Parent = NightVision

Name_10.Name = "Name"
Name_10.Parent = NightVision
Name_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_10.BackgroundTransparency = 1.000
Name_10.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_10.BorderSizePixel = 0
Name_10.Position = UDim2.new(0, 147, 0, 2)
Name_10.Size = UDim2.new(0, 147, 0, 44)
Name_10.Font = Enum.Font.SourceSans
Name_10.Text = "Turn On/Off Night Vision"
Name_10.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_10.TextSize = 15.000
Name_10.TextWrapped = true
Name_10.TextXAlignment = Enum.TextXAlignment.Left

HighMode.Name = "High Mode"
HighMode.Parent = CS_2
HighMode.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
HighMode.BackgroundTransparency = 0.500
HighMode.BorderColor3 = Color3.fromRGB(0, 0, 0)
HighMode.BorderSizePixel = 0
HighMode.Position = UDim2.new(-0.00144817121, 0, 0.36228171, 0)
HighMode.Size = UDim2.new(0, 141, 0, 49)
HighMode.Font = Enum.Font.SourceSans
HighMode.Text = "High Mode"
HighMode.TextColor3 = Color3.fromRGB(255, 255, 255)
HighMode.TextSize = 19.000

UICorner_24.Parent = HighMode

Name_11.Name = "Name"
Name_11.Parent = HighMode
Name_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_11.BackgroundTransparency = 1.000
Name_11.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_11.BorderSizePixel = 0
Name_11.Position = UDim2.new(0, 147, 0, 2)
Name_11.Size = UDim2.new(0, 147, 0, 44)
Name_11.Font = Enum.Font.SourceSans
Name_11.Text = "Toggle High / might have to restart game"
Name_11.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_11.TextSize = 15.000
Name_11.TextWrapped = true
Name_11.TextXAlignment = Enum.TextXAlignment.Left

FE.Name = "FE"
FE.Parent = csfe
FE.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
FE.BackgroundTransparency = 1.000
FE.BorderColor3 = Color3.fromRGB(0, 0, 0)
FE.BorderSizePixel = 0
FE.Size = UDim2.new(0, 327, 0, 245)
FE.Visible = false

FE_2.Name = "FE"
FE_2.Parent = FE
FE_2.Active = true
FE_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FE_2.BackgroundTransparency = 1.000
FE_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
FE_2.BorderSizePixel = 0
FE_2.Position = UDim2.new(0.0244648326, 0, 0.0244897958, 0)
FE_2.Size = UDim2.new(0, 313, 0, 231)

Astronaut.Name = "Astronaut"
Astronaut.Parent = FE_2
Astronaut.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
Astronaut.BackgroundTransparency = 0.500
Astronaut.BorderColor3 = Color3.fromRGB(0, 0, 0)
Astronaut.BorderSizePixel = 0
Astronaut.Position = UDim2.new(-0.00144817121, 0, 0.0769123584, 0)
Astronaut.Size = UDim2.new(0, 141, 0, 49)
Astronaut.Font = Enum.Font.SourceSans
Astronaut.Text = "Astronaut"
Astronaut.TextColor3 = Color3.fromRGB(255, 255, 255)
Astronaut.TextSize = 19.000

UICorner_25.Parent = Astronaut

Name_12.Name = "Name"
Name_12.Parent = Astronaut
Name_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_12.BackgroundTransparency = 1.000
Name_12.BorderColor3 = Color3.fromRGB(27, 42, 53)
Name_12.BorderSizePixel = 0
Name_12.Position = UDim2.new(0, 147, 0, 5)
Name_12.Size = UDim2.new(0, 147, 0, 44)
Name_12.Font = Enum.Font.SourceSans
Name_12.Text = "Makes you float. Hold space to go upwards."
Name_12.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_12.TextScaled = true
Name_12.TextSize = 13.000
Name_12.TextWrapped = true
Name_12.TextXAlignment = Enum.TextXAlignment.Left

UICorner_26.Parent = Main

-- Scripts:

local function ISBSW_fake_script() -- SliderHandle.LocalScript 
	local script = Instance.new('LocalScript', SliderHandle)

	local sliderHandle = script.Parent
	local sliderBar = sliderHandle.Parent  -- The bar that holds the handle
	local player = game.Players.LocalPlayer
	local char = player.Character or player.CharacterAdded:Wait()
	local humanoid = char:WaitForChild("Humanoid")
	
	local minSpeed, maxSpeed = 1, 300  -- Slider WalkSpeed range
	local userInput = game:GetService("UserInputService")
	local dragging = false
	
	-- Reference to the TextBox
	local textBox = script.Parent.Parent:WaitForChild("TextBox") -- Assuming TextBox is in the parent frame of the slider
	
	-- Function to update WalkSpeed based on slider value
	local function updateWalkSpeedFromSlider()
		local sliderStart = sliderBar.AbsolutePosition.X
		local sliderEnd = sliderStart + sliderBar.AbsoluteSize.X
		local newX = sliderHandle.Position.X.Offset
		local percent = (newX - sliderStart) / sliderBar.AbsoluteSize.X
		humanoid.WalkSpeed = minSpeed + (maxSpeed - minSpeed) * percent
	
		-- Update the TextBox value to reflect the new WalkSpeed
		textBox.Text = math.floor(humanoid.WalkSpeed)
	end
	
	-- Detect when player clicks the slider
	sliderHandle.MouseButton1Down:Connect(function()
		dragging = true
	end)
	
	-- Stop dragging when mouse is released
	userInput.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)
	
	game:GetService("RunService").RenderStepped:Connect(function()
		if dragging then
			local mousePos = userInput:GetMouseLocation().X
			local sliderStart = sliderBar.AbsolutePosition.X
			local sliderEnd = sliderStart + sliderBar.AbsoluteSize.X
			local newX = math.clamp(mousePos, sliderStart, sliderEnd)
	
			local percent = (newX - sliderStart) / sliderBar.AbsoluteSize.X
			humanoid.WalkSpeed = minSpeed + (maxSpeed - minSpeed) * percent
	
			-- Move the slider handle
			sliderHandle.Position = UDim2.new(0, newX - sliderStart, 0.5, -7)
	
			-- Update the TextBox when the slider moves
			textBox.Text = math.floor(humanoid.WalkSpeed)
		end
	end)
	
	-- Update slider when TextBox value changes
	textBox.FocusLost:Connect(function()
		local newWalkSpeed = tonumber(textBox.Text)
		if newWalkSpeed then
			-- Set walk speed based on the TextBox value
			humanoid.WalkSpeed = newWalkSpeed
	
			-- Update the slider handle position based on the WalkSpeed (only for values within the slider limit)
			if newWalkSpeed <= maxSpeed then
				local percent = (newWalkSpeed - minSpeed) / (maxSpeed - minSpeed)
				local sliderStart = sliderBar.AbsolutePosition.X
				local sliderEnd = sliderStart + sliderBar.AbsoluteSize.X
				local newX = sliderStart + percent * (sliderEnd - sliderStart)
				sliderHandle.Position = UDim2.new(0, newX - sliderStart, 0.5, -7)
			end
		end
	end)
end
coroutine.wrap(ISBSW_fake_script)()
local function ICBX_fake_script() -- SliderHandle_2.LocalScript 
	local script = Instance.new('LocalScript', SliderHandle_2)

	local h = script.Parent
	local b = h.Parent
	local vBox = b:FindFirstChild("TextBox")
	local p = game.Players.LocalPlayer
	local c = p.Character or p.CharacterAdded:Wait()
	local hmn = c:WaitForChild("Humanoid")
	local rootPart = c:WaitForChild("HumanoidRootPart")
	local uis = game:GetService("UserInputService")
	
	local minJ, maxJ = 1, 300
	local d = false
	
	local function updateJump(x)
		local sX = b.AbsolutePosition.X
		local eX = sX + b.AbsoluteSize.X
		local nX = math.clamp(x, sX, eX)
	
		local percent = (nX - sX) / b.AbsoluteSize.X
		local newJumpForce = math.floor(minJ + (maxJ - minJ) * percent)
	
		-- Adjust velocity based on slider position (Y-axis of the velocity)
		rootPart.Velocity = Vector3.new(rootPart.Velocity.X, newJumpForce, rootPart.Velocity.Z)
	
		-- Update the position of the slider handle
		h.Position = UDim2.new(percent, 0, h.Position.Y.Scale, h.Position.Y.Offset)
	
		if vBox then
			vBox.Text = tostring(newJumpForce)
		end
	end
	
	h.InputBegan:Connect(function(i)
		if i.UserInputType == Enum.UserInputType.MouseButton1 then
			d = true
		end
	end)
	
	uis.InputEnded:Connect(function(i)
		if i.UserInputType == Enum.UserInputType.MouseButton1 then
			d = false
		end
	end)
	
	uis.InputChanged:Connect(function(i)
		if d and i.UserInputType == Enum.UserInputType.MouseMovement then
			updateJump(uis:GetMouseLocation().X)
		end
	end)
	
	-- Handle TextBox input
	if vBox then
		vBox.FocusLost:Connect(function()
			local input = tonumber(vBox.Text)
			if input then
				input = math.clamp(input, minJ, maxJ)
				-- Adjust velocity based on the value entered in the TextBox
				rootPart.Velocity = Vector3.new(rootPart.Velocity.X, input, rootPart.Velocity.Z)
				local percent = (input - minJ) / (maxJ - minJ)
				h.Position = UDim2.new(percent, 0, h.Position.Y.Scale, h.Position.Y.Offset)
			else
				vBox.Text = tostring(rootPart.Velocity.Y)  -- Display current jump force (velocity Y)
			end
		end)
	end
	
end
coroutine.wrap(ICBX_fake_script)()
local function IMDD_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	-- Fling mode script with button toggle functionality
	
	local btn = script.Parent
	local active = false
	
	-- Helper function to get the root part of the character
	local function getRoot(character)
		return character and character:FindFirstChild("HumanoidRootPart")
	end
	
	local function fling(speaker)
		-- Apply custom physical properties to make the player flingable
		for _, child in pairs(speaker.Character:GetDescendants()) do
			if child:IsA("BasePart") then
				child.CustomPhysicalProperties = PhysicalProperties.new(math.huge, 0.3, 0.5)
			end
		end
	
		-- Apply noclip to the player
		local function noclipLoop()
			for _, child in pairs(speaker.Character:GetDescendants()) do
				if child:IsA("BasePart") then
					child.CanCollide = false
				end
			end
		end
		noclipLoop()
	
		-- Apply BodyAngularVelocity to spin the player
		local bambam = Instance.new("BodyAngularVelocity")
		bambam.Parent = getRoot(speaker.Character)
		bambam.AngularVelocity = Vector3.new(0, 99999, 0)
		bambam.MaxTorque = Vector3.new(0, math.huge, 0)
		bambam.P = math.huge
	
		-- Make the character parts massless and reset velocity
		local charParts = speaker.Character:GetChildren()
		for _, v in pairs(charParts) do
			if v:IsA("BasePart") then
				v.CanCollide = false
				v.Massless = true
				v.Velocity = Vector3.new(0, 0, 0)
			end
		end
	end
	
	local function toggle()
		active = not active
		btn.Text = active and "ON" or "OFF"
	
		if active then
			-- Activate Fling mode
			fling(game.Players.LocalPlayer)
			print("Fling Mode Enabled")
		else
			-- Deactivate Fling mode (you can add logic to reset the changes here)
			-- Reset the character's physical properties to default, if desired.
			local char = game.Players.LocalPlayer.Character
			for _, part in pairs(char:GetDescendants()) do
				if part:IsA("BasePart") then
					part.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0) -- Reset physical properties
					part.CanCollide = true
					part.Massless = false
					part.Velocity = Vector3.new(0, 0, 0) -- Reset velocity
				end
			end
			print("Fling Mode Disabled")
		end
	end
	
	btn.MouseButton1Click:Connect(toggle)
	
end
coroutine.wrap(IMDD_fake_script)()
local function DWFNRT_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local btn = script.Parent
	local uis = game:GetService("UserInputService")
	local rs = game:GetService("RunService")
	local p = game.Players.LocalPlayer
	local c = p.Character or p.CharacterAdded:Wait()
	local hmn = c:WaitForChild("Humanoid")
	
	local toggleActive = false  
	local noclipping = false  
	
	local function startNoclip()
		if noclipping or not toggleActive then return end
		noclipping = true
	
		rs.Stepped:Connect(function()
			if noclipping and toggleActive then
				for _, v in pairs(c:GetDescendants()) do
					if v:IsA("BasePart") and v.CanCollide then
						v.CanCollide = false
					end
				end
			end
		end)
	end
	
	local function stopNoclip()
		if not noclipping then return end
		noclipping = false
		for _, v in pairs(c:GetDescendants()) do
			if v:IsA("BasePart") then
				v.CanCollide = true
			end
		end
	end
	
	uis.InputBegan:Connect(function(i, g)
		if g or not toggleActive then return end
		if i.KeyCode == Enum.KeyCode.N then
			if noclipping then stopNoclip() else startNoclip() end
		end
	end)
	
	btn.MouseButton1Click:Connect(function()
		toggleActive = not toggleActive
		btn.Text = toggleActive and "ON" or "OFF"
		if not toggleActive then stopNoclip() end
	end)
	
end
coroutine.wrap(DWFNRT_fake_script)()
local function MLODO_fake_script() -- Frame.Main 
	local script = Instance.new('LocalScript', Frame)

	wait(0)
	local t = tick()
	
	-- tick() returns the number of seconds since January 1st, 1970
	-- Because this is a LocalScript, it will return the time based on your timezone
	
	-- Don't mess with anything in the script. The constants and variables are all mixed together
	
	local Type = 0		-- Manipulated by GUI	(0 = 12 hr, 1 = 24 hr)
	local Sec = true	-- Manipulated by GUI
	
	local year = 1970
	local month = 1
	local day = 1
	local Date = "January 1, 1970"
	
	local hour = 0
	local min = 0
	local sec = 0
	local tag = "AM"
	local Time = "12:00 AM"
	
	function getDate()
		local months = {
			--		{"MONTH", TOAL DAYS TO YEAR, DAYS}	<- Format
			{"January",31,31};
			{"February",59,28};
			{"March",90,31};
			{"April",120,30};
			{"May",151,31};
			{"June",181,30};
			{"July",212,31};
			{"August",243,31};
			{"September",273,30};
			{"October",304,31};
			{"November",334,30};
			{"December",365,31};
		}
		year = math.floor(1970+(t/31579200))
		if ((year%4) == 0) then	-- Check for leap year
			months[2][3] = 29
			for i,v in pairs(months) do
				if (i ~= 1) then
					v[2] = (v[2]+1)
				end
			end
		end
		day = math.floor(((t/86400)%365.25)+1)	-- Get current day of the year. Starts at 0, so 1 is added	(365.25 is the average # of days in a year due to leap year)
		for i,m in pairs(months) do
			if ((m[2]-m[3]) <= day) then	-- Get month based on day
				month = i
			end
		end
		local m = months[month]
		day = (day+m[3]-m[2])	-- Get day of the month
		year,day = tostring(year),tostring(day)
		local c,s = ", "," "	-- Comma, space
		Date = (months[month][1] .. s .. day .. c .. year)
	end
	
	function getTime()
		local sec = math.floor((t%60))		-- Sec, Min, and Hour equations I actually got off of Google. Everything else was written by me
		local min = math.floor((t/60)%60)
		local hour = math.floor((t/3600)%24)
		sec = tostring((sec < 10 and "0" or "") .. sec)
		min = tostring((min < 10 and "0" or "") .. min)
		tag = (Type == 0 and (hour < 12 and "AM" or "PM") or "")
		hour = ((Type == 1 and hour < 10 and "0" or "") .. tostring(Type == 0 and (hour == 0 and 12 or hour > 12 and (hour-12) or hour) or hour))	-- Ternary operators FTW. Helps get rid of 'if then' stuff. Actually learned this off of Java programming:	z = (x == y ? "Yes" : "No")
		local c,s = ":",(Type == 0 and " " or "")	-- Colon, (space if 12 hr clock)
		Time = (hour .. c .. min .. (Sec and c .. sec or "") .. s .. tag)
	end
	
	function display(start)
		if (start) then
			getDate()
			getTime()
			delay(0,function()
				for i = 1,0,-0.05 do
					script.Parent.Time.TextTransparency,script.Parent.Date.TextTransparency = i,i
					wait()
				end
				script.Parent.Time.TextTransparency,script.Parent.Date.TextTransparency = 0,0.5
			end)
		end
		script.Parent.Time.Text = Time	-- ORLY?
		script.Parent.Date.Text = Date
	end
	
	function buttons()
		-- This is all the GUI handling stuff
		local h12 = script.Parent.Hr12
		local h24 = script.Parent.Hr24
		local s = script.Parent.Sec
		h12.MouseButton1Click:connect(function()
			Type = 0
			h12.Style,h24.Style = 1,2
			h12.TextTransparency,h24.TextTransparency = 0,0.5
		end)
		h24.MouseButton1Click:connect(function()
			Type = 1
			h24.Style,h12.Style = 1,2
			h24.TextTransparency,h12.TextTransparency = 0,0.5
		end)
		s.MouseButton1Click:connect(function()
			Sec = (not Sec)	-- Fastest way to switch a boolean in lua
			s.Style = (Sec and 1 or 2)
			s.TextTransparency = (Sec and 0 or 0.5)
		end)
	end
	
	
	function start()
		buttons()
		display(true)
		while (true) do
			-- Simplicity FTW:
			t = tick()
			getDate()
			getTime()
			display()
			wait()
		end
	end
	
	start()
end
coroutine.wrap(MLODO_fake_script)()
local function LYYLN_fake_script() -- UserProfile.GetProfile 
	local script = Instance.new('LocalScript', UserProfile)

	local Players = game:GetService("Players")
	
	local player = Players.LocalPlayer
	
	
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	
	local imageLabel = script.Parent
	imageLabel.Image = content
end
coroutine.wrap(LYYLN_fake_script)()
local function CXBXCSN_fake_script() -- Name_5.LocalScript 
	local script = Instance.new('LocalScript', Name_5)

	script.Parent.Text = game.Players.LocalPlayer.Name
end
coroutine.wrap(CXBXCSN_fake_script)()
local function FVWXAY_fake_script() -- MainFrame.open-close 
	local script = Instance.new('LocalScript', MainFrame)

	local userInputService = game:GetService("UserInputService")
	local ts = game:GetService("TweenService")
	local gui = script.Parent  
	
	local isGuiOpen = true  -- Initially, the GUI is open
	gui.Visible = true 
	
	-- Create a UIScale object to handle smooth scaling
	local scale = Instance.new("UIScale")
	scale.Parent = gui
	scale.Scale = 1 
	local ti = TweenInfo.new(0.15, Enum.EasingStyle.Sine, Enum.EasingDirection.Out)
	
	local function toggleGui()
		isGuiOpen = not isGuiOpen
		local goal = {Scale = isGuiOpen and 1 or 0}
		local tween = ts:Create(scale, ti, goal)
		tween:Play()
	end
	
	userInputService.InputBegan:Connect(function(input, gameProcessed)
		if gameProcessed then return end
		if input.UserInputType == Enum.UserInputType.Keyboard and input.KeyCode == Enum.KeyCode.LeftAlt then
			toggleGui()
		end
	end)
	
end
coroutine.wrap(FVWXAY_fake_script)()
local function IQCNCVS_fake_script() -- MainFrame.UIDrag 
	local script = Instance.new('LocalScript', MainFrame)

	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.13
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(IQCNCVS_fake_script)()
local function SJQD_fake_script() -- KillUI.LocalScript 
	local script = Instance.new('LocalScript', KillUI)

	local button = script.Parent 
	local gui = button.Parent.Parent.Parent.Parent -- assuming the button is inside the GUI
	
	button.MouseButton1Click:Connect(function()
		gui:Destroy() -- destroy the entire GUI when the button is clicked
	end)
end
coroutine.wrap(SJQD_fake_script)()
local function DJNZZ_fake_script() -- ChangeTheme.LocalScript 
	local script = Instance.new('LocalScript', ChangeTheme)

	local button = script.Parent -- Reference to the button
	local frame = button.Parent.Parent.Parent -- The button is inside MainFrame, so its parent is the frame
	
	local function findChildRecursive(parent, name)
		for _, child in ipairs(parent:GetChildren()) do
			if child.Name == name then
				return child
			elseif #child:GetChildren() > 0 then
				local found = findChildRecursive(child, name)
				if found then return found end
			end
		end
		return nil
	end
	
	local themeLabel = findChildRecursive(frame, "ThemeLabel")
	
	local colors = {
		-- Core Modes
		{Color3.fromRGB(170, 170, 170), Color3.fromRGB(110, 110, 110)}, -- Steel Gray
		{Color3.fromRGB(255, 255, 255), Color3.fromRGB(230, 230, 230)}, -- White Mode
		{Color3.fromRGB(180, 180, 180), Color3.fromRGB(10, 10, 10)}, -- Black Mode
		{Color3.fromRGB(40, 40, 40), Color3.fromRGB(0, 0, 0)}, -- Dark Mode
	
		-- 8 Light-to-Dark Themes
		{Color3.fromRGB(173, 216, 230), Color3.fromRGB(0, 0, 139)}, -- Sky Blue
		{Color3.fromRGB(255, 102, 102), Color3.fromRGB(139, 0, 0)}, -- Crimson Red
		{Color3.fromRGB(144, 238, 144), Color3.fromRGB(0, 100, 0)}, -- Emerald Green
		{Color3.fromRGB(216, 191, 216), Color3.fromRGB(75, 0, 130)}, -- Royal Purple
		{Color3.fromRGB(255, 255, 153), Color3.fromRGB(184, 134, 11)}, -- Golden Yellow
		{Color3.fromRGB(255, 182, 193), Color3.fromRGB(199, 21, 133)}, -- Rose Pink
		{Color3.fromRGB(224, 255, 255), Color3.fromRGB(0, 128, 128)}, -- Arctic Frost
	
		-- 5 Unique Color Themes
		{Color3.fromRGB(255, 140, 0), Color3.fromRGB(0, 0, 255)}, -- Fiery Sunset
		{Color3.fromRGB(0, 255, 255), Color3.fromRGB(138, 43, 226)}, -- Mystic Ocean
		{Color3.fromRGB(139, 0, 0), Color3.fromRGB(255, 215, 0)}, -- Inferno
		{Color3.fromRGB(255, 20, 147), Color3.fromRGB(0, 255, 255)}, -- Neon Dream
		{Color3.fromRGB(25, 25, 112), Color3.fromRGB(138, 43, 226)}, -- Deep Space
		{Color3.fromRGB(0, 162, 232), Color3.fromRGB(255, 255, 255)}, -- Frostbyte (Blue/White)
		{Color3.fromRGB(0, 128, 0), Color3.fromRGB(0, 0, 0)} -- Green Shadow (Green/Black)
	}
	
	local colorNames = {
		"Steel Gray", "White Mode", "Black Mode", "Dark Mode",
		"Sky Blue", "Crimson Red", "Emerald Green", "Royal Purple", "Golden Yellow", "Rose Pink", "Arctic Frost",
		"Fiery Sunset", "Mystic Ocean", "Inferno", "Neon Dream", "Deep Space",
		"Frostbyte", "Green Shadow"
	}
	
	local colorIndex = 1
	
	local function calculateLuminance(color)
		return 0.2126 * color.R + 0.7152 * color.G + 0.0722 * color.B
	end
	
	
	local function updateElementColors(element)
		if element:IsA("TextButton") or element:IsA("TextLabel") then
			-- Check brightness of the background color
			local luminance = calculateLuminance(colors[colorIndex][1])
	
			
			if luminance < 0.5 then
				element.TextColor3 = Color3.fromRGB(255, 255, 255) -- Use white for dark backgrounds
			else
				element.TextColor3 = Color3.fromRGB(0, 0, 0) -- Use black for light backgrounds
			end
	
			-- Apply the colorful theme text color
			element.TextColor3 = colors[colorIndex][1]
	
			
			if element:IsA("TextButton") then
				element.TextColor3 = colors[colorIndex][1] 
				element.BackgroundColor3 = colors[colorIndex][2]  
			elseif element:IsA("TextLabel") then
				element.TextColor3 = colors[colorIndex][1]  
			end
		end
	
	
		for _, child in ipairs(element:GetChildren()) do
			updateElementColors(child)
		end
	end
	
	
	local gradient = frame:FindFirstChild("UIGradient")
	if not gradient then
		gradient = Instance.new("UIGradient")
		gradient.Parent = frame
	end
	
	local function updateGradient(index)
		if #colors[index] > 2 then
			gradient.Color = ColorSequence.new{
				ColorSequenceKeypoint.new(0, colors[index][1]),
				ColorSequenceKeypoint.new(0.16, colors[index][2]),
				ColorSequenceKeypoint.new(0.33, colors[index][3]),
				ColorSequenceKeypoint.new(0.5, colors[index][4]),
				ColorSequenceKeypoint.new(0.66, colors[index][5]),
				ColorSequenceKeypoint.new(0.83, colors[index][6]),
				ColorSequenceKeypoint.new(1, colors[index][7])
			}
		else
			gradient.Color = ColorSequence.new{
				ColorSequenceKeypoint.new(0, colors[index][1]),
				ColorSequenceKeypoint.new(1, colors[index][2])
			}
		end
	end
	
	updateGradient(colorIndex)
	
	-- Update all text buttons and labels with the new theme
	local function updateTextButtons()
		for _, child in ipairs(frame:GetChildren()) do
			updateElementColors(child)
		end
	end
	
	-- Set initial button text
	button.Text = "Switch Theme"
	button.TextColor3 = colors[colorIndex][1]
	button.BackgroundColor3 = colors[colorIndex][2]
	
	
	if themeLabel then
		themeLabel.Text = "Theme: " .. colorNames[colorIndex]
	end
	
	button.MouseButton1Click:Connect(function()
		-- Cycle to the next color
		colorIndex = (colorIndex % #colors) + 1
	
		-- Apply the new color gradient
		updateGradient(colorIndex)
	
		-- Update TextButtons and other elements
		updateTextButtons()
	
		-- Update the theme label if found
		if themeLabel then
			themeLabel.Text = "Theme: " .. colorNames[colorIndex]
			print("Updated theme label: " .. themeLabel.Text) -- Debug print
		end
	end)
	
	
	updateTextButtons()
	
end
coroutine.wrap(DJNZZ_fake_script)()
local function ZZDTVTS_fake_script() -- ShadowRunner.LocalScript 
	local script = Instance.new('LocalScript', ShadowRunner)

	local btn = script.Parent
	local active = false
	local uis = game:GetService("UserInputService")
	local runService = game:GetService("RunService")
	local tweenService = game:GetService("TweenService")
	local p = game.Players.LocalPlayer
	local c = p.Character or p.CharacterAdded:Wait()
	local lastPosition = c.HumanoidRootPart.Position
	local shadowClones = {}
	local cloneIndex = 0
	local cloneDistance = 5
	local originalPosition = nil
	local connection
	local shadowRunnerEnabled = false
	
	local function toggle()
		active = not active
		btn.Text = active and "Shadow Runner ON" or "Shadow Runner"
	
		if active then
			shadowRunnerEnabled = true
			cloneIndex = 0
			shadowClones = {}
			lastPosition = c.HumanoidRootPart.Position
			print("Shadow Runner Enabled")
		else
			shadowRunnerEnabled = false
			print("Shadow Runner Disabled")
	
			for _, clone in ipairs(shadowClones) do
				if clone then
					clone:Destroy()
				end
			end
			shadowClones = {}
			cloneIndex = 0
			if connection then
				connection:Disconnect()
				connection = nil
			end
		end
	end
	
	btn.MouseButton1Click:Connect(toggle)
	
	local function createShadowClone(position)
		local clonePart
		local isFirstClone = (cloneIndex == 1)
	
		if isFirstClone then
			clonePart = Instance.new("Part")
			clonePart.Size = Vector3.new(2, 5.5, 2)
		else
			clonePart = Instance.new("Part")
			clonePart.Size = Vector3.new(2, 2, 2)
		end
	
		clonePart.Position = position
		clonePart.Color = Color3.fromRGB(0, 0, 0)
		clonePart.Anchored = true
		clonePart.CanCollide = false
		clonePart.Parent = workspace
		clonePart.Shape = Enum.PartType.Ball
	
		local transparency = math.clamp(0.3 + (cloneIndex - 1) * 0.05, 0.3, 0.75)
		clonePart.Transparency = transparency
	
		local bodyVelocity = Instance.new("BodyVelocity")
		bodyVelocity.MaxForce = Vector3.new(4000, 4000, 4000)
		bodyVelocity.Velocity = Vector3.new(0, 100, 0)
		bodyVelocity.Parent = clonePart
	
		table.insert(shadowClones, clonePart)
	end
	
	local function fadeAndResetClones()
		local clones = shadowClones
		shadowClones = {}
	
		for i = #clones, 1, -1 do
			local clone = clones[i]
			if clone then
				local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Linear)
				local tween = tweenService:Create(clone, tweenInfo, { Transparency = 1 })
				tween:Play()
				tween.Completed:Connect(function()
					if clone and clone.Parent then
						clone:Destroy()
					end
				end)
			end
		end
	end
	
	local function resetShadowRunner()
		fadeAndResetClones()
		cloneIndex = 0
		shadowClones = {}
		lastPosition = c.HumanoidRootPart.Position
	
		if originalPosition then
			c.HumanoidRootPart.CFrame = CFrame.new(originalPosition)
		end
	
		if connection then
			connection:Disconnect()
			connection = nil
		end
	end
	
	uis.InputBegan:Connect(function(input, gameProcessedEvent)
		if gameProcessedEvent then return end
	
		if input.UserInputType == Enum.UserInputType.Keyboard and input.KeyCode == Enum.KeyCode.R then
			if shadowRunnerEnabled then
				if connection then
					print("Resetting Shadow Runner...")
					resetShadowRunner()
				else
					originalPosition = c.HumanoidRootPart.Position
					cloneIndex = 0
					connection = runService.RenderStepped:Connect(function()
						local currentPosition = c.HumanoidRootPart.Position
						if (currentPosition - lastPosition).Magnitude >= cloneDistance then
							cloneIndex = cloneIndex + 1
							createShadowClone(currentPosition)
							lastPosition = currentPosition
						end
					end)
				end
			else
				print("Shadow Runner is not enabled.")
			end
		end
	end)
	
end
coroutine.wrap(ZZDTVTS_fake_script)()
local function BAQJZRK_fake_script() -- NightVision.LocalScript 
	local script = Instance.new('LocalScript', NightVision)

	-- Night Vision Toggle Script with Sound
	
	local btn = script.Parent
	local nightVisionEnabled = false
	local player = game.Players.LocalPlayer
	local camera = game.Workspace.CurrentCamera
	local lighting = game:GetService("Lighting")
	
	-- Create a ColorCorrectionEffect for the Night Vision
	local colorCorrection = Instance.new("ColorCorrectionEffect")
	colorCorrection.Parent = lighting
	
	-- Save original lighting settings to restore them later
	local originalAmbient = lighting.Ambient
	local originalOutdoorAmbient = lighting.OutdoorAmbient
	local originalBrightness = lighting.Brightness
	local originalExposureCompensation = lighting.ExposureCompensation
	local originalSaturation = colorCorrection.Saturation
	local originalContrast = colorCorrection.Contrast
	local originalFogColor = lighting.FogColor
	local originalFogStart = lighting.FogStart
	local originalFogEnd = lighting.FogEnd
	
	-- Sounds
	local activationSoundId = 376178316  -- Sound to play when activating night vision
	local loopSoundId = 1253231728    -- Sound to play continuously when night vision is active
	
	local activationSound = Instance.new("Sound")
	activationSound.SoundId = "rbxassetid://" .. activationSoundId
	activationSound.Parent = camera
	activationSound.Pitch = 1.4  -- Speed up the activation sound to 1.4x speed
	activationSound.Volume = 0.5  -- Set volume to 0.5
	
	local loopSound = Instance.new("Sound")
	loopSound.SoundId = "rbxassetid://" .. loopSoundId
	loopSound.Parent = camera
	loopSound.Looped = true
	loopSound.Volume = 0.3  -- Set volume to 0.5
	
	-- Function to set the optimal lighting for night vision
	local function enableNightVision()
		colorCorrection.Enabled = true
		colorCorrection.TintColor = Color3.fromRGB(0, 255, 0)  -- Green tint for night vision
	
		-- Adjust lighting settings for night vision
		lighting.Ambient = Color3.fromRGB(255, 255, 255)  -- Increase ambient light
		lighting.OutdoorAmbient = Color3.fromRGB(255, 255, 255)  -- Make outdoor areas brighter
		lighting.Brightness = 2  -- Increase brightness for better visibility
		lighting.ExposureCompensation = 0.5  -- Slight exposure compensation
		colorCorrection.Saturation = 0.5  -- Decrease saturation for better visibility at night
		colorCorrection.Contrast = 1.5  -- Increase contrast for more definition
	
		-- Play the activation sound and loop sound
		activationSound:Play()
		loopSound:Play()
	end
	
	-- Function to reset lighting to original settings
	local function disableNightVision()
		colorCorrection.Enabled = false
	
		-- Reset all lighting settings to their original values
		lighting.Ambient = originalAmbient
		lighting.OutdoorAmbient = originalOutdoorAmbient
		lighting.Brightness = originalBrightness
		lighting.ExposureCompensation = originalExposureCompensation
		colorCorrection.Saturation = originalSaturation
		colorCorrection.Contrast = originalContrast
		lighting.FogColor = originalFogColor
		lighting.FogStart = originalFogStart
		lighting.FogEnd = originalFogEnd
	
		-- Stop the sounds
		activationSound:Stop()
		loopSound:Stop()
	end
	
	-- Toggle function to switch between enabling/disabling night vision
	local function toggleNightVision()
		if nightVisionEnabled then
			-- Disable night vision
			disableNightVision()
			btn.Text = "Enable Night Vision"
		else
			-- Enable night vision
			enableNightVision()
			btn.Text = "Disable Night Vision"
		end
		nightVisionEnabled = not nightVisionEnabled
	end
	
	-- Connect the button click to the toggle function
	btn.MouseButton1Click:Connect(function()
		toggleNightVision()
	end)
	
end
coroutine.wrap(BAQJZRK_fake_script)()
local function FUHBFXX_fake_script() -- HighMode.LocalScript 
	local script = Instance.new('LocalScript', HighMode)

	local btn = script.Parent
	local active = false
	
	local runService = game:GetService("RunService")
	local tweenService = game:GetService("TweenService")
	local camera = game.Workspace.CurrentCamera
	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:FindFirstChildOfClass("Humanoid")
	local originalFov = camera.FieldOfView
	
	local fovMin, fovMax = originalFov - 10, originalFov + 7
	local swirlIntensity = 0.0006
	local swirlSpeed = 0.01
	local textureSpeed = 0.1
	local directionChangeTime = 9
	local effectInstances = {}
	local movingTextures = {}
	local nextDirectionChange = tick() + directionChangeTime
	local shrinkAmount = 0.9 -- Objects shrink to 90% of their original size
	local growAmount = 1.1 -- Objects grow to 110% of their original size
	local breathSpeed = 6 -- Seconds per full cycle
	
	local function applyEffects()
		local blur = Instance.new("BlurEffect")
		blur.Size = 8
		blur.Parent = camera
		table.insert(effectInstances, blur)
	
		local bloom = Instance.new("BloomEffect")
		bloom.Intensity = 1.2
		bloom.Threshold = 0.8
		bloom.Size = 48
		bloom.Parent = camera
		table.insert(effectInstances, bloom)
	
		local colorCorrection = Instance.new("ColorCorrectionEffect")
		colorCorrection.Saturation = 0.2
		colorCorrection.TintColor = Color3.fromRGB(255, 200, 255)
		colorCorrection.Parent = camera
		table.insert(effectInstances, colorCorrection)
	end
	
	local function removeEffects()
		for _, effect in ipairs(effectInstances) do
			effect:Destroy()
		end
		effectInstances = {}
	end
	
	local function breatheObjects()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") and obj.Name ~= "HumanoidRootPart" then
				local originalSize = obj.Size
				local tweenShrink = tweenService:Create(obj, TweenInfo.new(breathSpeed, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), { Size = originalSize * shrinkAmount })
				local tweenGrow = tweenService:Create(obj, TweenInfo.new(breathSpeed, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), { Size = originalSize * growAmount })
	
				tweenShrink:Play()
				tweenShrink.Completed:Connect(function()
					tweenGrow:Play()
				end)
	
				tweenGrow.Completed:Connect(function()
					tweenShrink:Play()
				end)
			end
		end
	end
	
	local function applyMovingTextures()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") and obj.Name ~= "Part" then
				for _, existing in ipairs(obj:GetChildren()) do
					if existing:IsA("Texture") then
						existing:Destroy()
					end
				end
	
				local faces = {Enum.NormalId.Front, Enum.NormalId.Back, Enum.NormalId.Left, Enum.NormalId.Right, Enum.NormalId.Top, Enum.NormalId.Bottom}
				for _, face in ipairs(faces) do
					local texture = Instance.new("Texture")
					texture.Texture = "rbxassetid://16374392716"
					texture.Face = face
					texture.StudsPerTileU = 5
					texture.StudsPerTileV = 5
					texture.Parent = obj
	
					local velocity = Vector2.new(
						math.random() * 2 - 1,
						math.random() * 2 - 1
					)
					table.insert(movingTextures, {texture = texture, velocity = velocity})
				end
			end
		end
	end
	
	local function animateTextures()
		if tick() >= nextDirectionChange then
			for _, t in ipairs(movingTextures) do
				t.velocity = Vector2.new(
					math.random() * 2 - 1,
					math.random() * 2 - 1
				)
			end
			nextDirectionChange = tick() + directionChangeTime
		end
	
		for _, t in ipairs(movingTextures) do
			local tex = t.texture
			local vel = t.velocity
			tex.OffsetStudsU = tex.OffsetStudsU + vel.X * textureSpeed
			tex.OffsetStudsV = tex.OffsetStudsV + vel.Y * textureSpeed
		end
	end
	
	local function toggle()
		active = not active
		btn.Text = active and "High Mode ON" or "High Mode OFF"
	
		if active then
			print("High Mode Enabled")
			camera.FieldOfView = fovMin
			applyEffects()
			applyMovingTextures()
			breatheObjects()
	
			local swirlConnection
			local fovDirection = 1
			local currentAngle = 0
	
			swirlConnection = runService.RenderStepped:Connect(function(delta)
				if active then
					currentAngle = currentAngle + swirlSpeed
					local swirlX = math.sin(currentAngle) * swirlIntensity
					local swirlY = math.cos(currentAngle) * swirlIntensity
					camera.CFrame = camera.CFrame * CFrame.Angles(swirlX, swirlY, 0)
	
					animateTextures()
	
					camera.FieldOfView = camera.FieldOfView + (fovDirection * delta * 6)
					if camera.FieldOfView >= fovMax then fovDirection = -1 end
					if camera.FieldOfView <= fovMin then fovDirection = 1 end
				end
			end)
	
			btn.MouseButton1Click:Connect(function()
				if not active then
					swirlConnection:Disconnect()
					camera.FieldOfView = originalFov
					removeEffects()
					print("High Mode Disabled")
				end
			end)
	
		else
			print("High Mode Disabled")
			camera.FieldOfView = originalFov
			removeEffects()
		end
	end
	
	btn.MouseButton1Click:Connect(toggle)
	
end
coroutine.wrap(FUHBFXX_fake_script)()
local function TXMWKYS_fake_script() -- Astronaut.LocalScript 
	local script = Instance.new('LocalScript', Astronaut)

	local btn = script.Parent
	local active = false
	local astronautParts = {}  -- List to store modified parts for deactivation
	
	local function toggle()
		active = not active
		btn.Text = active and "Astronaut ON" or "Astronaut OFF"
	
		if active then
			-- Activate astronaut mode
			print("Astronaut Mode Enabled")
	
			-- Store astronaut parts so we can deactivate them later
			local plr = game:GetService("Players").LocalPlayer
			local char = plr.Character or plr.CharacterAdded:Wait()
			local uis = game:GetService("UserInputService")
			local run = game:GetService("RunService")
			local vel = Vector3.new(math.random(-2, 2), 0.2, math.random(-2, 2)) * 0.1
			local rot = Vector3.new()
			local drift_rot = Vector3.new()
			local wave_timer = 0
			local wave_dir = 1
	
			for _, v in pairs(char:GetDescendants()) do
				if v:IsA("BasePart") and v.Name ~= "HumanoidRootPart" then
					-- Save modified parts for later deactivation
					table.insert(astronautParts, v)
	
					-- Modify physical properties to simulate astronaut mode
					v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
					local a = Instance.new("AlignOrientation", v)
					a.Attachment0 = Instance.new("Attachment", v)
					a.Mode = Enum.OrientationAlignmentMode.OneAttachment
					a.Responsiveness = 3
					a.MaxTorque = 999999
					local bv = Instance.new("BodyVelocity", v)
					bv.MaxForce = Vector3.new(99999, 99999, 99999)
	
					task.spawn(function()
						while active and task.wait(0.03) do  -- Keep running while active
							local input = Vector3.new()
							if uis:IsKeyDown(Enum.KeyCode.W) then input = input + char.HumanoidRootPart.CFrame.LookVector * 0.3 end
							if uis:IsKeyDown(Enum.KeyCode.S) then input = input - char.HumanoidRootPart.CFrame.LookVector * 0.3 end
							if uis:IsKeyDown(Enum.KeyCode.A) then input = input - char.HumanoidRootPart.CFrame.RightVector * 0.3 end
							if uis:IsKeyDown(Enum.KeyCode.D) then input = input + char.HumanoidRootPart.CFrame.RightVector * 0.3 end
	
							vel = vel * 0.997 + input * 0.08
							bv.Velocity = vel + Vector3.new(0, wave_dir * 0.5, 0)  -- Increased upward drift
	
							if input.Magnitude > 0 then
								rot = rot * 0.95 + Vector3.new(input.Y, input.Z, -input.X) * (0.1 + input.Magnitude * 0.05)
							else
								rot = rot * 0.99
							end
	
							if math.random(1, 10) == 1 then
								drift_rot = drift_rot + Vector3.new(math.random(-30, 30), math.random(-30, 30), math.random(-30, 30)) * (0.01 + input.Magnitude * 0.03)
							end
							drift_rot = drift_rot * 0.995
							a.CFrame = CFrame.Angles(rot.X + drift_rot.X, rot.Y + drift_rot.Y, rot.Z + drift_rot.Z)
	
							wave_timer = wave_timer + 1
							if wave_timer > 200 then
								wave_timer = 0
								wave_dir = -wave_dir
							end
	
							-- Spacebar control for upward movement
							if uis:IsKeyDown(Enum.KeyCode.Space) then
								bv.Velocity = bv.Velocity + Vector3.new(0, 1, 0)  -- Add upward force
							else
								bv.Velocity = bv.Velocity + Vector3.new(0, -0.2, 0)  -- Default downward force
							end
	
							if char.HumanoidRootPart.Position.Y < workspace.FallenPartsDestroyHeight + 20 then
								char.HumanoidRootPart.Velocity = Vector3.new(0, 5, 0)
							end
						end
					end)
					v:SetNetworkOwner(plr)
				end
			end
		else
			-- Deactivate astronaut mode
			print("Astronaut Mode Disabled")
	
			-- Reset astronaut mode physics and remove BodyVelocity / AlignOrientation
			for _, v in pairs(astronautParts) do
				if v:IsA("BasePart") then
					v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
					-- Reset or remove custom physics (e.g., BodyVelocity, AlignOrientation)
					local bv = v:FindFirstChildOfClass("BodyVelocity")
					if bv then bv:Destroy() end
					local a = v:FindFirstChildOfClass("AlignOrientation")
					if a then a:Destroy() end
				end
			end
			astronautParts = {}  -- Clear astronaut parts list
		end
	end
	
	btn.MouseButton1Click:Connect(toggle)
	
end
coroutine.wrap(TXMWKYS_fake_script)()
local function ONOY_fake_script() -- Main.LocalScript 
	local script = Instance.new('LocalScript', Main)

	local TweenService = game:GetService("TweenService")
	local p = script.Parent:WaitForChild("csfe")
	local pages = {
		CS = p:WaitForChild("CS"),
		FE = p:WaitForChild("FE"),
	}
	local buttons = {
		p:WaitForChild("CSB"),
		p:WaitForChild("FEB"),
	}
	
	local fadeTime = 0.18 -- Dauer der Animation
	local currentPage = pages.CS
	
	local function showPage(pageName)
		if currentPage == pages[pageName] then return end -- Verhindert erneutes Öffnen
	
		local oldPage = currentPage
		local newPage = pages[pageName]
	
		-- Tween-Animation für das Ausblenden der alten Seite
		local fadeOut = TweenService:Create(oldPage, TweenInfo.new(fadeTime), {BackgroundTransparency = 1})
		fadeOut:Play()
		fadeOut.Completed:Wait()
		oldPage.Visible = false
	
		-- Neue Seite einblenden
		newPage.Visible = true
		newPage.BackgroundTransparency = 1
		local fadeIn = TweenService:Create(newPage, TweenInfo.new(fadeTime), {BackgroundTransparency = 1})
		fadeIn:Play()
	
		currentPage = newPage
	end
	
	
	buttons[1].MouseButton1Click:Connect(function() showPage("CS") end)
	buttons[2].MouseButton1Click:Connect(function() showPage("FE") end)
	
	showPage("CS")
	
	
end
coroutine.wrap(ONOY_fake_script)()
local function SEWZIW_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	local TweenService = game:GetService("TweenService")
	local p = script.Parent:WaitForChild("MainFrame")
	local pages = {
		Home = p:WaitForChild("Home"),
		Main = p:WaitForChild("Main"),
		Other = p:WaitForChild("Other"),
		Info = p:WaitForChild("Info")
	}
	local buttons = {
		p:WaitForChild("HomeButton"),
		p:WaitForChild("MainButton"),
		p:WaitForChild("OtherButton"),
		p:WaitForChild("InfoButton")
	}
	
	local fadeTime = 0.18 -- Dauer der Animation
	local currentPage = pages.Home
	
	local function showPage(pageName)
		if currentPage == pages[pageName] then return end -- Verhindert erneutes Öffnen
	
		local oldPage = currentPage
		local newPage = pages[pageName]
	
		-- Tween-Animation für das Ausblenden der alten Seite
		local fadeOut = TweenService:Create(oldPage, TweenInfo.new(fadeTime), {BackgroundTransparency = 1})
		fadeOut:Play()
		fadeOut.Completed:Wait()
		oldPage.Visible = false
	
		-- Neue Seite einblenden
		newPage.Visible = true
		newPage.BackgroundTransparency = 1
		local fadeIn = TweenService:Create(newPage, TweenInfo.new(fadeTime), {BackgroundTransparency = 0.7})
		fadeIn:Play()
	
		currentPage = newPage
	end
	
	
	buttons[1].MouseButton1Click:Connect(function() showPage("Home") end)
	buttons[2].MouseButton1Click:Connect(function() showPage("Main") end)
	buttons[3].MouseButton1Click:Connect(function() showPage("Other") end)
	buttons[4].MouseButton1Click:Connect(function() showPage("Info") end)
	
	showPage("Home")
	
end
coroutine.wrap(SEWZIW_fake_script)()
local function NYSF_fake_script() -- ScreenGui.ButtonClickScript 
	local script = Instance.new('LocalScript', ScreenGui)

	-- LocalScript inside your ScreenGui
	
	local TweenService = game:GetService("TweenService")
	local MainFrame = script.Parent:WaitForChild("MainFrame") -- Ensure MainFrame exists
	
	-- Function to apply the glow effect
	local function applyGlowEffect(button)
		-- Create a glow effect (using UIStroke)
		local glow = button:FindFirstChild("GlowEffect")
		if not glow then
			-- Create a new glow if it doesn't exist
			glow = Instance.new("UIStroke")
			glow.Name = "GlowEffect"
			glow.Parent = button
			glow.Thickness = 1.4 -- Reduced thickness (about 30% less than before)
			glow.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
			glow.Color = Color3.fromRGB(200, 200, 200) -- Greyish white color
			glow.Transparency = 0.7 -- 0.7 transparency (more visible but not too bright)
		end
	
		-- Make the glow immediately visible and then disappear with a slightly longer animation
		local tweenGlowIn = TweenService:Create(glow, TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out), {
			Transparency = 0.7, -- Slight transparency (visible but not too bright)
			Thickness = 2 -- Slightly thicker than default
		})
	
		-- Play the glow in
		tweenGlowIn:Play()
	
		-- Immediately remove the glow after click
		tweenGlowIn.Completed:Connect(function()
			glow:Destroy() -- Destroy glow effect right after animation is completed
		end)
	end
	
	-- Function to add the click event and apply the glow effect to all buttons inside MainFrame
	local function addGlowToButtons(frame)
		for _, child in ipairs(frame:GetChildren()) do
			if child:IsA("TextButton") then
				-- Connect the MouseButton1Click event to trigger the glow effect
				child.MouseButton1Click:Connect(function()
					applyGlowEffect(child)
				end)
			end
	
			-- If the child has any children (in case of nested frames), recursively apply the glow effect
			if #child:GetChildren() > 0 then
				addGlowToButtons(child)
			end
		end
	end
	
	-- Start applying the glow effect to all buttons inside MainFrame
	addGlowToButtons(MainFrame)
	
	-- Optionally, monitor any new buttons added to MainFrame (if dynamic additions occur)
	MainFrame.ChildAdded:Connect(function(child)
		if child:IsA("TextButton") then
			-- Apply the glow effect to any new TextButtons
			child.MouseButton1Click:Connect(function()
				applyGlowEffect(child)
			end)
		end
	
		-- Recursively handle any new buttons added to nested frames
		if #child:GetChildren() > 0 then
			addGlowToButtons(child)
		end
	end)
	
end
coroutine.wrap(NYSF_fake_script)()
