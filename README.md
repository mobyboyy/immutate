<h1 align="center">Immutate</h1>
<div align="center">A Llama fork optimized for readability</div>

## UNDER CONSTRUCTION


### Sample
```
local Set = require(Immutate.Dictionary)

local newSet = Dictionary({ x = 0, y = 0 })
	:filter(function(index, value) -- call the function
		return value == "x"
	end)
	:get() -- gets the raw table allowing for seamless changes
```
