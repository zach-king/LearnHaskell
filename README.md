# LearnHaskell
This repo was created for documenting and organizing my progression 
as I learned Haskell. I am learning Haskell via the book "Learn You 
a Haskell for Great Good" by Miran Lipovaca. Keep in mind that much 
of the code in this repo is originally from that book, and I do not 
take ownership or responsibility for any of it. I simply like to 
write and test each example myself as it helps with the learning process.

Now then, below here are some notes of mine

Functions:
-----------------
succ x: returns the successor to x (x+1 for numbers)

succ 0 => 1

min x y: returns the smaller of x and y

min 4 5 => 4

max x y: returns the larger of x and y

max 4 5 => 5

head <list>: returns the head of <list>

head [4,3,2] => 4

last <list>: returns the last element  of <list>

last [4,3,2] => 2

init <list>: returns all but the last element 

init [1,2,3,4] => [1,2,3]

tail <list>: returns all but the head element

tail [0,1,2,3] => [1,2,3]

length <list>: returns length of the <list>

length [1,2,3] => 3

null <list>: checks if <list> is empty

null [] => True

null [1,2,3] => False

reverse <list>: returns the reverse of <list>

reverse [1,2,3] => [3,2,1]

take <int> <list>: extracts the specified number of elements from the beginning
of the list.

take 2 [1,2,3,4] => [1,2]

drop <int> <list>: drops <int> number of elements from the beginning of <list>

drop 2 [-1,0,1,2,3] => [1,2,3]

maximum <list>: returns the maximum element in <list>

minimum <list>: returns the minimum element in <list>

sum <list>: returns the sum of <list> of numbers

product <list>: returns the product of <list> of numbers

elem <item> <list>: returns whether or not <item> is in <list>

4 `elem` [1,2,3,4] => True






Operations:
-----------------
[1,2,3] ++ [4,5,6] --> List concatenation (operands must be same type)

0:[1,2,3,4,5] --> Cons operator. Inserts item at head

"My num is 7" !! 10 --> Access List items with !! (indices start at 0)

[3,2,1] > [2,1,0] --> List comparisons (this one is true because 3 > 2)


[1..10] => [1,2,3,4,5,6,7,8,9,10]

['a'..'z'] => "abcdefghijklmnopqrstuvwxyz"

[2,4..20] => [2,4,6,8,10,12,14,16,18,20]

[5,4..1] => [5,4,3,2,1]

take 5 [2,4..] => [2,4,6,8,10]

take 10 (cycle [1,2,3]) => [1,2,3,1,2,3,1,2,3,1]

take 10 (repeat 1) => [1,1,1,1,1,1,1,1,1,1]
