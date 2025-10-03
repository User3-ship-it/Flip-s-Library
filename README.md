# Flip's lib

This is basically just a simple but good UI library for roblox, this is still work in proggress and doesnt have too many elements yet but i will add more stuff soon.

## Getting started

So, first of all, put this at the top of ur script for loading the GUI lib stuff

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/User3-ship-it/Flip-s-Library/refs/heads/main/MainCode"))()
```

## Usage

Firstly, To add ur UI, do this right after the Library variable

```lua
local lib = Library:Init({
	name = "My UI library",
})
```

Make sure to add "{}" or else it wont work and it will put default options

## -Making Tabs-

this ones pretty easy, you just do this

```lua
local tab = lib:CreateTab({
	name = "Home",
})
```
to activate a tab from the code instead of needing to click it, this is what u do:

```lua
tab:Activate()
```

## -Elements-

So, to add a button its easy too, just need to do this:

```lua
local button = tab:Button({
	name = "Aimbot Toggle",
	callback = function()
		print("Button Clickid")
	end,
})
```

Theres not much elements for now, since i didnt have alot of time to finish this, but i will soon update the code to add more elements like toggles, dropdowns, etc.

## License

[MIT](https://choosealicense.com/licenses/mit/)
