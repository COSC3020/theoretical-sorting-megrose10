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
for X to be incorrect. Speaking on the physical analysis, while testing a list of 5 numbers, there are about 5! decisions that 
could come out, so natrually, each number would need to make sure it was in its right location. For a faster algotithm, 
it would still take $O(5log5)$, since it cannot just test 5 times and be done.

I used the class slides/video on reviewing the material.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
