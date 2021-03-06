---
description: Information about this namespace
---

# Client Engine

## Use cases

This namespace exposes the functions of the CS:GO client functions.

## Namespace usage

```lua
engine.function()
```

## Functions

| Function | Type | Description |
| :--- | :--- | :--- |
| `GetScreenWidth()` | `int` | Gets screen width |
| `GetScreenHeight()` | `int` | Gets screen height |
| `GetLevelName()` | `string` | Gets current level name |
| `GetLevelNameShort()` | `string` | Gets shortened current level name |
| `GetLocalPlayerIndex()` | `int` | Gets local player's entity index |
| `GetMapGroupName()` | `string` | Gets current level's group name |
| `GetPlayerForUserID(int userid)` | `int` | Gets entity index from a user id |
| `GetPlayerInfo(int entindex)` | `PlayerInfo` | Gets the player info of a player's user id |
| `GetViewAngles` | `QAngle` | Gets local view angles |
| `SetViewAngles(QAngle angle)` | `void` | Sets local view angles |
| `IsConnected()` | `bool` | Gets if the client is connected |
| `IsInGame()` | `bool` | Gets if the client is in a game |
| `IsHLTV()` | `bool` | Gets if the client is in HLTV |
| `IsPlayingDemo()` | `bool` | Gets if the client is playing a demo |
| `IsRecordingDemo()` | `bool` | Gets if the client is recording a demo |
| `IsTakingScreenshot()` | `bool` | Gets iif the client is taking a screenshot |

## Related

{% page-ref page="../bindings/types/qangle.md" %}

{% page-ref page="../bindings/types/playerinfo.md" %}

