# nano.debug

lightweight roblox debugger with anti-detection

## features

**console** — game output capture with filters

**env** — 70+ exploit function checker

**spy** — remote event/function logger

**loggers** — http, market, bindable tracking

**explorer** — instance search & player info

**player**
- walkspeed / jumppower
- noclip, fly, freecam
- cframe speed (undetected)
- silent aim + fov circle
- esp (box, name, health, distance)
- hitbox expander
- crosshair
- spoof walkspeed/jumppower
- tp to player
- lag switch
- fps unlocker

**analysis** — decompiler, ac detector, gc stats

**scripts** — favorites, quick load (iy, dex, spy)

**config** — theme editor, anti-idle, auto-rejoin

## anti-detection

- random gui names
- hidden from getchildren/findfirstchild
- kick blocking
- property spoofing for anticheat
- gethui / syn.protect_gui support

## install

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/cruckzok/nano-debug/main/nano.lua"))()
