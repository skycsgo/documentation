---
description: Adds a notification in the desired style.
---

# Notifications

#### `client.Notify`

| Parameter | Type |
| :--- | :--- |
| `Text` | `string` |
| `Color` | `color` |
| `Flags` | `NotifyType` |

### Return type

```text
void()
```

## Adding notification

Notifications have different types.

```lua
client.Notify("Hello!", Color.new(255, 255, 255), NotifyType.CONSOLE_ONLY)
client.Notify("Im in the top left.", Color.new(255, 255, 255), NotifyType.DEFAULT)
client.Notify("And im in your chat!", Color.new(255, 255, 255), NotifyType.CHAT)
```

## Related

{% page-ref page="../../bindings/enums/notifytype.md" %}





