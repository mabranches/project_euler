The sum of the squares of the first ten natural numbers is,

```12 + 22 + ... + 102 = 385```

The square of the sum of the first ten natural numbers is,

```(1 + 2 + ... + 10)2 = 552 = 3025```

Hence the difference between the sum of the squares of the first ten natural numbers and the square of the sum is 3025 − 385 = 2640.

Find the difference between the sum of the squares of the first one hundred natural numbers and the square of the sum.

# Benchmarks

### Ruby
```ruby
$ ruby problem_6/solution.rb
=> Solution 1
=> Result: 25164150
=> Time: 0.000031s
==============================
=> Solution 2
=> Result: 25164150
=> Time: 0.000003s
```

### Python
```python
$ python problem_6/solution.py
=> Result: 25164150
=> Time: 0.000020s
```

### C
```c
$ gcc -o p6 solutions/problem_6/solution.c utils/c/utils.c -I./utils/c
$ ./p6
=> Solution 1
=> Result: 25164150
=> Time: 0.000010s
=> Solution 2
=> Result: 25164150
=> Time: 0.000002s
```

### Go
```go
$ go run problem_6/solution.go
=> Result: 25164150
=> Time: 0.00000250s
```