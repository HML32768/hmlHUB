# bit.band
### Summary
Bitwise 'and'
### Prototype
```lua
n = bit.band (a, b, ...)
```
### Description
This takes one or more arguments. All are converted to signed 'long long' (64-bit integers). The result is all arguments "and-ed" together bitwise.  
eg. bit.band (15, 7, 3) --> 3

### Example:
```lua
bit_0 = bit.band(value, 0x01) 
```
- `value` - first argument
- `0x0001` - hex bit mask (b00000001)
