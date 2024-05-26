
lst = ['ali', 15, True, 8.5, 'reza']
print(lst)
['ali', 15, True, 8.5, 'reza']
a = list(lst)

a.pop(3)
del(a[0])
a.remove('reza')

print(a)
[15, True]
b = list(lst)

b.append(20)
b.insert(0 , 'mamad')
b = b + [83.5]

print(b)
['mamad', 'ali', 15, True, 8.5, 'reza', 20, 83.5]
c = list(lst)

d = ['shahrooz', False]
c.extend(d)

print(c)
['ali', 15, True, 8.5, 'reza', 'shahrooz', False]
testlist = [0,1,2,3,4,5,6,7,8,9]
print(f'even numbers :           {testlist[ : :2]}')
print(f'odd numbers :            {testlist[1: :2]}')
print(f'numbers between 2 & 7 :  {testlist[3:7  ]}')
