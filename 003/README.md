# [PE003](https://projecteuler.net/problem=3) - Largest Prime Factor

> The prime factors of 13195 are 5, 7, 13 and 29.
>
> What is the largest prime factor of the number 600851475143 ?

**Solution:** `>./q:600851475143`

## Explanation
- `q:` returns the list of prime factors of its argument.
- `/` inserts its first argument, a dyad, between all items in its second argument.
- `>.` returns the maximum of its two arguments

So, our code could be rewritten as `>. / q:600851475143`.

Put together, we get the maximum of the prime factors of 600851475143, which is the solution.
