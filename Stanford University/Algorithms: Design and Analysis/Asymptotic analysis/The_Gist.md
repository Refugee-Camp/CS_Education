The Gist - Question 1

```
Algorithm 1
  1: for i = 1 to n do
  2:   if A[i] == t then
  3:       Return TRUE
  4: Return FALSE
````

What is the running time of this piece of code?

```
O(n)
```

The Gist - Question 2
Given A, B (arrays of length n) and t (an integer). Does A or Bcontain t?

```
Algorithm 2
    
1:  for i = 1 to n do
2:     if A[i] == t then
3:         Return TRUE
4:  for i = 1 to n do
5:     if B[i] == t then
6:         Return TRUE
7:  Return FALSE
```

What is the running time of this piece of code?

```
O(n)
```

The Gist - Question 3
Problem: Do arrays A, B have a number in common? Given arrays A, B of length n.

```
Algorithm 3
      
1: for i = 1 to n do
2:    for j = 1 to n do
3:       if A[i] == B[j] then
4:           Return TRUE
5: Return FALSE
```

What is the running time of this piece of code?

```
O(n^2)
```
