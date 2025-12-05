```
num = 6
opposite = [0,2,4,6,8]
lastDigit = num - (num / 10) * 10

FOR j FROM 0 to 4
    IF lastDigit != opposite[j]:
        PRINT "Odd"
        BREAK

```