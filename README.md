local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Star Hub : Acesso Antecipado", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Olá!",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("Olá","Este e o Star Hub! Um projeto que posso dizer que deu certo...Pois teve milhares de versões! Mas essa deu certo espero que você goste do script!")
Tab:AddButton({
	Name = "Nosso discord!",
	Callback = function()
      		setclipboard("https://discord.gg/kBDk5YMR2R")
  	end    
})

local Tab = Window:MakeTab({
	Name = "Brookhaven!",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Sem Key"
})

Tab:AddButton({
	Name = "Rael Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Laelmano24/Rael-Hub/refs/heads/main/Universal/script.txt"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Com Key"
})

Tab:AddButton({
	Name = "Chaos Hub",
	Callback = function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Em Breve!"
})

Tab:AddButton({
	Name = "Jãozin Hub!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Eita..",
	Content = "Achou mesmo que estava mentindo?",
	Image = "rbxassetid://4483345998",
	Time = 5
})
  	
l
