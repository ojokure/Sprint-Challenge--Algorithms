#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)

linear time O(n)

b)

logarithmic time O(nlog n) because n is halfed as j increases on the second loop

c)

linear time O(n) because n reduces each time the recursive call is made

## Exercise II

# deploying an approach similar to binary search, seeing as number of floors we have to go through is sorted

# n = number of floors/stories, so highest_floor = length(n)

# first_floor = 0

# mid_floor = highest floor // 2

# we assume f = mid_floor

# It wil be optimal to start throwing eggs down from the mid floor till we get to the floor of the egg's threshold

# so if we throw an egg from the mid_floor(f) and it breaks we go one step lower and throw again and if still breaks

## ? we half the number of floors from f(mid_floor) to first_floor(0) and set that to new f

# else if it does not break ? we half the number of floors from f(mid_floor) to the highest_floor and set that to

# our new f and keep halfing till and checking a floor less than f till we get to the threshold.

# runtime complexity of O(log n) worst case and best case O(1)
