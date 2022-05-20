# Insert to Middle of an Array
Define a function that accepts a list and number as arguments, determines whether the length of the list is odd or even, finds the midpoint (+1 for odd arrays), and returns a new array without using .insert() methods.

## Whiteboard Process
![Whiteboard Process]()

## Approach & Efficiency
Since we can't use python list methods, we were forced to // the list by 2 (to drop the float) and save that value as the midpoint. Then we define a function, instantiate an empty list to assign values to, and run a for loop for the input list. Then when we reach the midpoint, we use an if conditional to check if the length of the list is == to midpoint and whether it's even or odd through modulus and insert the input number at list[midpoint]. Then the loop continues as normal and returns the new, modified array.

Time and Space is O(n) because it's a linear equation that iterates once.

## Partner
Marni Hager
