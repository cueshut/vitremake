# Vitality UI Library

--Vitality is a konfigurativna UI librarija za Roblox

**[Open the landing page](https://cueshut.github.io/vitremake/)**

## Quick start

Load the library from the repository's raw URL:

```lua
local LIBRARY_URL = "https://raw.githubusercontent.com/cueshut/vitremake/main/vitality.lua"
local Library = loadstring(game:HttpGet(LIBRARY_URL))()

local Window = Library:Window({ Name = "Vitality" })
```

See [example.lua](example.lua) for a full showcase of the available controls.
