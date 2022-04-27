game["Loaded"]:Wait()
local Players = game:GetService("Players")
local LP = Players["LocalPlayer"]
while not LP do
   Players["ChildAdded"]:Wait()
   LP = Players["LocalPlayer"]
end
local Char = LP["Character"]
while not Char do
   LP["CharacterAdded"]:Wait()
   Char = LP["Character"]
end

local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/Jxereas/UI-Libraries/main/notification_gui_library.lua", true))()
function noti(name)
local noti = Notification.new("Success", name, "Copied to clipboard")
noti:deleteTimeout(2)
end


local Player = game:GetService('Players').LocalPlayer

Player.Chatted:Connect(function(msg)
 if msg=="/e vegeta" or msg=="/e Vegeta" then
      noti('Vegeta')
    setclipboard("837234")
    elseif
        msg == "/e earth" or msg == "/e Earth" then
    noti('Earth')
    setclipboard("334235")
    elseif
        msg == "/e namek" or msg == "/e Namek" then
    noti('Namek')
    setclipboard("726467")
    elseif
        msg == "/e arlia" or msg == "/e Arlia" then
    noti('Arlia')
    setclipboard("482946")
    elseif
        msg == "/e acrojin" or msg == "/e Acrojin" then
    noti('Acrojin')
    setclipboard('538241')
    elseif
        msg == "/e lyra" or msg == "/e Lyra" then
    noti('Lyra')
    setclipboard('987288')
    elseif 
        msg == "/e videam" or msg == "/e Videam" then
    noti('Videam')
    setclipboard('174573')
    elseif
        msg == "/e kai" or msg == "/e Kai" then
    noti('Kai Planet')
    setclipboard('549395')
        end
end)
