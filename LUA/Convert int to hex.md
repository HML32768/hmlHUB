# Convert int to hex

### Prototype
```lua
hex = string.format("%x", num)
```

### Example:
```lua
function convert (H, L)
  	local hex_H = string.format("%x", H)
  	local hex_L = string.format("%x", L)
  	local res = (tostring(hex_H)..tostring(hex_L))
  	return tonumber('0x' .. res)
end 
```
- `convert` - function that converts two dec bytes into a hex number (Logic Machine script)
- `H` - high byte dec
- `L` - low byte dec
- `hex_H` - high byte hex
- `hex_L` - low byte hex
- `string.format` - formats string with a given set of rules
- `"%x"` - present given integer in its hex form
- `res` - result number as a string

  
