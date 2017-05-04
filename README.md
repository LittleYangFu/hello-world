# hello-world
My First Repository！

s = set(['Adam', 'Lisa', 'Paul'])
L = ['Adam', 'Lisa', 'Bart', 'Paul']
for l in L:
    if l in s:
        s.remove(l)
    else:
        s.add(l)
print(s)
