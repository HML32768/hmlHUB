# Decimal to hex function

```lua
print("Decimal to hex function\n")
function decimalToHex(num)
    if num == 0 then
        return '0'
    end
    local neg = false
    if num < 0 then
        neg = true
        num = num * -1
    end
    local hexstr = "0123456789ABCDEF"
    local result = ""
    while num > 0 do
        local n = math.fmod(num, 16)    -- Returns the remainder of the division of x by y that rounds the quotient towards zero
        result = string.sub(hexstr, n + 1, n + 1) .. result
        num = math.floor(num / 16)      -- Returns the largest integer smaller than or equal to x = num/16
    end
    if neg then
        result = '-' .. result
    end
    return result
end
```

- `num` - decimal number
 
