# Reverse an Array
Define a function that accepts a list as input and outputs a reversed list

## Whiteboard Process
![Whiteboard Process]([https://github.com/Terransky/data-structures-and-algorithms/blob/main/python/array-reverse.png](https://github.com/Terransky/data-structures-and-algorithms/blob/array-reverse/python/code_challenges/array-reverse/array-reverse.png))

## Approach & Efficiency
I created a second list to store the values of the input list and instantiated it to be the same length as the input to avoid an out of range error.
I used a for loop and counter to iterate over the input backward by taking the length of the input and subtracting the counter.
I assigned the elements to the new list.

It doesn't mutate the list so it uses twice as much memory since we're not removing the input from memory. 
Time and Space is O(n) because it's a linear equation that iterates once.

## Partner
Sergii Otryshko
