#TestList

Question (Line 94): what does this method do?
Answer: this method removes the entire element at index 5, shortening the list by 1.

Question (Line 101): what does this one do?
Answer: this method removes the value 5 from the list. shortens list by 1.

#TestIterator

Question (Line 78): what happens if you use list.remove(Integer.valueOf(77))?
Answer: the method will not work and throw a ConcurrentModificationException.

#TestPerformance

SIZE = 10, REPS = 1000000
Speed: 115ms, BUILD SUCCESSFUL in 1s

SIZE = 100, REPS = 10000000
Speed: 1sec 128ms, BUILD SUCCESSFUL in 2s

SIZE = 1000, REPS = 10000000
Speed: 4sec 913ms, BUILD SUCCESSFUL in 6s

SIZE = 10000, REPS = 10000000
Speed: 45sec 951ms, BUILD SUCCESSFUL in 47s
