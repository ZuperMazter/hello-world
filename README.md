# hello-world
for fun in life print smile

d = {'Zuper': 'Hero', 'Mazter': 'Coder', 'SSJ' : 'Super Semi Junior'}

for k in d:
    print (k,'-->', d[k])

# Reduce to most simple and show potential version state
if k.startswith('Z'):
    del d[k]
    print (k,'-->', d[k])
