## CSO2 dounai_lib

This is a Lua library made for a video game [Counter-Strike: Online 2](https://cso2.wohlnet.ru/).

## About

The main goal of this project, is to make Lua coding in CSO2 easier, faster and make your code as much as readable!

There was tons of new additional APIs, with more features and bug fixes, they will save your time a lot!

Meanwhile, this project is 100% compatible with vanilla Lua code (So the code made by Nexon and you will not get harm).

**This project is tested and working in Qingxue and Global server, support with other servers is unknown.**

## Installation

1. [Download latest release](https://github.com/dounai2333/dounai_lib/releases/latest).
2. Unpack it to your main CSO2 folder (The one with "Bin" and "Data" folder exists).
3. Open your lua project, add following code to the first line: `require("dounai-lib")`.
4. You are now good to go!

## TODO

### Admin system

This is the feature that my old project already have, but I wanna create a "better" and "more better" version.

The goal is make a 70% similar admin system in SourceMod, admin can slay, kick, or troll somebody in-game.

### More custom events

Due to limitation of cso2 Lua, we are heavily rely on event system to do most of stuff.

Which I wanna extend more events, give us more options to do everything!

Current plan:
1. `prop_health_changed`: Hook "func_breakable" `OnHealthChanged` event and fire a in-game event.
2. `counter_value`: Hook "math_counter" `OutValue` event are fire a in-game event.

## Documentation

[Wiki page](https://github.com/dounai2333/dounai_lib/wiki)

## Special Thanks

* OrgannerX: The guy who gave me the idea to start this project at all! Without him and his countless helps, this project will never exist.

* JACK: The guy who keep me having interest on CSO2, by porting couple Zombie Escape maps back in 2021-2022.
