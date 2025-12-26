# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the value of n.
### Step 2: 
Get the value from the user for the number of rotation.
### Step 3: 
By using append functions,add the values to end.
### Step 4: 
Using the slicing concept rotate the list.
### Step 5: 
Print the output.
## Program:
```
n = int(input("Enter number of values: "))

arr = []
for i in range(n):
    arr.append(int(input(f"Enter value {i+1}: ")))

first = arr[0]

for i in range(n - 1):
    arr[i] = arr[i + 1]

arr[n - 1] = first

print("After circulation:")
for x in arr:
    print(x, end=" ")
```
## Output:
```
Enter number of values: 5
Enter value 1: 2
Enter value 2: 4
Enter value 3: 6
Enter value 4: 8
Enter value 5: 10
After circulation:
4 6 8 10 2
```
## Result:
 Thus,the output for circulate the values N variables is executed and achieved.
