# How to delete all the occurence of a string or int in a list

To delete all the occurences use the following code:

```
old_list = [1,2,3,4,2,3,4,5]
new_list = list(filter(lambda e : e != 2 , old_list))
print(new_list)
[1,3,4,3,4,5]
```
