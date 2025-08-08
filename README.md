# Python-Week-2-Assignment
Creating a list in python
We start by initializing an empty list named my_list. 

my_list = []

Step 2: Append the elements 10, 20, 30, 40 to my_list.
We use the append() method multiple times to add each element to the list.

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

Step 3: Insert the value 15 at the second position in the list.
The second position is index 1 (since indexing starts at 0). We use the insert() method.

my_list.insert(1, 15)

Step 4: Extend my_list with another list: ``.
The extend() method adds multiple elements from another list.

my_list.extend([50, 60, 70])

Step 5: Remove the last element from my_list.
Using pop() without arguments removes the last item.

my_list.pop()

Step 6: Sort my_list in ascending order.
The sort() method sorts the list in place.

my_list.sort()

Step 7: Find and print the index of the value 30 in my_list.
The index() method returns the position of the specified value.

index_30 = my_list.index(30)
print(f"The index of value 30 in my_list is: {index_30}")
