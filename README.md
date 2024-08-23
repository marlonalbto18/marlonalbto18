local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Untitled ScriptHub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Hub-1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "ScriptHub"
})

OrionLib:MakeNotification({
	Name = "LOADED! ( WIP )!",
	Content = "ScriptHub Made by Mar",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "Red Dot Lock",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/reddot1/main/reddot1", true))()
  	end    
})

Tab:AddButton({
	Name = "SH",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/SCRIPTHUBV2/main/SCRIPTHUBV2", true))()
  	end    
})

Tab:AddButton({
	Name = "Q tool",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/qtoolv3/main/qtoolv3", true))()
  	end    
})

Tab:AddButton({
	Name = "FOV (made by me) *OP*",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/iecEeWtN", true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Player.lua/main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Main"
})

Tab:AddButton({
	Name = "Speed!",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/backupspeedtool/main/backupspeedtool", true))()
  	end    
})

Tab:AddButton({
	Name = "Roblox Speed ( undetected ) !",
	Callback = function()
      		LocalPlayer.Huamanoid.WalkSpeed = +50
  	end    
})

Tab:AddButton({
	Name = "Roblox Speed ( undetected ) !",
	Callback = function()
      		LocalPlayer.Huamanoid.WalkSpeed = +16
  	end    
})
