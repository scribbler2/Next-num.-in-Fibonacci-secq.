```python
num1 = 0
num2 = 1

n = int(input("Enter the number of Fibonacci sequence you want to generate: "))

for i in range(2, n+1):
    next_num = (num1 + num2) % 10
    num1 = num2
    num2 = next_num

print("The next number in the Fibonacci sequence is", next_num)
```

    Enter the number of Fibonacci sequence you want to generate: 7
    The next number in the Fibonacci sequence is 3
    


```python

```
