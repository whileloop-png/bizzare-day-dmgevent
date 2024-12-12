--//variables
_g.image_color = Color3.new(255, 255, 255)
_g.sound_id_that_plays = "rbxassetid://5274463739" --7039305222 --5274463739 --8551016315 farts
_g.image_u_want_displayed = "rbxassetid://9180622665" --amogus i think
_g.pitch = 0.7
_g.volume = 10000
--//variables

local reps = game:GetService("ReplicatedStorage")
local players = game:GetService("Players")

local victim = players:FindFirstChild("enter their username here") --uhh has to be their full username too lazy to make an auto correction

if victim and victim.Character then
    local targetcharacter = victim.Character
    local humanoidinstance = targetcharacter.Humanoid
    local somenumber1 = 0
    local anothernumber = 0
    local positionvector = Vector3.new(0, 0, 0)

    if targetcharacter:FindFirstChild("Left Arm") then
        local leftarmcframe = targetcharacter["Left Arm"].CFrame + Vector3.new(0, 3, 0)
        
        reps.Damage:FireServer(humanoidinstance, leftarmcframe, somenumber1, anothernumber, positionvector, _g.image_u_want_displayed, _g.pitch, _g.image_color, _g.sound_id_that_plays, _g.pitch, _g.volume)
    end
else
    warn("target player not found or their character doesnt exist", victim)
end
