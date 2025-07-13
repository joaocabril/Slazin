-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local principal = Instance.new("Frame")
local barra = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local barra_2 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local fechar = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local tradutor = Instance.new("ImageButton")
local UICorner_6 = Instance.new("UICorner")
local sessoes = Instance.new("Frame")
local autofarm = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local aimbot = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local misc = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local UICorner_10 = Instance.new("UICorner")
local perfil = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_11 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local barra_3 = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local UICorner_13 = Instance.new("UICorner")
local farmTela = Instance.new("Frame")
local barra_4 = Instance.new("Frame")
local UICorner_14 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local erva = Instance.new("Frame")
local UICorner_15 = Instance.new("UICorner")
local titulo = Instance.new("TextLabel")
local descricao = Instance.new("TextLabel")
local descricao2 = Instance.new("TextLabel")
local erva_2 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local lixo = Instance.new("Frame")
local UICorner_17 = Instance.new("UICorner")
local titulo_2 = Instance.new("TextLabel")
local descricao_2 = Instance.new("TextLabel")
local descricao2_2 = Instance.new("TextLabel")
local erva_3 = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local UIGradient_2 = Instance.new("UIGradient")
local miscTela = Instance.new("Frame")
local barra_5 = Instance.new("Frame")
local UICorner_19 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")
local erva_4 = Instance.new("Frame")
local UICorner_20 = Instance.new("UICorner")
local titulo_3 = Instance.new("TextLabel")
local descricao_3 = Instance.new("TextLabel")
local descricao2_3 = Instance.new("TextLabel")
local erva_5 = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local UIGradient_3 = Instance.new("UIGradient")
local lixo_2 = Instance.new("Frame")
local UICorner_22 = Instance.new("UICorner")
local titulo_4 = Instance.new("TextLabel")
local descricao_4 = Instance.new("TextLabel")
local descricao2_4 = Instance.new("TextLabel")
local erva_6 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local UIGradient_4 = Instance.new("UIGradient")
local aimbotTela = Instance.new("Frame")
local barra_6 = Instance.new("Frame")
local UICorner_24 = Instance.new("UICorner")
local TextLabel_6 = Instance.new("TextLabel")
local aimbot_2 = Instance.new("Frame")
local UICorner_25 = Instance.new("UICorner")
local titulo_5 = Instance.new("TextLabel")
local descricao_5 = Instance.new("TextLabel")
local descricao2_5 = Instance.new("TextLabel")
local aimbot_3 = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local UIGradient_5 = Instance.new("UIGradient")
local esp = Instance.new("Frame")
local UICorner_27 = Instance.new("UICorner")
local titulo_6 = Instance.new("TextLabel")
local descricao_6 = Instance.new("TextLabel")
local descricao2_6 = Instance.new("TextLabel")
local esp_2 = Instance.new("TextButton")
local UICorner_28 = Instance.new("UICorner")
local UIGradient_6 = Instance.new("UIGradient")
local minimizar = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local icon = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

principal.Name = "principal"
principal.Parent = ScreenGui
principal.BackgroundColor3 = Color3.fromRGB(8, 8, 8)
principal.BorderColor3 = Color3.fromRGB(0, 0, 0)
principal.BorderSizePixel = 0
principal.Position = UDim2.new(0, 104, 0, 249)
principal.Size = UDim2.new(0, 726, 0, 423)

barra.Name = "barra"
barra.Parent = principal
barra.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
barra.BorderColor3 = Color3.fromRGB(0, 0, 0)
barra.BorderSizePixel = 0
barra.Position = UDim2.new(0, 0, 0.122931443, 0)
barra.Size = UDim2.new(0, 242, 0, 2)

UICorner.CornerRadius = UDim.new(3, 0)
UICorner.Parent = barra

barra_2.Name = "barra"
barra_2.Parent = principal
barra_2.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
barra_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
barra_2.BorderSizePixel = 0
barra_2.Position = UDim2.new(0, 0, 0.267139494, 0)
barra_2.Size = UDim2.new(0, 242, 0, 2)

UICorner_2.CornerRadius = UDim.new(3, 0)
UICorner_2.Parent = barra_2

UICorner_3.Parent = barra_2

Frame.Parent = principal
Frame.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0502754822, 0, 0.5, 0)
Frame.Rotation = 90.000
Frame.Size = UDim2.new(0, 415, 0, 2)

UICorner_4.CornerRadius = UDim.new(3, 0)
UICorner_4.Parent = Frame

fechar.Name = "fechar"
fechar.Parent = Frame
fechar.BackgroundColor3 = Color3.fromRGB(226, 41, 41)
fechar.BorderColor3 = Color3.fromRGB(0, 0, 0)
fechar.BorderSizePixel = 0
fechar.Position = UDim2.new(0.0329524763, 0, 108.544922, 0)
fechar.Size = UDim2.new(0, 14, 0, 14)
fechar.Font = Enum.Font.SourceSans
fechar.Text = ""
fechar.TextColor3 = Color3.fromRGB(0, 0, 0)
fechar.TextSize = 14.000

UICorner_5.CornerRadius = UDim.new(3, 0)
UICorner_5.Parent = fechar

TextLabel.Parent = principal
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.00964187365, 0, 0.196217492, -6)
TextLabel.Size = UDim2.new(0, 99, 0, 36)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "version 1.2"
TextLabel.TextColor3 = Color3.fromRGB(70, 70, 70)
TextLabel.TextSize = 10.000

tradutor.Name = "tradutor"
tradutor.Parent = principal
tradutor.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
tradutor.BackgroundTransparency = 1.000
tradutor.BorderColor3 = Color3.fromRGB(0, 0, 0)
tradutor.BorderSizePixel = 0
tradutor.Position = UDim2.new(0.275482088, 0, 0.167848706, -3)
tradutor.Size = UDim2.new(0, 30, 0, 30)
tradutor.Image = "rbxassetid://99168416700344"

UICorner_6.CornerRadius = UDim.new(0, 5)
UICorner_6.Parent = tradutor

sessoes.Name = "sessoes"
sessoes.Parent = principal
sessoes.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sessoes.BackgroundTransparency = 1.000
sessoes.BorderColor3 = Color3.fromRGB(0, 0, 0)
sessoes.BorderSizePixel = 0
sessoes.Position = UDim2.new(0, 0, 0.271867603, 0)
sessoes.Size = UDim2.new(0, 242, 0, 203)

autofarm.Name = "autofarm"
autofarm.Parent = sessoes
autofarm.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
autofarm.BackgroundTransparency = 1.000
autofarm.BorderColor3 = Color3.fromRGB(0, 0, 0)
autofarm.BorderSizePixel = 0
autofarm.Position = UDim2.new(0.02892562, 0, 0.103448279, 0)
autofarm.Size = UDim2.new(0, 200, 0, 41)
autofarm.Font = Enum.Font.Roboto
autofarm.Text = "   AutoFarm"
autofarm.TextColor3 = Color3.fromRGB(175, 175, 175)
autofarm.TextSize = 21.000
autofarm.TextXAlignment = Enum.TextXAlignment.Left

UICorner_7.CornerRadius = UDim.new(0, 6)
UICorner_7.Parent = autofarm

aimbot.Name = "aimbot"
aimbot.Parent = sessoes
aimbot.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
aimbot.BackgroundTransparency = 1.000
aimbot.BorderColor3 = Color3.fromRGB(0, 0, 0)
aimbot.BorderSizePixel = 0
aimbot.Position = UDim2.new(0.02892562, 0, 0.30541873, 0)
aimbot.Size = UDim2.new(0, 200, 0, 41)
aimbot.Font = Enum.Font.Roboto
aimbot.Text = "   Aimbot"
aimbot.TextColor3 = Color3.fromRGB(175, 175, 175)
aimbot.TextSize = 21.000
aimbot.TextXAlignment = Enum.TextXAlignment.Left

UICorner_8.CornerRadius = UDim.new(0, 6)
UICorner_8.Parent = aimbot

misc.Name = "misc"
misc.Parent = sessoes
misc.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
misc.BackgroundTransparency = 1.000
misc.BorderColor3 = Color3.fromRGB(0, 0, 0)
misc.BorderSizePixel = 0
misc.Position = UDim2.new(0.02892562, 0, 0.507389188, 0)
misc.Size = UDim2.new(0, 200, 0, 41)
misc.Font = Enum.Font.Roboto
misc.Text = "   Misc"
misc.TextColor3 = Color3.fromRGB(175, 175, 175)
misc.TextSize = 21.000
misc.TextXAlignment = Enum.TextXAlignment.Left

UICorner_9.CornerRadius = UDim.new(0, 6)
UICorner_9.Parent = misc

UICorner_10.CornerRadius = UDim.new(0, 7)
UICorner_10.Parent = principal

perfil.Name = "perfil"
perfil.Parent = principal
perfil.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
perfil.BackgroundTransparency = 1.000
perfil.BorderColor3 = Color3.fromRGB(0, 0, 0)
perfil.BorderSizePixel = 0
perfil.Position = UDim2.new(0, 0, 0.756501198, 0)
perfil.Size = UDim2.new(0, 242, 0, 100)

TextLabel_2.Parent = perfil
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.252066106, 0, 0.22657226, 0)
TextLabel_2.Size = UDim2.new(0, 99, 0, 36)
TextLabel_2.Font = Enum.Font.Roboto
TextLabel_2.Text = "u9huz"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 19.000

ImageLabel.Parent = perfil
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.05785124, 0, 0.316572279, 0)
ImageLabel.Size = UDim2.new(0, 37, 0, 37)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_11.CornerRadius = UDim.new(0, 6)
UICorner_11.Parent = ImageLabel

TextLabel_3.Parent = perfil
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.338842988, 0, 0.386572272, 3)
TextLabel_3.Size = UDim2.new(0, 99, 0, 36)
TextLabel_3.Font = Enum.Font.Roboto
TextLabel_3.Text = "32183123213"
TextLabel_3.TextColor3 = Color3.fromRGB(175, 175, 175)
TextLabel_3.TextSize = 15.000

barra_3.Name = "barra"
barra_3.Parent = principal
barra_3.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
barra_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
barra_3.BorderSizePixel = 0
barra_3.Position = UDim2.new(0, 0, 0.744680822, 0)
barra_3.Size = UDim2.new(0, 242, 0, 2)

UICorner_12.CornerRadius = UDim.new(3, 0)
UICorner_12.Parent = barra_3

UICorner_13.Parent = barra_3

farmTela.Name = "farmTela"
farmTela.Parent = principal
farmTela.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
farmTela.BackgroundTransparency = 1.000
farmTela.BorderColor3 = Color3.fromRGB(0, 0, 0)
farmTela.BorderSizePixel = 0
farmTela.Position = UDim2.new(0.333333343, 0, 0, 0)
farmTela.Size = UDim2.new(0, 484, 0, 423)
farmTela.Visible = false

barra_4.Name = "barra"
barra_4.Parent = farmTela
barra_4.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
barra_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
barra_4.BorderSizePixel = 0
barra_4.Position = UDim2.new(0, 0, 0.0756501183, 0)
barra_4.Size = UDim2.new(0, 484, 0, 2)

UICorner_14.CornerRadius = UDim.new(3, 0)
UICorner_14.Parent = barra_4

TextLabel_4.Parent = farmTela
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.293388426, 0, -0.0212765951, 0)
TextLabel_4.Size = UDim2.new(0, 200, 0, 50)
TextLabel_4.Font = Enum.Font.Roboto
TextLabel_4.Text = "Autofarm"
TextLabel_4.TextColor3 = Color3.fromRGB(175, 175, 175)
TextLabel_4.TextSize = 19.000
TextLabel_4.TextStrokeTransparency = 0.520

erva.Name = "erva"
erva.Parent = farmTela
erva.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
erva.BorderColor3 = Color3.fromRGB(0, 0, 0)
erva.BorderSizePixel = 0
erva.Position = UDim2.new(0.027885247, 0, 0.122931443, 0)
erva.Size = UDim2.new(0, 196, 0, 207)

UICorner_15.CornerRadius = UDim.new(0, 7)
UICorner_15.Parent = erva

titulo.Name = "titulo"
titulo.Parent = erva
titulo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
titulo.BackgroundTransparency = 1.000
titulo.BorderColor3 = Color3.fromRGB(0, 0, 0)
titulo.BorderSizePixel = 0
titulo.Position = UDim2.new(0.0545737967, 0, 0.075630255, 0)
titulo.Size = UDim2.new(0, 90, 0, 30)
titulo.Font = Enum.Font.Roboto
titulo.Text = "Farm Erva"
titulo.TextColor3 = Color3.fromRGB(175, 175, 175)
titulo.TextSize = 20.000
titulo.TextStrokeTransparency = 0.520

descricao.Name = "descricao"
descricao.Parent = erva
descricao.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
descricao.BackgroundTransparency = 1.000
descricao.BorderColor3 = Color3.fromRGB(0, 0, 0)
descricao.BorderSizePixel = 0
descricao.Position = UDim2.new(0.244089872, -1, 0.347617328, 3)
descricao.Size = UDim2.new(0, 90, 0, 30)
descricao.Font = Enum.Font.Roboto
descricao.Text = "Farmar Erva"
descricao.TextColor3 = Color3.fromRGB(255, 255, 255)
descricao.TextSize = 19.000
descricao.TextStrokeTransparency = 0.820

descricao2.Name = "descricao2"
descricao2.Parent = erva
descricao2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
descricao2.BackgroundTransparency = 1.000
descricao2.BorderColor3 = Color3.fromRGB(0, 0, 0)
descricao2.BorderSizePixel = 0
descricao2.Position = UDim2.new(-0.00319438078, 0, 0.458937198, -6)
descricao2.Size = UDim2.new(0, 188, 0, 100)
descricao2.Font = Enum.Font.Roboto
descricao2.Text = "Para o funcionamento correto, Ã© necessÃ¡rio possuir pelo menos uma FAC."
descricao2.TextColor3 = Color3.fromRGB(175, 175, 175)
descricao2.TextSize = 17.000
descricao2.TextStrokeTransparency = 0.820
descricao2.TextTransparency = 0.300
descricao2.TextWrapped = true

erva_2.Name = "erva"
erva_2.Parent = erva
erva_2.BackgroundColor3 = Color3.fromRGB(127, 127, 127)
erva_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
erva_2.BorderSizePixel = 0
erva_2.Position = UDim2.new(0.791553617, 0, 0.0924369767, -1)
erva_2.Size = UDim2.new(0, 24, 0, 24)
erva_2.Font = Enum.Font.SourceSans
erva_2.Text = ""
erva_2.TextColor3 = Color3.fromRGB(0, 0, 0)
erva_2.TextSize = 14.000

UICorner_16.CornerRadius = UDim.new(3, 0)
UICorner_16.Parent = erva_2

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(122, 122, 122)), ColorSequenceKeypoint.new(0.49, Color3.fromRGB(166, 166, 166)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = erva_2

lixo.Name = "lixo"
lixo.Parent = farmTela
lixo.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
lixo.BorderColor3 = Color3.fromRGB(0, 0, 0)
lixo.BorderSizePixel = 0
lixo.Position = UDim2.new(0.57333982, 0, 0.122931443, 0)
lixo.Size = UDim2.new(0, 196, 0, 207)

UICorner_17.CornerRadius = UDim.new(0, 7)
UICorner_17.Parent = lixo

titulo_2.Name = "titulo"
titulo_2.Parent = lixo
titulo_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
titulo_2.BackgroundTransparency = 1.000
titulo_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
titulo_2.BorderSizePixel = 0
titulo_2.Position = UDim2.new(0.0545737967, 0, 0.075630255, 0)
titulo_2.Size = UDim2.new(0, 90, 0, 30)
titulo_2.Font = Enum.Font.Roboto
titulo_2.Text = "Farm Lixo"
titulo_2.TextColor3 = Color3.fromRGB(175, 175, 175)
titulo_2.TextSize = 20.000
titulo_2.TextStrokeTransparency = 0.520

descricao_2.Name = "descricao"
descricao_2.Parent = lixo
descricao_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
descricao_2.BackgroundTransparency = 1.000
descricao_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
descricao_2.BorderSizePixel = 0
descricao_2.Position = UDim2.new(0.27470243, -1, 0.347617328, 3)
descricao_2.Size = UDim2.new(0, 90, 0, 30)
descricao_2.Font = Enum.Font.Roboto
descricao_2.Text = "Farmar Lixo"
descricao_2.TextColor3 = Color3.fromRGB(255, 255, 255)
descricao_2.TextSize = 19.000
descricao_2.TextStrokeTransparency = 0.820

descricao2_2.Name = "descricao2"
descricao2_2.Parent = lixo
descricao2_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
descricao2_2.BackgroundTransparency = 1.000
descricao2_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
descricao2_2.BorderSizePixel = 0
descricao2_2.Position = UDim2.new(0.0580301099, 0, 0.415458947, -6)
descricao2_2.Size = UDim2.new(0, 173, 0, 117)
descricao2_2.Font = Enum.Font.Roboto
descricao2_2.Text = "VocÃª precisa estar no trabalho de lixeiro para que funcione corretamente."
descricao2_2.TextColor3 = Color3.fromRGB(175, 175, 175)
descricao2_2.TextSize = 17.000
descricao2_2.TextStrokeTransparency = 0.820
descricao2_2.TextTransparency = 0.300
descricao2_2.TextWrapped = true

erva_3.Name = "erva"
erva_3.Parent = lixo
erva_3.BackgroundColor3 = Color3.fromRGB(127, 127, 127)
erva_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
erva_3.BorderSizePixel = 0
erva_3.Position = UDim2.new(0.791553617, 0, 0.0924369767, -1)
erva_3.Size = UDim2.new(0, 24, 0, 24)
erva_3.Font = Enum.Font.SourceSans
erva_3.Text = ""
erva_3.TextColor3 = Color3.fromRGB(0, 0, 0)
erva_3.TextSize = 14.000

UICorner_18.CornerRadius = UDim.new(3, 0)
UICorner_18.Parent = erva_3

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(122, 122, 122)), ColorSequenceKeypoint.new(0.49, Color3.fromRGB(166, 166, 166)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Parent = erva_3

miscTela.Name = "miscTela"
miscTela.Parent = principal
miscTela.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
miscTela.BackgroundTransparency = 1.000
miscTela.BorderColor3 = Color3.fromRGB(0, 0, 0)
miscTela.BorderSizePixel = 0
miscTela.Position = UDim2.new(0.333333343, 0, 0, 0)
miscTela.Size = UDim2.new(0, 484, 0, 423)

barra_5.Name = "barra"
barra_5.Parent = miscTela
barra_5.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
barra_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
barra_5.BorderSizePixel = 0
barra_5.Position = UDim2.new(0, 0, 0.0756501183, 0)
barra_5.Size = UDim2.new(0, 484, 0, 2)

UICorner_19.CornerRadius = UDim.new(3, 0)
UICorner_19.Parent = barra_5

TextLabel_5.Parent = miscTela
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.293388426, 0, -0.0212765951, 0)
TextLabel_5.Size = UDim2.new(0, 200, 0, 50)
TextLabel_5.Font = Enum.Font.Roboto
TextLabel_5.Text = "Misc"
TextLabel_5.TextColor3 = Color3.fromRGB(175, 175, 175)
TextLabel_5.TextSize = 19.000
TextLabel_5.TextStrokeTransparency = 0.520

erva_4.Name = "erva"
erva_4.Parent = miscTela
erva_4.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
erva_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
erva_4.BorderSizePixel = 0
erva_4.Position = UDim2.new(0.027885247, 0, 0.122931443, 0)
erva_4.Size = UDim2.new(0, 196, 0, 207)

UICorner_20.CornerRadius = UDim.new(0, 7)
UICorner_20.Parent = erva_4

titulo_3.Name = "titulo"
titulo_3.Parent = erva_4
titulo_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
titulo_3.BackgroundTransparency = 1.000
titulo_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
titulo_3.BorderSizePixel = 0
titulo_3.Position = UDim2.new(0.0545737967, 0, 0.075630255, 0)
titulo_3.Size = UDim2.new(0, 90, 0, 30)
titulo_3.Font = Enum.Font.Roboto
titulo_3.Text = "Anti Staff"
titulo_3.TextColor3 = Color3.fromRGB(175, 175, 175)
titulo_3.TextSize = 20.000
titulo_3.TextStrokeTransparency = 0.520

descrica
