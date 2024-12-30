if game.PlaceId == 18343561950 then
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "KaChun | Ball Tower Defense [🎄CHRISTMAS-EVENT🎄]", HidePremium = false, SaveConfig = true, ConfigFolder = "KaChunConfig"})

local Tab = Window:MakeTab({
	Name = "AutoAFK",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

FramTab:AddToggle({
	Name = "Auto AFK",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
})



end
OrionLib:Init()
