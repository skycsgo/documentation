---
description: Information about this namespace
---

# Entity List

## Use cases

This namespace exposes the functions of the CS:GO entity list.

## Namespace usage

```lua
entitylist.function()
```

## Functions

| Function | Type | Description |
| :--- | :--- | :--- |
| `GetLocalPlayer()` | `C_BasePlayer` | Get local player |
| `GetPlayerByIndex(int entindex)` | `C_BasePlayer` | Get player by index |
| `GetPlayerWeapon()` | `C_BaseCombatWeapon` | Get player's active weapon |

## Related

{% page-ref page="../bindings/types/c\_baseentity/c\_baseplayer.md" %}

{% page-ref page="../bindings/types/c\_baseentity/c\_basecombatweapon.md" %}

