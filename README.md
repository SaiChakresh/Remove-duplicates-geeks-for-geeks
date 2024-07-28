# Remove-duplicates-geeks-for-geeks
Given a string str without spaces, the task is to remove all duplicate characters from it, keeping only the first occurrence.
Here the string is given which you have to return without any repetitions 

ex:

given string is : occurance

you have to return :ocurane

you have to return the string without any duplications by keeping the first occurance

This can be solved with a time complexity of O(n)

Solution:

First convert the given string to list using list(str)

Then create a new list which contains the solution 

For every element in the first list check weather the new list contains the element 

If not add the element to the new list 

After checking all the elements then return the new list by using the join() function

like return ''.join(new_list)
