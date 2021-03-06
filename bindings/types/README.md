# Types

## How to use types

Here is a small example on using type variables and functions

```lua
local ifImAlive = entitylist.GetLocalPlayer.IsAlive()
local aliveColor = Color.new(0, 255, 0, 100)
local deadColor = Color.new(255, 0, 0, 100)

render.Box(50, 50, (ifImAlive and aliveColor or deadColor ), RENDER_FILLED)
```

## Pages

{% page-ref page="c\_baseentity/" %}

{% page-ref page="playerinfo.md" %}

{% page-ref page="vector.md" %}

{% page-ref page="qangle.md" %}

{% page-ref page="color.md" %}





