game["Loaded"]:wait()
repeat wait() until game.Players.LocalPlayer

local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/Jxereas/UI-Libraries/main/notification_gui_library.lua", true))()
function noti(name)
local noti = Notification.new("Success", name, "Copied to clipboard")
noti:deleteTimeout(2)
end

game.Players.LocalPlayer.Chatted:connect(function(msg)
    if  msg == "/e vegeta" or msg == "/e Vegeta" then
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
