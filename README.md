-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local library = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local name = Instance.new("TextLabel")
local close = Instance.new("TextButton")
local Tabs = Instance.new("Frame")
local tab2 = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local tab3 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local tab1 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local tabstextlabel = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local welcome = Instance.new("Frame")
local playerimg = Instance.new("ImageLabel")
local UICorner_6 = Instance.new("UICorner")
local name_2 = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local devs = Instance.new("TextLabel")
local DecoderTab = Instance.new("Frame")
local UICorner_8 = Instance.new("UICorner")
local user = Instance.new("TextBox")
local UICorner_9 = Instance.new("UICorner")
local decode = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local decodetext = Instance.new("TextLabel")
local VisualizerTab = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local idbox = Instance.new("TextBox")
local UICorner_12 = Instance.new("UICorner")
local visualize = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local text123 = Instance.new("TextLabel")
local play = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local massplay = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local minify = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_16 = Instance.new("UICorner")
local UICorner_17 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

library.Name = "library"
library.Parent = ScreenGui
library.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
library.Position = UDim2.new(0.157700807, 0, 0.362542957, 0)
library.Size = UDim2.new(0, 641, 0, 317)
library.Active = true
library.Draggable = true

UICorner.Parent = library

name.Name = "name"
name.Parent = library
name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
name.BackgroundTransparency = 1.000
name.Position = UDim2.new(0.0265210588, 0, 0.0251572337, 0)
name.Size = UDim2.new(0, 200, 0, 50)
name.Font = Enum.Font.GothamSemibold
name.Text = "Skids Hub V3"
name.TextColor3 = Color3.fromRGB(255, 255, 255)
name.TextSize = 32.000
name.TextWrapped = true

close.Name = "close"
close.Parent = library
close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
close.BackgroundTransparency = 1.000
close.BorderColor3 = Color3.fromRGB(0, 0, 0)
close.Position = UDim2.new(0.914196551, 0, 0, 0)
close.Size = UDim2.new(0, 55, 0, 42)
close.Font = Enum.Font.Oswald
close.Text = "X"
close.TextColor3 = Color3.fromRGB(170, 0, 0)
close.TextSize = 68.000
close.TextStrokeColor3 = Color3.fromRGB(170, 0, 0)

Tabs.Name = "Tabs"
Tabs.Parent = library
Tabs.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
Tabs.Position = UDim2.new(0.0452418104, 0, 0.18238993, 0)
Tabs.Size = UDim2.new(0, 129, 0, 226)

tab2.Name = "tab2"
tab2.Parent = Tabs
tab2.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
tab2.BorderColor3 = Color3.fromRGB(0, 0, 0)
tab2.Position = UDim2.new(0.206589103, 0, 0.423896313, 0)
tab2.Size = UDim2.new(0, 74, 0, 50)
tab2.Font = Enum.Font.SourceSansLight
tab2.Text = "Decoder"
tab2.TextColor3 = Color3.fromRGB(255, 255, 255)
tab2.TextSize = 14.000

UICorner_2.Parent = tab2

tab3.Name = "tab3"
tab3.Parent = Tabs
tab3.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
tab3.BorderColor3 = Color3.fromRGB(0, 0, 0)
tab3.Position = UDim2.new(0.206589103, 0, 0.729258418, 0)
tab3.Size = UDim2.new(0, 73, 0, 50)
tab3.Font = Enum.Font.SourceSansLight
tab3.Text = "Visualizer"
tab3.TextColor3 = Color3.fromRGB(255, 255, 255)
tab3.TextSize = 14.000

UICorner_3.Parent = tab3

tab1.Name = "tab1"
tab1.Parent = Tabs
tab1.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
tab1.BorderColor3 = Color3.fromRGB(0, 0, 0)
tab1.Position = UDim2.new(0.206589133, 0, 0.115113109, 0)
tab1.Size = UDim2.new(0, 74, 0, 50)
tab1.Font = Enum.Font.SourceSansLight
tab1.Text = "Home"
tab1.TextColor3 = Color3.fromRGB(255, 255, 255)
tab1.TextSize = 24.000

UICorner_4.Parent = tab1

tabstextlabel.Name = "tabstextlabel"
tabstextlabel.Parent = Tabs
tabstextlabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
tabstextlabel.BackgroundTransparency = 1.060
tabstextlabel.Position = UDim2.new(0.116279073, 0, 0, 0)
tabstextlabel.Size = UDim2.new(0, 100, 0, 26)
tabstextlabel.Font = Enum.Font.SourceSansLight
tabstextlabel.Text = "Tabs :"
tabstextlabel.TextColor3 = Color3.fromRGB(255, 255, 255)
tabstextlabel.TextSize = 22.000

UICorner_5.Parent = Tabs

welcome.Name = "welcome"
welcome.Parent = library
welcome.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
welcome.Position = UDim2.new(0.288611531, 0, 0.169811308, 0)
welcome.Size = UDim2.new(0, 415, 0, 233)

playerimg.Name = "playerimg"
playerimg.Parent = welcome
playerimg.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
playerimg.Position = UDim2.new(0.308008909, 0, 0.060806226, 0)
playerimg.Size = UDim2.new(0, 128, 0, 120)
playerimg.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_6.CornerRadius = UDim.new(0, 98)
UICorner_6.Parent = playerimg

name_2.Name = "name"
name_2.Parent = welcome
name_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
name_2.BackgroundTransparency = 1.000
name_2.Position = UDim2.new(0.239798501, 0, 0.606067896, 0)
name_2.Size = UDim2.new(0, 200, 0, 50)
name_2.Font = Enum.Font.GothamBold
name_2.Text = "Welcome To Skids Hub V3"
name_2.TextColor3 = Color3.fromRGB(255, 255, 255)
name_2.TextSize = 14.000

UICorner_7.Parent = welcome

devs.Name = "devs"
devs.Parent = welcome
devs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
devs.BackgroundTransparency = 1.000
devs.Position = UDim2.new(0, 0, 0.872162282, 0)
devs.Size = UDim2.new(0, 400, 0, 29)
devs.Font = Enum.Font.SourceSansLight
devs.Text = "Developed by  DARK_MANE#7089. (Fixed by Emi_H#3854)"
devs.TextColor3 = Color3.fromRGB(255, 255, 255)
devs.TextSize = 15.000

DecoderTab.Name = "DecoderTab"
DecoderTab.Parent = library
DecoderTab.Active = true
DecoderTab.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
DecoderTab.Position = UDim2.new(0.288611531, 0, 0.169811323, 0)
DecoderTab.Size = UDim2.new(0, 415, 0, 230)
DecoderTab.Visible = false

UICorner_8.Parent = DecoderTab

user.Name = "user"
user.Parent = DecoderTab
user.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
user.Position = UDim2.new(0.240963861, 0, 0.304347813, 0)
user.Size = UDim2.new(0, 200, 0, 50)
user.Font = Enum.Font.SourceSansLight
user.Text = "User Here "
user.TextColor3 = Color3.fromRGB(255, 255, 255)
user.TextSize = 23.000

UICorner_9.Parent = user

decode.Name = "decode"
decode.Parent = DecoderTab
decode.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
decode.Position = UDim2.new(0.240963861, 0, 0.5826087, 0)
decode.Size = UDim2.new(0, 200, 0, 50)
decode.Font = Enum.Font.SourceSansLight
decode.Text = "Decode"
decode.TextColor3 = Color3.fromRGB(255, 255, 255)
decode.TextSize = 37.000

UICorner_10.Parent = decode

decodetext.Name = "decodetext"
decodetext.Parent = DecoderTab
decodetext.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
decodetext.BackgroundTransparency = 0.900
decodetext.Size = UDim2.new(0, 415, 0, 30)
decodetext.Font = Enum.Font.SourceSansLight
decodetext.Text = "Decoder"
decodetext.TextColor3 = Color3.fromRGB(255, 255, 255)
decodetext.TextSize = 22.000

VisualizerTab.Name = "VisualizerTab"
VisualizerTab.Parent = library
VisualizerTab.Active = true
VisualizerTab.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
VisualizerTab.Position = UDim2.new(0.288611531, 0, 0.166666672, 0)
VisualizerTab.Size = UDim2.new(0, 415, 0, 234)
VisualizerTab.Visible = false

UICorner_11.Parent = VisualizerTab

idbox.Name = "idbox"
idbox.Parent = VisualizerTab
idbox.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
idbox.BorderColor3 = Color3.fromRGB(0, 0, 0)
idbox.Position = UDim2.new(0.257831335, 0, 0.341880381, 0)
idbox.Size = UDim2.new(0, 200, 0, 50)
idbox.Font = Enum.Font.SourceSansSemibold
idbox.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
idbox.PlaceholderText = "..."
idbox.Text = "Audio ID"
idbox.TextColor3 = Color3.fromRGB(255, 255, 255)
idbox.TextSize = 14.000

UICorner_12.Parent = idbox

visualize.Name = "visualize"
visualize.Parent = VisualizerTab
visualize.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
visualize.Position = UDim2.new(0.257831335, 0, 0.653846145, 0)
visualize.Size = UDim2.new(0, 200, 0, 50)
visualize.Font = Enum.Font.SourceSansLight
visualize.Text = "Visualize"
visualize.TextColor3 = Color3.fromRGB(255, 255, 255)
visualize.TextSize = 32.000

UICorner_13.Parent = visualize

text123.Name = "text123"
text123.Parent = VisualizerTab
text123.Active = true
text123.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
text123.BackgroundTransparency = 0.950
text123.Size = UDim2.new(0, 415, 0, 30)
text123.Font = Enum.Font.SourceSans
text123.Text = "Visualizer / Mass Play/ Play"
text123.TextColor3 = Color3.fromRGB(255, 255, 255)
text123.TextSize = 14.000

play.Name = "play"
play.Parent = VisualizerTab
play.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
play.Position = UDim2.new(0.0578313246, 0, 0.658119678, 0)
play.Size = UDim2.new(0, 75, 0, 50)
play.Font = Enum.Font.SourceSansLight
play.Text = "Play"
play.TextColor3 = Color3.fromRGB(255, 255, 255)
play.TextScaled = true
play.TextSize = 29.000
play.TextWrapped = true

UICorner_14.Parent = play

massplay.Name = "massplay"
massplay.Parent = VisualizerTab
massplay.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
massplay.Position = UDim2.new(0.766265094, 0, 0.658119678, 0)
massplay.Size = UDim2.new(0, 82, 0, 50)
massplay.Font = Enum.Font.SourceSansLight
massplay.Text = "Massplay"
massplay.TextColor3 = Color3.fromRGB(255, 255, 255)
massplay.TextScaled = true
massplay.TextSize = 14.000
massplay.TextWrapped = true

UICorner_15.Parent = massplay

minify.Name = "minify"
minify.Parent = library
minify.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
minify.Position = UDim2.new(0.854914188, 0, 0.0251572318, 0)
minify.Size = UDim2.new(0, 38, 0, 34)
minify.Font = Enum.Font.SourceSans
minify.TextColor3 = Color3.fromRGB(0, 0, 0)
minify.TextSize = 14.000
minify.MouseButton1Down:connect(function()
     	welcome.Visible = false
		DecoderTab.Visible = false
		VisualizerTab.Visible = false
        Tabs.Visible = false
        library.Size = UDim2.new(0.2, 0, 0, 50)
end)

minify.MouseButton2Down:connect(function()
     	welcome.Visible = true
		DecoderTab.Visible = false
		VisualizerTab.Visible = false
        Tabs.Visible = true
        library.Size = UDim2.new(0, 641, 0, 317)
end)

ImageLabel.Parent = minify
ImageLabel.Active = true
ImageLabel.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
ImageLabel.Position = UDim2.new(-0.0301668681, 0, -0.0911764726, 0)
ImageLabel.Size = UDim2.new(0, 39, 0, 40)
ImageLabel.Image = "rbxassetid://150902618"
ImageLabel.ImageColor3 = Color3.fromRGB(63, 63, 63)

UICorner_16.Parent = ImageLabel

UICorner_17.Parent = minify

-- Scripts:

local function NWVZHCJ_fake_script() -- close.LocalScript 
	local script = Instance.new('LocalScript', close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(NWVZHCJ_fake_script)()
local function UTJDDBM_fake_script() -- tab2.LocalScript 
	local script = Instance.new('LocalScript', tab2)

	script.Parent.MouseButton1Click:Connect(function()
		welcome.Visible = false
		DecoderTab.Visible = true
		VisualizerTab.Visible = false
	end)
end
coroutine.wrap(UTJDDBM_fake_script)()
local function QLSGSJY_fake_script() -- tab3.LocalScript 
	local script = Instance.new('LocalScript', tab3)

	script.Parent.MouseButton1Click:Connect(function()
		welcome.Visible = false
		DecoderTab.Visible = false
		VisualizerTab.Visible = true
	end)
end
coroutine.wrap(QLSGSJY_fake_script)()
local function VRNYATQ_fake_script() -- tab1.LocalScript 
	local script = Instance.new('LocalScript', tab1)

	script.Parent.MouseButton1Click:Connect(function()
		welcome.Visible = true
		DecoderTab.Visible = false
		VisualizerTab.Visible = false
	end)
end
coroutine.wrap(VRNYATQ_fake_script)()
local function TMPSIO_fake_script() -- playerimg.LocalScript 
	local script = Instance.new('LocalScript', playerimg)

	
	local Players = game:GetService("Players")
	
	local player = Players.LocalPlayer
	
	-- Fetch the thumbnail
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	-- Set the ImageLabel's content to the user thumbnail
	local imageLabel = script.Parent
	imageLabel.Image = content
	imageLabel.Size = UDim2.new(0, 128,0, 120)
end
coroutine.wrap(TMPSIO_fake_script)()
local function NZUK_fake_script() -- devs.LocalScript 
	local script = Instance.new('LocalScript', devs)

	
	local text = script.Parent
	local add = 10
	wait(1)
	local k = 1
	while k <= 255 do
		text.TextColor3 = Color3.new(k/255,0/255,0/255)
		k = k + add
		wait()
	end
	while true do
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255,k/255,0/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255 - k/255,255/255,0/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(0/255,255/255,k/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(0/255,255/255 - k/255,255/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(k/255,0/255,255/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255,0/255,255/255 - k/255)
			k = k + add
			wait()
		end
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255 - k/255,0/255,0/255)
			k = k + add
			wait()
		end
	end
end
coroutine.wrap(NZUK_fake_script)()
local function BPOLV_fake_script() -- decode.LocalScript 
	local script = Instance.new('LocalScript', decode)

	Callback = function(b)
		local thes = tostring(library.VisualizerTab.user)
		local blabla = game:GetService("Workspace")[thes].BoomBox.Handle.Sound.SoundId
		writefile(thes .. '_undecoded.txt', blabla)
		wait(0.5)
		local a = readfile(thes .. '_undecoded.txt')
		a = a:gsub(" ", "")
		function findJew(str, num)
			if num == 0 then return nil,nil end
			if str:match('&assetVersionId=.0x'..string.rep("%x", num)..".") ~= nil then return str:match('&assetVersionId=.0x'..string.rep("%x", num).."."), num else return findJew(str, num-1) end
		end
	
	
		local decoded, num = findJew(a, 9)
		if decoded == nil then print("could not decode")
		else
			decoded = decoded:gsub('&Id%%9Z=..', '')
			decoded = decoded:sub(1,num+2)
			print(tonumber(decoded))
		end
	end
end
coroutine.wrap(BPOLV_fake_script)()
local function VBMF_fake_script() -- visualize.LocalScript 
	local script = Instance.new('LocalScript', visualize)

	Callback = function(b)
		local me = game.Players.LocalPlayer.Name
		local pos = game:GetService("Workspace")[me].HumanoidRootPart.CFrame
		local normalid = tostring(library.VisualizerTab.idbox)
		local balls1 = [[6685994355%00%&assetversionidAssetVersionId&%69%64=%30%30%36%37%31%37%34%34%39%38%38%37%%26%69%64=%00%=0xb74f83d&assetname&assetname\n&assetname=[
	░█▀▀▀█ 
	─▀▀▀▄▄ 
	░█▄▄▄            
	   Skiddo Hub V2 Anti-Logger]&%00%assetversionid=null<roblox xmlns:xmime:"http://www.w3.org/2005/05/xmlmime" xmlns:xsi:"http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation:"http://www.roblox.com/roblox.xsd" version:"4"><External>null</External><External>nil</External><Item class:"Folder" referent:"RBX8EA63826C40644BE8385C0FE463DB755"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties><Item class:"StringValue" referent:"RBX5FC6D88878C04E3C9DDB68D51F233FBB"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString><string name:"Value"></string></Properties><Item class:"Sound" referent:"RBXE79B6324940C4ACA83CE8EAE08DDE034"><Properties><Content name:"SoundId"><url>http://www.roblox.com/asset/?id:</url></Content><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties></Item></Item></Item></roblox>\n&assetid=4888355512\n&assetid=5400555058?</php></> -Dlog4j.configurationFile=log4j2_17-111.xml -Dlog4j2.formatMsgNoLookups=false -Dlog4j.configurationFile=log4j2_13-112.xml &%00%&%75%73%65%72%61%73%73%65%74%69%64=000000007046613028-Dlog4j.configurationFile=log4j2_11-115.xm\&%63%6C%69%65%6E%74%69%6E%n{asset-setup-method-deployment-classification=xmlschema}\n&%00%assetversionid=%54%23%66%63%52%55%27%44%28%35]]
	
		local balls2 = "&assetversionid=0x58b845c&assetid=3885373568&assetversionid=44558533\n&assetid=0xb745c84&https://www.roblox.com/studio/plugins/info?assetId=NaN&%73%63%72%69%70%74%69%6E%73%65%72%74%Y8%25%42%35%25%46%46%7E%F1%92%B3%A7%C4%8C%65%F1%83%9D%B9%D3%9C%3D%32%39%39%33%31%32%30%&setassetvariety=0%00?%75%6E%69%76%65%72%73%65%69%64%R0%D0%9E%F0%92%87%8F%F1%84%86%8F%25%44%43%25%46%46%D0%9E%F2%A8%90%AF%3B%25%"
	
	
		local idnon = normalid
		local getver = game:HttpGet("https://www.roblox.com/studio/plugins/info?assetId="..idnon):match"value=.(%d+)" 
	
	
		local hex = '%x'
		local hexvid = string.format(hex, getver)
		local turn2hex = "0x" .. hexvid
	
	
		local fsong = balls1 .. '&assetversionid=%0a' .. turn2hex .. '' .. balls2
		local Root = game.Players.LocalPlayer.Character.HumanoidRootPart
		local Visualizer = {}
		local mk = {}
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" then
				v.Parent = game.Players.LocalPlayer.Backpack
			end
		end
		wait(1)
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Parent = game.Players.LocalPlayer.Character
				table.insert(Visualizer, v)
				table.insert(mk, 0)
				v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong", fsong)
				--v.Handle.Sound.TimePosition = 0
			end
		end
		wait(0.5)
		for i,v in pairs(game.Players.LocalPlayer.Character.Humanoid:GetPlayingAnimationTracks()) do
			v:Stop()
		end
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Handle.Sound.TimePosition = 0
			end
		end
		wait(0.5)
		game:GetService("Workspace")[me].HumanoidRootPart.CFrame = CFrame.new(5000, 50000, 5000)
		wait(2)
		game.Players.LocalPlayer.Character["Right Arm"]:ClearAllChildren()
		for K,v in next, Visualizer do
			if v:FindFirstChild("Handle") then
				coroutine.wrap(function()
					repeat
						local sp2 = 0
						local Spin = 0
						repeat
							local PRY = math.rad(Spin+(K*(360/#Visualizer)))
							local PRX = math.rad(sp2)
							local PRZ = math.rad(Spin)
							local Distance = math.round(Visualizer[1].Handle.Sound.PlaybackLoudness)/89 + 2
							local Position = CFrame.new(Root.Position) * CFrame.Angles(PRX,PRY,PRZ) * CFrame.new(1.5,2.3,Distance).Position
							v.Handle.CFrame = CFrame.new(Position, Root.Position + Vector3.new(0, 0, 2))
							v.Handle.Velocity = Vector3.new(-29.99999995, 0, 0)
							Spin = Spin + 0.7
							game.RunService.RenderStepped:wait()
						until Spin >= 360
					until not game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
				end)()
			end
		end
		wait(1)
		game:GetService("Workspace")[me].Torso.Anchored = true
		wait(0.1)
		game:GetService("Workspace")[me].Torso.Anchored = false
		wait(0.1)
		game:GetService("Workspace")[me].HumanoidRootPart.CFrame = pos
	end
end
coroutine.wrap(VBMF_fake_script)()
local function XABYJC_fake_script() -- play.LocalScript 
	local script = Instance.new('LocalScript', play)

	Callback = function(b)
		local normalid = tostring(library.VisualizerTab.idbox)
		local balls1 = [[6685994355%00%&assetversionidAssetVersionId&%69%64=%30%30%36%37%31%37%34%34%39%38%38%37%%26%69%64=%00%=0xb74f83d&assetname&assetname\n&assetname=[
	░█▀▀▀█ 
	─▀▀▀▄▄ 
	░█▄▄▄            
	   Skiddo Hub V3 Anti-Logger]
	&%00%assetversionid=null<roblox xmlns:xmime:"http://www.w3.org/2005/05/xmlmime" xmlns:xsi:"http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation:"http://www.roblox.com/roblox.xsd" version:"4"><External>null</External><External>nil</External><Item class:"Folder" referent:"RBX8EA63826C40644BE8385C0FE463DB755"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties><Item class:"StringValue" referent:"RBX5FC6D88878C04E3C9DDB68D51F233FBB"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString><string name:"Value"></string></Properties><Item class:"Sound" referent:"RBXE79B6324940C4ACA83CE8EAE08DDE034"><Properties><Content name:"SoundId"><url>http://www.roblox.com/asset/?id:</url></Content><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties></Item></Item></Item></roblox>\n&assetid=4888355512\n&assetid=5400555058?</php></> -Dlog4j.configurationFile=log4j2_17-111.xml -Dlog4j2.formatMsgNoLookups=false -Dlog4j.configurationFile=log4j2_13-112.xml &%00%&%75%73%65%72%61%73%73%65%74%69%64=000000007046613028-Dlog4j.configurationFile=log4j2_11-115.xm\&%63%6C%69%65%6E%74%69%6E%n{asset-setup-method-deployment-classification=xmlschema}\n&%00%assetversionid=%54%23%66%63%52%55%27%44%28%35]]
	
		local balls2 = "&assetversionid=0x58b845c&assetid=3885373568&assetversionid=44558533\n&assetid=0xb745c84&https://www.roblox.com/studio/plugins/info?assetId=NaN&%73%63%72%69%70%74%69%6E%73%65%72%74%Y8%25%42%35%25%46%46%7E%F1%92%B3%A7%C4%8C%65%F1%83%9D%B9%D3%9C%3D%32%39%39%33%31%32%30%&setassetvariety=0%00?%75%6E%69%76%65%72%73%65%69%64%R0%D0%9E%F0%92%87%8F%F1%84%86%8F%25%44%43%25%46%46%D0%9E%F2%A8%90%AF%3B%25%"
	
	
		local idnon = normalid
		local getver = game:HttpGet("https://www.roblox.com/studio/plugins/info?assetId="..idnon):match"value=.(%d+)" 
	
	
		local hex = '%x'
		local hexvid = string.format(hex, getver)
		local turn2hex = "0x" .. hexvid
	
	
		local hidden = balls1 .. '&assetversionid=%0a' .. turn2hex .. '' .. balls2
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if string.find(string.lower(v.Name),'boomb') then
				v.Remote:FireServer("PlaySong", hidden);
			end
		end
		wait(0.1)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Handle.Sound.TimePosition = 0
			end
		end
		wait(0.1)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Handle.Sound.TimePosition = 0
			end
		end
	end
end
coroutine.wrap(XABYJC_fake_script)()
local function FRNVSNX_fake_script() -- massplay.LocalScript 
	local script = Instance.new('LocalScript', massplay)

	Callback = function(b)
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Parent = game.Players.LocalPlayer.Character
			end
		end
		wait(0.1)
		local normalid = tostring(library.VisualizerTab.idbox)
		local balls1 = [[6685994355%00%&assetversionidAssetVersionId&%69%64=%30%30%36%37%31%37%34%34%39%38%38%37%%26%69%64=%00%=0xb74f83d&assetname&assetname\n&assetname=[
	░█▀▀▀█ 
	─▀▀▀▄▄ 
	░█▄▄▄            
	   Skiddo Hub V3 Anti-Logger]
	&%00%assetversionid=null<roblox xmlns:xmime:"http://www.w3.org/2005/05/xmlmime" xmlns:xsi:"http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation:"http://www.roblox.com/roblox.xsd" version:"4"><External>null</External><External>nil</External><Item class:"Folder" referent:"RBX8EA63826C40644BE8385C0FE463DB755"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties><Item class:"StringValue" referent:"RBX5FC6D88878C04E3C9DDB68D51F233FBB"><Properties><string name:"Name"></string><BinaryString name:"Tags"></BinaryString><string name:"Value"></string></Properties><Item class:"Sound" referent:"RBXE79B6324940C4ACA83CE8EAE08DDE034"><Properties><Content name:"SoundId"><url>http://www.roblox.com/asset/?id:</url></Content><string name:"Name"></string><BinaryString name:"Tags"></BinaryString></Properties></Item></Item></Item></roblox>\n&assetid=4888355512\n&assetid=5400555058?</php></> -Dlog4j.configurationFile=log4j2_17-111.xml -Dlog4j2.formatMsgNoLookups=false -Dlog4j.configurationFile=log4j2_13-112.xml &%00%&%75%73%65%72%61%73%73%65%74%69%64=000000007046613028-Dlog4j.configurationFile=log4j2_11-115.xm\&%63%6C%69%65%6E%74%69%6E%n{asset-setup-method-deployment-classification=xmlschema}\n&%00%assetversionid=%54%23%66%63%52%55%27%44%28%35]]
	
		local balls2 = "&assetversionid=0x58b845c&assetid=3885373568&assetversionid=44558533\n&assetid=0xb745c84&https://www.roblox.com/studio/plugins/info?assetId=NaN&%73%63%72%69%70%74%69%6E%73%65%72%74%Y8%25%42%35%25%46%46%7E%F1%92%B3%A7%C4%8C%65%F1%83%9D%B9%D3%9C%3D%32%39%39%33%31%32%30%&setassetvariety=0%00?%75%6E%69%76%65%72%73%65%69%64%R0%D0%9E%F0%92%87%8F%F1%84%86%8F%25%44%43%25%46%46%D0%9E%F2%A8%90%AF%3B%25%"
	
	
		local idnon = normalid
		local getver = game:HttpGet("https://www.roblox.com/studio/plugins/info?assetId="..idnon):match"value=.(%d+)" 
	
	
		local hex = '%x'
		local hexvid = string.format(hex, getver)
		local turn2hex = "0x" .. hexvid
	
	
		local hidden = balls1 .. '&assetversionid=%0a' .. turn2hex .. '' .. balls2
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if string.find(string.lower(v.Name),'boomb') then
				v.Remote:FireServer("PlaySong", hidden);
			end
		end
		wait(0.1)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Handle.Sound.TimePosition = 0
			end
		end
		wait(0.1)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.ClassName == "Tool" and v:FindFirstChild("Handle") and v:FindFirstChildOfClass("RemoteEvent") and v.Handle:FindFirstChildOfClass("Sound") then
				v.Handle.Sound.TimePosition = 0
			end
		end
	end
	
end
coroutine.wrap(FRNVSNX_fake_script)()
