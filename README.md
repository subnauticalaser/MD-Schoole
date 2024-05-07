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

and doing this with it:

```lua
-- v40 is: string.byte
v40=v1['\115\116\114\105\110\103']['\98\121\116\101'];
```


## 2: Making it more Difficult
to set up var(s), you can do this at the top or Anywhere in your code:

```lua
local v2=table.insert;
local v3=((unpack)or(table.unpack));
local v4=table.pack;
```


## Heres an 
