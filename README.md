# Obfuscator Guide


## Get Started

### Return the code
To return a code in lua, u need a 'Return' type, u can do a 'function' inside it. Remember that u can make it more difficult by using the arg(s), like this exsample

```lua
return(function(...)
```

### Setup and Run the code medout Loadstring
**Roblox** does not Support Loadstring in LocalScript, Pepole can use this to Trace down your Script by running it in Roblox Studio. To Prevent this, u can do '**Lua Library**' like:

```lua
local v1=((getfenv)or(function(...)return(_ENV)end))();
```
