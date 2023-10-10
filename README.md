![omg real beytah luigi in logo wtf download mediafire pls](https://cdn.discordapp.com/attachments/1148358428473966693/1160025483392602132/cheesyweesy.gif?ex=653328eb&is=6520b3eb&hm=5dc06f92b3dd2f2477cdb1756052624ef57c8731d3acae60b924d24b838313a8&)
# Welcome to sm64ex-coop epic modding
We will be learning about of making mario health NOTHING!??!?!?!1

# m.health = 0
```lua
-- Thiz is the classic but lazy do better
local function mario_update(m)
	m.health = 0
end

hook_event(HOOK_MARIO_UPDATE, mario_update)
```

# m.health = 0xFF
```lua
-- omg you smart def super smart you gotta be the next coop dev
local function mario_update(m)
	m.health = 0xFF
end

hook_event(HOOK_MARIO_UPDATE, mario_update)
```

# m.health = 255
```lua
-- Bro is allergic to hex codes
local function mario_update(m)
	m.health = 255
end

hook_event(HOOK_MARIO_UPDATE, mario_update)
```

# Death Actions
```lua
-- wtf
local function mario_update(m)
	set_mario_action(m, ACT_STANDING_DEATH, 0)
end

hook_event(HOOK_MARIO_UPDATE, mario_update)
```
