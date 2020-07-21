#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The Big O notation value for this is O(n^3). This is because n is cubed in a loop. As n becomes bigger, the number of loops exponentially increases.

corrected: This is O(n) because the inner block increases the value of a by n^2 which simplifies n^3 to just n.



b) Because of the double loops, this is O(n^2).

corrected: The inner while loop increments the j value in a log manner. So that is O(log n) and the outter loop is O(n). Result is O(n log n)


c) This recursive function is O(n) since it recurses once in the function and decrements the n value by one each time.

## Exercise II

-drop egg until one is broken... starting on the first floor.
-if broken ++ (broken dropped egg) then stop. that floor is f.
-if broken !++ (not broken), go up one more floor and start again.

n -= 1 (one less egg to drop)

func dropped_not_broken(n):
    current_floor = 0
    broken_egg = 0

    for i in range(n):
    if currrent_floor < f:
        current_floor += 1
    elif:
        broken_egg += 1
        return current_floor

improved: using Binary Search, which has O(log n) complexity.

O(n) because of the nested for loop in the while loop.