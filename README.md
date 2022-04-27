local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/Jxereas/UI-Libraries/main/notification_gui_library.lua", true))()

local noti = Notification.new("Success", "script", "not posted")
noti:deleteTimeout(5)
