# CSGO CHEAT UI CLONE

```lua
local Module = loadstring(game:HttpGet('https://raw.githubusercontent.com/3345-c-a-t-s-u-s/CSGO_UI_CLONE/main/source.c'))()

local UI = Module:NewWindow('HEHE',nil)--UDim2.new(0.100000001, 355, 0.100000001, 275)

local Tab = UI:NewTab('Example Tab')

local Section = Tab:NewSection('Example Section','left')
local Section2 = Tab:NewSection('Example Section','right')

Section2:NewLabel('<<<- Right Section')
Section:NewLabel('Example to use')

Section:NewButton('BUTTON',function()
	print('button')
end)

Section:NewSlider('SLIDER',1,100,50,function(v)
	print(v)
end)

Section:NewToggle('TOGGLE',false,function(v)
	print(v)
end)

Section:NewToggle('TOGGLE',false,function(v)
	print(v)
end)

Section:NewKeybind('KEYBIND',Enum.KeyCode.Slash,function(v)
	print(v)
end)

Section:NewDropdown('DROPDOWN',{1,2,3,4,5,6,7,8,9,10},function(v)
	print(v)
end)

Section2:NewDropdown('DROPDOWN',{1,2,3,4,5,6,7,8,9,10},function(v)
	print(v)
end)

Section2:NewDropdown('DROPDOWN',{1,2,3,4,5,6,7,8,9,10},function(v)
	print(v)
end)

Section2:NewDropdown('DROPDOWN',{1,2,3,4,5,6,7,8,9,10},function(v)
	print(v)
end)
```
