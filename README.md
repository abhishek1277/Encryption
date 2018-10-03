# Encryption

> This problem deals with a custom encryption scheme that works as follows.

### Problem Statement 
Given a string like "how are you?" and `m` * `n` grid. The characters of the string are filled into the grid row wise top to bottom. So for 3 * 5 you get:

```
h o w _ a
r e _ y o
u ? * * *
```

- In the above example `_` is shown visually where there is a space ('` `') character.
- Unfilled cells are filled with `*`'s

The encrypted string is found by starting at a top-left corner and going clockwise in a decreasing spiral till all of the cells are covered. So if corner is top-left you get "`how_ao***?ure_y`"

#### Constraints
`1 < m, n <= length of string S`

#### Sample Input
- The first line consists of a single string, `S`.
- The second line consists of two integers, `m` and `n`.

#### Sample Output
A single line printing the desired encrypted string.

### Implementation
Python implementation by [Abhishek Kumar](https://github.com/AbhishekKumar1277).

