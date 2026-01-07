local redzlib = loadstring(game:HttpGet("https://api.rubis.app/v2/scrap/XpaZxjXIqaYnGNgY/raw"))()

local Window = redzlib:MakeWindow({
    Title = "Teste Hub  | Brookhaven RP",
    SubTitle = "by Denolk // Versão 1.1 Beta",
    SaveFolder = "testehubfolder"
  })

  Window:AddMinimizeButton({
    Button = { Image = "rbxassetid://", BackgroundTransparency = 0 },
    Corner = { CornerRadius = UDim.new(35, 1) },
})

local Tab = Window:MakeTab({"Teste", "list"})
