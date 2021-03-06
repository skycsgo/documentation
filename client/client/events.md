---
description: 'You can register a CS:GO event using this.'
---

# Events

#### `client.RegisterEvent`

| Parameter | Type |
| :--- | :--- |
| `Event` | `string` |
| `CallbackFunction` | `function` |



### Return type

```text
void()
```

## Registering an event

Here is an example on how to register an event.

```lua
local function OnBulletImpact(thisEvent)
    local attacker = entitylist.GetFromUserID(thisEvent:GetInt("attacker"))
    
    --your magical code ✨
end

client.RegisterEvent("bullet_impact", OnBulletImpact)
```

{% hint style="info" %}
You can find all CS:GO events in [this page](https://wiki.alliedmods.net/Counter-Strike:_Global_Offensive_Events).
{% endhint %}

## Related

{% page-ref page="../../bindings/types/igameevent.md" %}





