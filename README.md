# jusroman.website.io

**my test python solution**

'''python
l=[]
for i in range(2000, 3201):
    if (i%7==0) and (i%5!=0):
        l.append(str(i))
print ','.join(l)

```python
def fact(x):
    if x == 0:
        return 1
    return x * fact(x - 1)
x = int(raw_input())
print fact(x)
