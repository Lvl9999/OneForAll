# One For All Farmer

Most OP script ever (I generate 3 dekus per day on average).

# How to farm:
1. Put this script in the "Autoexe" folder.

```lua
getgenv().Start = true -- true/false  | (true = start),(false = stop)
getgenv().FastVersion = true -- For good executors with fast loading like krnl
getgenv().NotifyWebHook = "WebHookUrl" -- If you want to be notified everytime you get a OFA (Optional)

if getgenv().Start == true then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Lvl9999/OneForAll/main/SakuraStand"))();
end
```

# How to fuse:

1. Set up a program called MultiBlox (Download: https://robloxscripts.com/multibox-uwp-instance-manager-free-tool/ )
2. Add your ALT account (Must be 2 months old to play Sakura Stand) (you can use Pulsive's alt gen: https://discord.gg/GDN6ua59 (Their Discord)
3. Get that ALT to mastery 3 (Using my OP hub: https://github.com/Lvl9999/Flames )
4. Join both your main and alt to a public/vip

5.
```lua
getgenv().StartFusing = true -- true/false  | (true = start),(false = stop)

getgenv().MainAccount = "InsertHereTheNameOfMain" -- The Account that will used to fuse the stages to the "Holder Account" and will recieve it back.
getgenv().HolderAccount = "InsertHereTheNameOfAlt" -- The Account that will be used to be used to passed down and then give back the stages to "Main Account".

```
6. Run the script and youre done 🎖️
