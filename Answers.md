
## markdown quick reference
# headers

*emphasis*

**strong**

* list

>block quote

    code (4 spaces indent)
[links](http://wikipedia.org)

# Test Results
**Array List**

*(size/reps) = time*

100/100,000 = 2s

1,000/100,000 = 7s

10,000/100,000 = 13s

100,000/100,000 = 24s

**Linked List**

*(size/reps) = time*

100/100,000 = 2s

1,000/100,000 = 2s

10,000/100,000 = 3s

100,000/100,000 = 14s

#Questions

*(TODO also try with a LinkedList - does it make any difference?)*

* The LinkedList noticeably increases the speed of the tests.

*(TODO what happens if you use list.remove(77)?)*

* It would try to remove an item in index 77.

*(what does this method do?)*

* List.remove(5) removes the sixth element (index 5) of the list.

*(what does this one do?)*

* It removes the first instance of the given number.

*(which of the two lists performs better as the size increases?)*

* The LinkedList performs better as size increases.