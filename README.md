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

To verify this claim, like in the slides, you can follow the two ways the 
algorithm can go, true or false. So, while I would insert an unsorted list, I 
would also want to insert a sorted list. A sorted list may be it's worst case 
and this will tell me whether or not X is correct. Also, depending on what this 
sorts could change the outcome of the complexity. While numbers may sort fine, 
what happens if I sort letters or strings? So, depending on what you can 
sort, and depending on how it deals with sorted data would tell us if this
complexity is correct.

I used the class slides on reviewing the material.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
