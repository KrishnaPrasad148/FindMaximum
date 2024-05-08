# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
```
Developed By : S.Krisna Prasad
Register No : 212223230108
```

i)	# To find the maximum of marks using the list method sort.
```Python

def max_marks(lst):
    lst.sort()
    ans = lst[-1]
    return ans
print(f"The answer is {max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])}")
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(lst):
    ans = max(lst)
    return ans
print(f"The answer is {max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])}")

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(lst):
    max = lst[0]
    for i in lst:
        if(i>max):
            max = i
    return max
print(f"The answer is {max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])}")


```



## Output:
### i)
![Screenshot 2024-05-08 064507](https://github.com/KrishnaPrasad148/FindMaximum/assets/147332763/c867ad2b-56ce-4f4e-9276-4beb308e5b5e)

### ii)
![Screenshot 2024-05-08 064520](https://github.com/KrishnaPrasad148/FindMaximum/assets/147332763/8c4fa140-ab21-47cb-b476-3e581a69ff20)

### iii)
![Screenshot 2024-05-08 064538](https://github.com/KrishnaPrasad148/FindMaximum/assets/147332763/e2e54cae-0fbe-4556-8b2a-ee1200402cdb)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
