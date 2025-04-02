local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/Star-dos-scripts/OrionLibYellow/refs/heads/main/README.md')))()')))()
local Window = OrionLib:MakeWindow({Name = "StarHUB : ACESSO ANTECIPADO", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Olá",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddParagraph("Olá","Digo Olá de respeito a vc!")
Tab:AddButton({
	Name = "Button!",
	Callback = function()
	   setclipboard("https://discord.gg/TVMucqmj")
  	end    
})
local Tab = Window:MakeTab({
	Name = "Brookhaven",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "KEY"
})
Tab:AddButton({
	Name = "Chaos HUB",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))()
  	end    
})
