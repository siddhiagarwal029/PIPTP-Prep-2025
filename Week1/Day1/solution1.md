### Problem 1:

```python
def fun(w, x):
    y = 0
    if (x % w == 0) or (w % x == 0):
        y = y + 1
    else:
        y = y + 10
    return y

print(fun(40, 4))
```
### Approach:
---
Uses % operator and find if x%w is equals to 0 or w%x is equals to zero. If one of the condition true then print 1 or else print 10.

### Solution:
---
1
***
