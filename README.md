# Telhub 
--tel hub

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

--Windows 

local Window = Library.CreateLib("tel hub", "DarkTheme")

--tabs

local Tab = Window:NewTab("tel hub")
 
Section:NewLabel("tel hub")

--script 


--```lua
-- IceHub - BrookHaven
-- Criado por Bing

-- Carrega a biblioteca IceHub
local IceHub = loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()

-- Cria um menu com opções para o jogo
local menu = IceHub:CreateMenu("IceHub - BrookHaven")

-- Adiciona uma seção de funções gerais
local general = menu:AddSection("Geral")

-- Adiciona uma função para matar todos os jogadores
general:AddButton("Matar Todos", function()
    IceHub:KillAll()
end)

-- Adiciona uma função para lançar todos os jogadores
general:AddButton("Lançar Todos", function()
    IceHub:FlingAll()
end)

-- Adiciona uma função para enviar todos os jogadores para o vazio
general:AddButton("Vazio Todos", function()
    IceHub:VoidAll()
end)

-- Adiciona uma seção de funções de teletransporte
local teleport = menu:AddSection("Teletransporte")

-- Adiciona uma função para teletransportar para o hospital
teleport:AddButton("Hospital", function()
    IceHub:Teleport("Hospital")
end)

-- Adiciona uma função para teletransportar para a delegacia
teleport:AddButton("Delegacia", function()
    IceHub:Teleport("Delegacia")
end)

-- Adiciona uma função para teletransportar para a escola
teleport:AddButton("Escola", function()
    IceHub:Teleport("Escola")
end)

-- Adiciona uma seção de funções de personalização
local customize = menu:AddSection("Personalizar")

-- Adiciona uma função para mudar a cor do cabelo
customize:AddColorPicker("Cor do Cabelo", Color3.new(1, 1, 1), function(color)
    IceHub:ChangeHairColor(color)
end)

-- Adiciona uma função para mudar a cor da pele
customize:AddColorPicker("Cor da Pele", Color3.new(1, 1, 1), function(color)
    IceHub:ChangeSkinColor(color)
end)

-- Adiciona uma função para mudar o tamanho do corpo
customize:AddSlider("Tamanho do Corpo", 0, 100, 50, function(size)
    IceHub:ChangeBodySize(size)
end)

-- Adiciona uma seção de funções de veículos
local vehicles = menu:AddSection("Veículos")

-- Adiciona uma função para spawnar um carro
vehicles:AddButton("Spawnar Carro", function()
    IceHub:SpawnVehicle("Car")
end)

-- Adiciona uma função para spawnar uma moto
vehicles:AddButton("Spawnar Moto", function()
    IceHub:SpawnVehicle("Bike")
end)

-- Adiciona uma função para spawnar um helicóptero
vehicles:AddButton("Spawnar Helicóptero", function()
    IceHub:SpawnVehicle("Helicopter")
end)

-- Adiciona uma seção de créditos
local credits = menu:AddSection("Créditos")

-- Adiciona um texto com os créditos
credits:AddLabel("IceHub - BrookHaven\nCriado por Icy\nGerado por Rafael")
```

--Espero que você goste do script que eu gerei. Você pode encontrar mais informações sobre o icehub Brookhaven nos seguintes links:

--[IceHub - BrookHaven - Pastebin.com](^1^)
--[NEW! Ice Hub V4.7 - [Update!] Brookhaven RP Op Gui Script ... - YouTube](^2^)
-- [IceHub Brookhaven RP Script - BloxScript4You](^3^)
-- [Icehub Script Brookhaven, Direct Copy &

--(1) IceHub - BrookHaven - Pastebin.com. https://pastebin.com/Jh1eKH9e.
--(2) NEW! Ice Hub V4.7 - [Update!] Brookhaven RP Op Gui Script ... - YouTube. 
