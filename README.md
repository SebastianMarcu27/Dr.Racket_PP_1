I encountered issues while solving tasks 5, 6, and 7 and used AI to understand what I was doing wrong.

For task 5, I forgot to handle the case where the list had an odd number of elements, in which case the 
last heap needed to be added without being merged. Additionally, the AI helped me write an auxiliary 
function to combine the results of pairs, particularly by suggesting a loop for successive merging.

For task 6, I kept trying to structure the code similarly to task 5 once that was completed, but I kept 
getting errors in some test cases regardless of how I wrote it. I attempted to write it almost identically 
to task 5 but reversing the traversals and merges. Then, I used a shortcut to check if task 6 was exactly 
the opposite of task 5 by simply reversing the function from task 5, which produced the correct results 
for all test cases. With this information, I used AI to figure out what I was doing wrong in my manual 
implementation of that reverse (two-pass-merge-LR). ChatGPT showed me a different, more concise approach 
to what I was trying to do. This led me to create a function for reversing a list using tail recursion 
with an accumulator that builds the reversed list step by step. After reversing, the two-pass-merge-LR 
was applied to the new list, ensuring that the heaps were merged in a right-to-left order.

For task 7, I forgot to initialize the recursive loop, and AI also helped me write the line of code for 
adding and recursively applying the function to the list in case a single element remained.
