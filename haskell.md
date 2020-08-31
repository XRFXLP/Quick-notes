Source: https://www.youtube.com/watch?v=02_H3LjqMr8

Single line comment:
```haskell 
-- This is a single line comment
```
Multiline comments:
```haskell
{-
  Okay, this is a 
  multi
  l
  i
  n
  e
  comment
  -}
  ```
  
 Importing:
 ```
 Import Module.SubModule
 ```
 Haskell is statically typed language, and it has following primitive datatypes:
 1. `Int` (Bounded whole number)
 2. `Integer`(Unbounded whole number)
 3. `Float`(Single precision)
 4. `Double`(upto 11 precision is supported)
 5. `Bool`
 6. `Char`
 7. `Tuple`
 8. `List [1..n]`
 
 `div` performs integral division, while `/` performs true division
 In order to use any function binary operator in infix mode: 5 `oper` 4
 
 Convert `Int` -> `Float` by using: `fromIntegral num` 
 Built-in mathematical functions: 
 `pi, exp, log, truncate,  round, ceiling, floor`  
 
 `and = &&, or == ||, not = not`
 
 List in haskell are singly linked lists, and they store values of same type.
 Concatentions: `++`: e.g. `[1] ++ [2, 3] = [1,2,3]`
 Cons: `1 : 2 : 3 : [] => [1, 2, 3]`
 length: `length [1, 2, 3] => 3`
 reverse: `reverse [1, 2, 3] => [3, 2, 1]`
 Check list is empty: `null [] => true`
 get_nth_index: `list !! n`
 `head, last, tail, init, take n, drop n, element `elem` list`
 maximum
 minimum
 sum
 product
 [2, 4..40]
 ['A','C'..'Z']
 repeat
 replicate
 cycle [1,2,3,4]
 listTimes2 = [x * 2 | x <- [1..10], x * 3 <= 50, , , , , , ,]
 zipWith (+) [1,2,3,34] [1,33,434343,343]
 filer (>5) list
 takeWhile (<=20) list
 foldl l = left
 foldr r = right
 
 
 List comprehensions:
 pow3List [3^n | n <- [1..10]]
 [[x * y | y <- [1..10]] | x <- [1..10]]
 
 fst, snd
 zip
 there is no difference betwen array of character, and string.
 ```haskell
 isOdd n
    | mod n 2 == 0 = False
    | otherwise = True
 ```
 `where`:
batAvgRating hits atBats
  | avg <= 0.200 = "T"
  | aweffwef = "dqwd"
  | dqeqwe = "qweeew
  | otherwise = "fjiwofwifwj
  where avg = diejd d/ooeu  rh
  
  if gotta have else
  ```haskell
  getClass n = case n of 
    5 -> "G"
    6 -> "PTSD"
    _ -> "FO"
   ```
   
   Modules: 
   ```
   module X (f1, f2)  where
   ..
   ..
   . <- function defintions
   ```
  
