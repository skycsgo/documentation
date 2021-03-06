---
description: You can run your own code with these callbacks.
---

# Function Callback

#### `client.AddCallback`

| Parameter | Type |
| :--- | :--- |
| `CallbackDestination` | `string` |
| `CallbackFunction` | `function` |

### Return type

```text
void()
```

## Using callbacks

You can add callbacks in many different functions.  
Here is an example of a rendering callback.

```lua
local function DrawMyBox()
  render.Box(50, 50, Color.new(255, 0, 0, 100), RenderFlag.FILLED)
end

client.AddCalback("on_paint", DrawMyBox)
```

## Callback list

| Callback | Description |
| :--- | :--- |
| `on_paint` | Used for vGUISurface \(Depracated\) |
| `on_render` | Used for rendering. |
| `on_command` | Used mostly for engine functions |
| `on_command_pre_prediction` | Code in here is ran before`on_command`  |
| `on_command_post_prediction` | Code in here is ran after`on_command`  |



