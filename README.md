----- MAP ------
--[[
[+] Online Business Simulator 2
[+] Star Simulator Beta
[+] Shoe Simulator
[+] Eating Simulator
[+] Fall of Hell
[+] Tower of hell
[+] Tower of mistery
[+] Ultimate Tower Defense
[+] Collect All Pets!
[+] Giant Survival
[+] Natural Disaster Survival
[+] Legends Of Speed
[+] Base Battles
[+] Pet Adventure Simulator!
[+] Break In (Story)
[+] Teleporter Simulator
[+] Pet Simulator x
[+] Shark Bite
[+] Survive The Killers
]]

--- Dont By Pass This
wait(1)
game.StarterGui:SetCore("SendNotification", {
Title = "Loaded Scripts"; 
Text = "Loaded";
Duration = 1; 
})

wait(1)
spawn(function()
    game.StarterGui:SetCore("SendNotification", {
	Title = "Anti Afk Always On"; 
	Text = "Anti Afk Always On";
	Icon = ""; 
	Duration = 1; 
})
end) 

for i,v in pairs(getconnections(game.Players.LocalPlayer.Idled)) do
v:Disable()
end

wait(2)
bc = BrickColor.new("White")
game.StarterGui:SetCore("ChatMakeSystemMessage", {
	Text = "Pog Hub No Carte | discord.gg/x4gGhjVxXz | 03.s#6260";
	Font = Enum.Font.Cartoon;
	Color = bc.Color;
	FontSize = Enum.FontSize.Size96;	
})


function Ui()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    end
    local Pl = game.PlaceId
    if Pl == 5327880096 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/OnlineBusinessSimulator2/main/README.md"))()
    end
    if Pl == 8781849572 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/StarSimulatorBeta/main/README.md"))()
    end
    if Pl == 6904735821 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/ShoeSimulator/main/README.md"))()   
    end
    if Pl == 6953291455 or Pl == 6953291455  then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/EatingSimulator/main/README.md"))()
    end

    if Pl == 1069951594 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/FallofHellAutoWin/main/README.md"))()
    end   

    if Pl == 1962086868 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/TowerOfHell/main/README.md"))()
    end   

    if Pl == 4954752502 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/TowerOfMistery/main/README.md"))()
    end   
    if Pl == 5902977746 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03sAlt/UltimateTowerDefense/main/README.md"))()
    end 
    if Pl == 8884433153 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/CollectAllPets/main/README.md"))()
    end 
    if Pl == 4003872968 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/GiantSurvival/main/README.md"))()
    end 
    if Pl == 189707 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/NaturalDisasterSurvival/main/README.md"))()
    end 
    if Pl == 3101667897 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/LegendsOfSpeedOP/main/README.md"))()
    end 
    if Pl == 5326405001 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/BaseBattles/main/README.md"))()
    end

    if Pl == 9280120396 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03sAlt/PetAdventureSimulator/main/README.md"))()
    end

    if Pl == 3851622790 then
        loadstring(game:HttpGet("https://pastebin.com/raw/RneGAhg1"))()
    end

    if Pl == 9123917180 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/TeleporterSimulator/main/README.md"))()
    end

    if Pl == 6284583030 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/PetSimulatorx/main/PetSimulatorXBobux"))()
    end

    if Pl == 734159876 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/SharkBite/main/BabyShark"))()
    end

    if Pl == 4580204640 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/SurviveTheKillerVip/main/README.md"))()
    end
