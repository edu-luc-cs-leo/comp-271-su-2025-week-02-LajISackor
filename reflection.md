## Reflection on Realistic.java Assignment

In this assignment, I implemented the `getSmallest()` method and compared my work to Professor Leo’s solutions, including `getSmallest2()` and `getSmallest3()`. I got the main logic of identifying and removing the smallest element mostly right. My loop structure was close to Leo’s, particularly the idea of scanning for the smallest index and copying elements into a new array.

Where I missed the mark was in how I handled edge cases and return types. Leo’s `getSmallest2()` uses an `Integer` return type and handles the empty array case better by returning `null`. This was an important lesson about designing methods defensively. Additionally, his comments were clearer and more methodical, something I have to do a better job at in future assignments.

I also learned that compactness doesn’t always sacrifice clarity — `getSmallest3()` was a good example of this. Going forward, I’ll start earlier and make time to both test and review my code carefully. 

Finally, implementing `heapifyUp()` in my `MinHeap` really showed how tree-based arrays work. I now better understand how to maintain heap properties through swaps and parent-child relationships.

