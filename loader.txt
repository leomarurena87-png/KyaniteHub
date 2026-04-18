-- ts file was generated at discord.gg/25ms

function Notification()
    game.StarterGui:SetCore('SendNotification', {
        Title = 'Kyanite Hub',
        Text = 'Normal User',
        Icon = 'rbxassetid://14328445561',
        Duration = 5,
    })
end

local _ = game:GetService('MarketplaceService'):GetProductInfo(game.PlaceId).Name
local v1 = {
    'NeedMoneyForLuarmor',
    'Hentai',
    'Meow',
}
local v2, v3, v4 = pairs(v1)

local function v5()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Dont%20get%20Sniffed%20Chapter%202'))()
end
local function v6()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Family%20Paradise'))()
end
local function v7()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Kohau%20Hibachi%20Resaturant'))()
end
local function v8()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/toh'))()
end
local function v9()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Natural%20Survival'))()
end
local function v10()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/yaf'))()
end
local function v11()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Dont%20get%20Sniffed%20Chapter%201'))()
end

local v12 = 1

local function v13()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Cheese%20Escape%20Chapter%202'))()
end
local function v14()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Arm%20Wrestle%20Simulator'))()
end
local function v15()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/lb'))()
end
local function v16()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Cheese%20Escape%20Chapter%201'))()
end
local function v17()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Boxing%20Simulator%202'))()
end
local function v18()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Worm%202048'))()
end
local function v19()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/los'))()
end
local function v20()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/Rebirth%20Champions%20X'))()
end
local function v21()
    Notification()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NekoMe0w/KyaniteHub/main/Scripts/pl'))()
end

local v22 = nil

while true do
    local v23

    v4, v23 = v2(v3, v4)

    if v4 == nil then
        break
    end
    if v12 ~= #v1 then
        if v23 ~= getgenv().Key then
            v12 = v12 + 1
        else
            if not pcall(({
                [4241242833] = v6,
                [4375619868] = v7,
                [3101667897] = v19,
                [8540346411] = v20,
                [1962086868] = v8,
                [155615604] = v21,
                [189707] = v9,
                [11708967881] = v10,
                [5777099015] = v16,
                [9053673709] = v13,
                [2888719930] = v17,
                [13127800756] = v14,
                [662417684] = v15,
                [12399018110] = v18,
                [13762516482] = v5,
                [13390606647] = v11,
            })[game.PlaceId]) then
                return error('game not found', -1)
            end

            v22 = getgenv().Key
            v1 = ''
        end
    else
        game.Players.LocalPlayer:Kick('Do not try and spoof your key!')

        v1 = ''
    end
end
while true do
    if getgenv().Key ~= v22 then
        game.Players.LocalPlayer:Kick('Not a valid key!')
    end

    wait()
end
