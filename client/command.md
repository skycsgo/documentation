---
description: Information about this namespace
---

# Command

## Use cases

This namespace exposes the functions of CS:GO commands.

## Namespace usage

```lua
cmd.function()
```

## Functions

| Function | Type | Description |
| :--- | :--- | :--- |
| `GetSendPacket()` | `bool` | Get global send packet variable |
| `SetSendPacket(bool val)` | `void` | Set global send packet variable |
| `GetChoke()` | `int` | Get choke |
| `GetButton(Button button)` | `bool` | Get button state |
| `SetButton(Button button, bool state)` | `void` | Set button state |

## Related

{% page-ref page="../bindings/enums/button.md" %}

