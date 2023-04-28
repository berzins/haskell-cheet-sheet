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
`> [4, 5]`


Calculate the sum of alist of numbers:
```haskell
length [1, 2, 3, 4, 5]
```
`> 5`


Get the length of a list:
```haskell
sum [1, 2, 3, 4, 5]
```
`> 15`
```haskell
sum []
```
`> 0`


Calculate the product/multiplication of a list of numbers:
```haskell
product [1, 2, 3, 4, 5]
```
`> 120`


Append two lists:
```haskell
[1, 2, 3] ++ [4, 5] 
```
`> [1, 2, 3, 4, 5]`




Reverse list:
```haskell
reverse [1, 2, 3] + [4, 5] 
```
`> [5, 4, 3, 2, 1]`


