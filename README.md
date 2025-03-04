-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Abrir = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local perfil = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Copiarlikndeyoutube = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local ejecutaelscript = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Abrir.Name = "Abrir"
Abrir.Parent = ScreenGui
Abrir.BackgroundColor3 = Color3.fromRGB(0, 255, 8)
Abrir.BorderColor3 = Color3.fromRGB(0, 0, 0)
Abrir.BorderSizePixel = 0
Abrir.Position = UDim2.new(0, 0, 0.732171118, 0)
Abrir.Size = UDim2.new(0, 162, 0, 41)
Abrir.Font = Enum.Font.Bangers
Abrir.Text = "abrir"
Abrir.TextColor3 = Color3.fromRGB(0, 0, 0)
Abrir.TextScaled = true
Abrir.TextSize = 14.000
Abrir.TextWrapped = true

UICorner.Parent = Abrir

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(28, 255, 12)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.660262883, 0, 0.160063386, 0)
Frame.Size = UDim2.new(0, 336, 0, 180)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(38, 255, 0)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0, 0, 0.48888889, 0)
TextLabel.Size = UDim2.new(0, 336, 0, 40)
TextLabel.Font = Enum.Font.Bangers
TextLabel.Text = "Creado por ELOSO: HElPER"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_3.Parent = TextLabel

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(38, 255, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(0, 336, 0, 40)
TextLabel_2.Font = Enum.Font.Bangers
TextLabel_2.Text = "frame CReado POr YAnser_EXPLOIT OWNER"
TextLabel_2.TextColor3 = Color3.fromRGB(252, 26, 26)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeColor3 = Color3.fromRGB(104, 26, 0)
TextLabel_2.TextWrapped = true

UICorner_4.Parent = TextLabel_2

perfil.Name = "perfil"
perfil.Parent = Frame
perfil.BackgroundColor3 = Color3.fromRGB(26, 255, 0)
perfil.BorderColor3 = Color3.fromRGB(0, 0, 0)
perfil.BorderSizePixel = 0
perfil.Position = UDim2.new(0, 0, 0.711111128, 0)
perfil.Size = UDim2.new(0, 336, 0, 48)
perfil.Font = Enum.Font.Cartoon
perfil.Text = "COPIAR LIK DE  PERFIL ROBLOX "
perfil.TextColor3 = Color3.fromRGB(0, 0, 0)
perfil.TextScaled = true
perfil.TextSize = 14.000
perfil.TextWrapped = true

UICorner_5.Parent = perfil

Copiarlikndeyoutube.Name = "Copiar likn de youtube"
Copiarlikndeyoutube.Parent = Frame
Copiarlikndeyoutube.BackgroundColor3 = Color3.fromRGB(26, 255, 0)
Copiarlikndeyoutube.BorderColor3 = Color3.fromRGB(0, 0, 0)
Copiarlikndeyoutube.BorderSizePixel = 0
Copiarlikndeyoutube.Position = UDim2.new(0, 0, 0.222222224, 0)
Copiarlikndeyoutube.Size = UDim2.new(0, 336, 0, 48)
Copiarlikndeyoutube.Font = Enum.Font.Bangers
Copiarlikndeyoutube.Text = "COPIAR LIKN DE YOUTUBE"
Copiarlikndeyoutube.TextColor3 = Color3.fromRGB(255, 0, 0)
Copiarlikndeyoutube.TextScaled = true
Copiarlikndeyoutube.TextSize = 14.000
Copiarlikndeyoutube.TextWrapped = true

UICorner_6.Parent = Copiarlikndeyoutube

ejecutaelscript.Name = "ejecuta el script"
ejecutaelscript.Parent = Frame
ejecutaelscript.BackgroundColor3 = Color3.fromRGB(26, 255, 0)
ejecutaelscript.BorderColor3 = Color3.fromRGB(0, 0, 0)
ejecutaelscript.BorderSizePixel = 0
ejecutaelscript.Position = UDim2.new(-0.0178571437, 0, 1.13333333, 0)
ejecutaelscript.Size = UDim2.new(0, 336, 0, 48)
ejecutaelscript.Font = Enum.Font.Bangers
ejecutaelscript.Text = "EJECUTAR EL SCRIPT"
ejecutaelscript.TextColor3 = Color3.fromRGB(0, 0, 0)
ejecutaelscript.TextScaled = true
ejecutaelscript.TextSize = 14.000
ejecutaelscript.TextWrapped = true
ejecutaelscript.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/pUvk88GY"))()
end)

UICorner_7.Parent = ejecutaelscript

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 30, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.791666687, 0, -0.150000006, 0)
TextButton.Size = UDim2.new(0, 64, 0, 27)
TextButton.Font = Enum.Font.Bangers
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_8.Parent = TextButton

-- Scripts:

local function XMBNBY_fake_script() -- Abrir.LocalScript 
	local script = Instance.new('LocalScript', Abrir)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui.ScreenGui.Frame.Visible = true
	end)
end
coroutine.wrap(XMBNBY_fake_script)()
local function WJWB_fake_script() -- perfil.LocalScript 
	local script = Instance.new('LocalScript', perfil)

	-- LocalScript dentro del TextButton
	
	local textButton = script.Parent -- El TextButton en el que este script está adjunto
	local linkToCopy = "https://www.roblox.com/es/users/3665892293/profile" -- El enlace que deseas copiar al portapapeles
	
	-- Función que cambia el texto del botón a "Copiado"
	local function cambiarTexto()
		textButton.Text = "Copiado gracias!"
	end
	
	-- Función para copiar el enlace al portapapeles
	local function copiarAlPortapapeles()
		setclipboard(linkToCopy) -- Usa la función setclipboard para copiar al portapapeles
	end
	
	-- Evento para detectar cuando se hace clic en el TextButton
	textButton.MouseButton1Click:Connect(function()
		copiarAlPortapapeles() -- Copiar el enlace
		cambiarTexto() -- Cambiar el texto a "Copiado"
	end)
	
end
coroutine.wrap(WJWB_fake_script)()
local function DQXFIKZ_fake_script() -- Copiarlikndeyoutube.LocalScript 
	local script = Instance.new('LocalScript', Copiarlikndeyoutube)

	-- LocalScript dentro del TextButton
	
	local textButton = script.Parent -- El TextButton en el que este script está adjunto
	local linkToCopy = "https://www.youtube.com/@YANSER_EXPLOIT" -- El enlace que deseas copiar al portapapeles
	
	-- Función que cambia el texto del botón a "Copiado"
	local function cambiarTexto()
		textButton.Text = "Copiado"
	end
	
	-- Función para copiar el enlace al portapapeles
	local function copiarAlPortapapeles()
		setclipboard(linkToCopy) -- Usa la función setclipboard para copiar al portapapeles
	end
	
	-- Evento para detectar cuando se hace clic en el TextButton
	textButton.MouseButton1Click:Connect(function()
		copiarAlPortapapeles() -- Copiar el enlace
		cambiarTexto() -- Cambiar el texto a "Copiado"
	end)
	
	
end
coroutine.wrap(DQXFIKZ_fake_script)()
local function PTXINB_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui.ScreenGui.Frame.Visible = false
	end)
end
coroutine.wrap(PTXINB_fake_script)()
