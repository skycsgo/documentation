# Enums

## How to use enums

Here is a small example on using type variables and functions

```lua
render.Text(50, 50, Font.Tahoma12, "Hello world!", TextFlags.OUTLINE | TextFlags.CENTER_X)
```

In this example, `Font.Tahoma12` and `TextFlags.X` are enums.  
And as you can see, we've used a [**Bitwise Operator**](http://www.lua.org/manual/5.3/manual.html#3.4.2) ****in the flags.

```lua
TextFlags.OUTLINE | TextFlags.CENTER_X
```



