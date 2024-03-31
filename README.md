# s21_containers
## Implementation of the s21_containers.h. library
### Requirements:
* The program must be developed in C++ language of C++17 standard using gcc compiler;
* The program code must be located in the src folder;
* When writing code it is necessary to follow the Google style;
* Make sure to use iterators;
* Classes must be template;
* Classes must be implemented within the s21 namespace;
* Prepare full coverage of container classes methods with unit-tests using the GTest library;
* Copying of the Standard Template Library (STL) implementation is not allowed;
* The logic of the Standard Template Library (STL) must be followed (in terms of checks, memory handling and behaviour in abnormal situations).

### Part 1. Implementation of the s21_containers.h library
List of classes: list, map, queue, set, stack, vector.
* Make it as a header file s21_containers.h which includes different header files with implementations of the specified containers (s21_list.h, s21_map.h and etc.);
* Provide a Makefile for testing the library (with targets clean, test);
* The classical implementation of containers should be considered as a basis, but the final choice of implementations remains free. Except for the list - it should be implemented via the list structure rather than the array.
### Part 2. Bonus. Implementation of the s21_containersplus.h library
List of classes to be implemented additionally: array, multiset.
* Make it as a header file s21_containersplus.h which includes different header files with implementations of the specified containers (s21_array.h, s21_multiset.h);
* Provide a Makefile for testing the library (with targets clean, test);
* The classical implementation of containers should be considered as a basis, but the final choice of the algorithm remains free.
### Part 3. Bonus. Implementation of the insert_many method
|	Modifiers	|	Definition	|	Containers	|
|------------|------------|------------|
|	iterator insert_many(const_iterator pos, Args&&... args)	|	Inserts new elements into the container directly before pos.	|	List, Vector.	|
|	void insert_many_back(Args&&... args)	|	Appends new elements to the end of the container.	|	List, Vector, Queue.	|
|	void insert_many_front(Args&&... args)	|	Appends new elements to the top of the container.	|	List, Stack.	|
|	vector<std::pair<iterator,bool>> insert_many(Args&&... args)	|	Inserts new elements into the container.	|	Map, Set, Multiset.	|

