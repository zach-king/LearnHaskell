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






Operations:
-----------------
[1,2,3] ++ [4,5,6] --> List concatenation (operands must be same type)

0:[1,2,3,4,5] --> Cons operator. Inserts item at head

"My num is 7" !! 10 --> Access List items with !! (indices start at 0)

[3,2,1] > [2,1,0] --> List comparisons (this one is true because 3 > 2)

