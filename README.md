# rs
Strings
---
**Find**
```python
str1.find('x')          # find 'first' location of char x and return index
str1.rfind('x')         # find first int location of char x from reverse
```

**Spllit**
```python
l = "0:start:0"
tokens = l.split(":")
print(tokens) # ['0', 'start', '0']

l= "How are you?"
tokens = l.split()
print(tokens) # ['How', 'are', 'you?']
```



List
---
create an list with 5 zeros
```python
test = [0] * 5 # [0, 0, 0, 0, 0]
```

**Append**
```python
new_list = []
new_list.append(1)
new_list.append(3)
# new_list [1, 3]
```


**Reverser**
```python
ss = [1,2,3]
ss.reverse()
print(ss) #3,2,1
```


**Join two lists**
```python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]
list3 = list1 + list2 # ['a', 'b', 'c', 1, 2, 3]
```


**Sort**
```python
a = ['Ford', 'BMW', 'Volvo']
print(a)  # ['Ford', 'BMW', 'Volvo']
a.sort()  
print(a)  # ['BMW', 'Ford', 'Volvo']  **a is sorted

#another way 
b = ['Ford', 'BMW', 'Volvo']
print(sorted(b)) # ['BMW', 'Ford', 'Volvo']
print(b)         # ['Ford', 'BMW', 'Volvo']  **b is not sorted
```



Dictionary
---
```python
d = {'key': 'value'}         # Declare dict{'key': 'value'}
d['key'] = 'value'           # Add Key and Value
{x:0 for x in {'a', 'b'}}    # {'a': 0, 'b': 0} declare through comprehension 
d['key'])                    # Access value
d.items()                    # Items as tuple list dict_items([('key', 'value')])
if 'key' in d: print("meh")  # Check if value exists
par = {}
par.setdefault(1,1)          # returns 1, makes par = { 1 : 1 }
par = {0:True, 1:False}
par.pop(0)                   # Remove key 0, Returns True, par now {1: False}
for k in d: print(k)         # Iterate through keys
```
