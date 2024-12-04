# bit.band
### Summary
Bitwise 'and'
### Prototype
```lua
n = bit.band (a, b, ...)
```
### Description
This takes one or more arguments. All are converted to signed 'long long' (64-bit integers). The result is all arguments "and-ed" together bitwise.


### Example:
```lua
bit_0 = bit.band(value, 0x0001) -- b00000001
```
- `value` - first argument
- `0x0001` - hex bit mask
