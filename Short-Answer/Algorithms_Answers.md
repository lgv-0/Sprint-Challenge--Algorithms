#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - While the math being used appears to be multiplicative, if n is 3, it will loop 3 times.

3=27=9, 18, 27
5=125=25, 50, 75, 100, 125
6=216=36, 72, 108, 144, 180, 216
7=343=49, 98, 147, 196, 245, 294, 343
8=512=64, 128, 192, 256, 320, 384, 448, 512

b) O(n log n) - problem will grow faster with larger numbers due to j's limitation with j *= 2


c) O(n) - The function will only be recursively called by the # of bunnies there are

## Exercise II

Assuming each floor is given a number (floor 1, 2, 3), and when an egg is dropped it is known what floor it is being dropped from,
if the floor it is being dropped from is less than our maximum "floor" value, then the egg should be set to a broken state.

There shouldn't need to be a need for complex algorithms as an egg being dropped should be happening as an "event" from a given position.

O(1)