#### Exercise I
a) O(n)
Each iteration of the while loop increments a by n^2. Therefore, after n iterations a = n^2 + n^2 + ... + n^2 = n^2(1 + 1 + ... + 1) = n^2(n) = n^3 and the condition for the while loop breaks.

b) O(n * (n - 2) * (n - 4) * 9) -> O(n^3)
First loop: n
Second loop: n - 2
Third loop: n - 4
Fourth loop: 9, if n > 4


c) O(n + 1) -> O(n)
Assuming the input is a natural number or 0, the function will run n + 1 times (otherwise infite). The bunnies argument decrements from n down to 0, which covers n + 1 integers.

#### Exercise II
