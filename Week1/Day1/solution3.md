### Problem 3:
```python
Integer funn(Integer a, Integer b)
    if(a && b && a+b > 0)
        return a + funn(a-2,b-2)+b
    End if
    return a^b
End function funn()
```
### Approach:
---
This function keeps subtracting 2 from both numbers and adds them up until one becomes zero, then returns their XOR as the final result.
### solution:
---
40
---
