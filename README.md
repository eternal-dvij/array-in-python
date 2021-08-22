# array-in-python
The Python language does not come with array data structure support. Instead, it has in-built list structures that are easy to use as well as provide some methods to perform operations.
Lists and Arrays are similar in Python. Where the major difference among the two is that arrays only allow items of the same data type whereas lists allow them to be different.
Since Python doesn’t support conventional Arrays, we can use lists to depict the same and try to reverse them. 

**Code goes here**
```python
i = int(input("enter the size of the array "))
a = list(map(int,input("\nEnter the numbers : ").strip().split()))[:i]  #invest yourself to explore the map,strip,split function
if len(list(a))<i:
    print("input is lesser than the size given")
elif len(list(a))>i:
    print("greater input!")

print("\nList is - ", a)
```
**Check yourself!!! What happens when you missed the indentation for last print \/**
```python
i = int(input("enter the size of the array "))
a = list(map(int,input("\nEnter the numbers : ").strip().split()))[:i]
if len(list(a))<i:
    print("input is lesser than the size given")
elif len(list(a))>i:
    print("greater input!")
 print("\nList is - ", a)
```
