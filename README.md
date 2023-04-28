# Haskell cheat sheet


### Collection operators

Get first element:
```haskell
head [1, 2, 3, 4, 5]
```
`> 1`

Remove first element:
```haskell
tail [1, 2, 3, 4, 5]
```
`> [2, 3, 4, 5]`

Select nth element:
```haskell
[1, 2, 3, 4, 5] !! 2
```
`> 3`


Select first n elements:
```haskell
take 3 [1, 2, 3, 4, 5]
```
`> [1, 2, 3]`


Remove the first n elements:
```haskell
take 3 [1, 2, 3, 4, 5]
```
`> [1, 2, 3]`
