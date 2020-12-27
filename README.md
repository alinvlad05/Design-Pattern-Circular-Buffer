# Design-Pattern-Circular-Buffer
 
A circular buffer makes a bounded queue when separate indices are used for inserting and removing data.

When you store an item in the circular buffer, you STORE the item at the TAIL location,and the tail advances to the next location.
When you read an item, you READ the item at the current HEAD location,and the head advances to the next position.
Two streams can store and read data from the same circular buffer AT THE SAME TIME.
