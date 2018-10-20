# ShellSort
A beginner's guide to shell sort

This is ONE of a series made to be helpful to newbs in the Data struuctures and algorithms, to help them grasp the algorithms and its intuitions, i hope you find it helpful, if you want any more clarification or an algorithm to be broken down by me in this style just send a mail, thanks a lot for checking this.

- This algorithm is basically a modified insertion sort (explanation of it is here https://github.com/YouseefNoaman/InsertionSort),
  instead of just doing an insertion sort, this algorithm runs 2 consecutive insertion sorts, the first one compares the values at 
  every gap (in this implementation gap = array length / 2), then the second one runs the normal insertion sort.
- O(n^2), because an element is selected and being compared to the whole array, but it could hugely differ based on the gap.
- Unstable algorithm, as the order of the duplicate numbers will not be reserved
- in-place algorithm, no extra memory is needed.
