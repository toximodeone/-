arr = [1,2,3,4,5,6,7,8,9]
ara = [4,5,6,7,8,10,11,12,13]

c = []

for item in ara:
    if item in arr:
        c.append(item)
print(c)
