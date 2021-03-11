---
description: This is a list of all global variables.
---

# Variables

| Variable | Type | Description |
| :--- | :--- | :--- |
| `GetFramerate` | `int` | Client framerate |
| `GetPing` | `int` | Client ping |
| `GetServerIP` | `string` | Connected server IP address |
| `GetLocalTime` | `string` | Client PC local time |
| `GetRealtime` | `float` | Absolute game time |
| `GetCurtime` | `float` | Current game time |
| `GetFramecount` | `int` | Absolute frame count |
| `GetFrametime` | `float` | Time spent on last client frame |
| `GetAbsoluteFrametime` | `float` | Non-paused frametime |
| `GetMaxClients` | `int` | Current maxplayers setting |
| `GetTickcount` | `int` | Simulation ticks |
| `GetIntervalPerTick` | `float` | Simulation tick interval |
| `GetScreenSize` | `Vector2D` | `Gets global screen size` |

## Usage

```lua
local realtime = globals.realtime()
```

