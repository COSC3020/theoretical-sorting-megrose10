# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

In order to verify said claim, we must first look at the best case runtime. According to the slides/video, the best run time
for a comparison algorithm would be $O(nlogn)$, so, this run time would be incorrect. Looking further,
the binary tree for each decision including leaves of true or false must have at least a height of $n!$, so the given time 
would be incorrect. So, therefore, while the best case we may expect $O(nlogn)$, this proves the given run time
for X to be incorrect. Speaking on the physical analysis, if I had a list of let's say [1, 3, 2, 4], this would have 
theoretically 4! possibillites. We could first look if a[0] < a[1], since this is true we can try this same comparison on a[2]
then on a[3], which would all return true. This would result in us comparing 3 times, but we are not done yet, we can then compare
a[1], to the other elements and we would find a[2] is less than a[1], so they would need to swap. We are still not done, continuing this 
we would check about 5 or more times depending on the implementation which is more than the said comparison time X
claims to have. If we look at this through 4log4, this would still be more than n. While if we have a sorted list, we can check if the number
before is less than the number ahead, we would still want to verify this by checking each element. 

I used the class slides/video on reviewing the material.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
