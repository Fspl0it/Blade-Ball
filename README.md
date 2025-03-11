## 🔹 Frostware Blade Ball 

<p align="center">
  <img src="https://s6.ezgif.com/tmp/ezgif-65e125cbe9c4c.gif" alt="Rectangle Image">
</p>

**Frostware** is a **Roblox utility cheat** for **Blade Ball** this script is **Trusted** by thousands of user's. this script is **well known** through-out the community as the **best blade ball script**

**Join server https://discord.gg/getfrost**

**Script**
```
local url = "https://raw.githubusercontent.com/Fspl0it/Blade-Ball/refs/heads/main/Game.lua"

local success, response = pcall(function()
    return game:HttpGet(url)
end)

if success and response and not response:find("404: Not Found") then
    local func, err = loadstring(response)
    if func then
        pcall(func)
    else
        warn("Failed to execute script:", err)
    end
else
    warn("Not Loaded")
end
```
