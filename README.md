# Telhub 


local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()



local Window = Library.CreateLib("tel hub", "DarkTheme")



local Tab = Window:NewTab("tel hub")
 
Section:NewLabel("tel hub")

 






local IceHub = loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()


local menu = IceHub:CreateMenu("IceHub - BrookHaven")


local general = menu:AddSection("Geral")


general:AddButton("Matar Todos", function()
    IceHub:KillAll()
end)


general:AddButton("Lançar Todos", function()
    IceHub:FlingAll()
end)


general:AddButton("Vazio Todos", function()
    IceHub:VoidAll()
end)


local teleport = menu:AddSection("Teletransporte")


teleport:AddButton("Hospital", function()
    IceHub:Teleport("Hospital")
end)


teleport:AddButton("Delegacia", function()
    IceHub:Teleport("Delegacia")
end)


teleport:AddButton("Escola", function()
    IceHub:Teleport("Escola")
end)


local customize = menu:AddSection("Personalizar")



customize:AddColorPicker("Cor do Cabelo", Color3.new(1, 1, 1), function(color)
    IceHub:ChangeHairColor(color)
end)



customize:AddColorPicker("Cor da Pele", Color3.new(1, 1, 1), function(color)
    IceHub:ChangeSkinColor(color)
end)



customize:AddSlider("Tamanho do Corpo", 0, 100, 50, function(size)
    IceHub:ChangeBodySize(size)
end)



local vehicles = menu:AddSection("Veículos")


vehicles:AddButton("Spawnar Carro", function()
    IceHub:SpawnVehicle("Car")
end)


vehicles:AddButton("Spawnar Moto", function()
    IceHub:SpawnVehicle("Bike")
end)


vehicles:AddButton("Spawnar Helicóptero", function()
    IceHub:SpawnVehicle("Helicopter")
end)


local credits = menu:AddSection("Créditos")



credits:AddLabel("IceHub - BrookHaven\nCriado por Icy\nGerado por Rafael")
```


