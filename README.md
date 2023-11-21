local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "random thing", HidePremium = false, introtext = "مرحبا بك", SaveConfig = true, ConfigFolder = "OrionTest"})




local scripts = Window:MakeTab({
	Name = "للسخريه",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = scripts:AddSection({
	Name = "scripts"
})


OrionLib:MakeNotification({
	Name = "SPDM!",
	Content = "OWNER",
	Image = "rbxassetid://4483345998",
	Time = 5
})

scripts:AddButton({
	Name = "تلطيم",
	Callback = function()
      		loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_rf6iQURzu1fqrytcnLBAvW34C9N55kS9g9G3CKz086rC47M6632sEd4ZZYB0AYgV.lua.txt'),true))()
  	end    
})

scripts:AddButton({
	Name = "تنقل",
	Callback = function()
      		mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Equip to Click TP"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
  	end    
  })






scripts:AddToggle({
	Name = "anti fling",
	Default = false,
	Callback = function(Value)
       print (true)
  end
})

while _g == "anti fling" do

loadstring(game:HttpGet("https://pastebin.com/raw/Q0Nh2SYx", true))()
end



  
local scripts = Window:MakeTab({
	Name = "سكربتات اضافيه",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = scripts:AddSection({
	Name = "عشوائي"
})

Section:AddButton({
	Name = "infnite yiels",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})

Section:AddButton({
	Name = "unslagger",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/enrabiaaa/Unslagger.exe/main/Script.lua"))()
  	end    
})


OrionLib:Init()
