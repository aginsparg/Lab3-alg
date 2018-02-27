Lab3
===========

**Test Iterator**

Running testRemove() with an iterator, the test runs in 5ms are removes
all instances of 77. With list.remove(Integer.valueOf(77)), it takes the same
5 ms but it only removes the first instance of the number 77.

As an ArrayList the tests ran in a total of 7 ms. and with a LinkedList
ran in 8 ms. Therefore it seems that in this case there would not be
much of a difference in efficiency between the ArrayList and LinkedList.


**Test List**

As an ArrayList the test ran in 14 ms and with a LinkedList ran in 
10 ms. Although this may seem insignificant, as the lengths of the lists
grow, the difference in time would also likely grow.

in testRemoveObject() the method list.remove(5) removes the value at 
the index 5 and shortens the list. list.remove(Integer.valueOf(5))
removes the first instance of the number 5 in the list and then shortens
the list. 

**Test Performance**

As the size increases, the run time for the test takes longer. The LinkedList took longer to run
than the run time of the ArrayList by a signigicant amount for the Access, but for AddRemove
LinkedList is much faster.

As the REPS gets larger the test time takes longer. Additionally, the 
difference between the run time of linkedlistaddremove and linkedlistaccess grew. 
As with the size the the linkedlistaccess took longer than arraylistaccess but the addremove for
linkedlist took shorted than that of the arraylist.  