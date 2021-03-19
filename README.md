# fibonacci-sequence #

Optimised Fibonacci sequence generating algorithm.

Standard fibonnaci algorithm, with an exponential run-time, would follow:
```
def fib(n)
  if n == 0 || n == 1
    return n
  else
    return fib(n - 1) + fib(n - 2)
  end
end
```
Optimised algorithm has a polynomial run-time with use of memoization.