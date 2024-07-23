local function delayedChat(message, delay)
  wait(delay)
  game:GetService("Chat"):Chat(game.Players.LocalPlayer, message)
end

-- Send the initial message
game:GetService("Chat"):Chat(game.Players.LocalPlayer, "Welcome To IP Leaker V1.21")

-- Schedule the subsequent messages
delayedChat("Please Wait While We Track " .. game.Players.LocalPlayer.Name, 3)
delayedChat("Tracking IP....", 6)
delayedChat("Successfully Tracked IP", 9)
delayedChat("Thank you for Your Cooperation. See You Later.", 12)
