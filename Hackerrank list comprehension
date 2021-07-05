#Main code

import itertools


i = []
j = []
k = []
glist = [i,j,k]
u = []

if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())

    while x >= 0:
        i.append(x)
        x = x - 1

    while y >= 0:
        j.append(y)
        y = y - 1

    while z >= 0:
        k.append(z)
        z = z - 1

for i in itertools.product(glist[0], glist[1], glist[2]):
    if sum(i) == n:
        continue

    if sum(i) != n:
        u.append(i)
        u.sort()

xlist = [list(i) for i in u]
print(xlist)
