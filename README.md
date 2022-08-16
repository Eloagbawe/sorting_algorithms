solution to sorting_algorithms exercises


0. Write a function that sorts an array of integers in ascending order using the [Bubble sort](https://en.wikipedia.org/wiki/Bubble_sort) algorithm

	Prototype: void bubble_sort(int *array, size_t size);
	You’re expected to print the array after each time you swap two elements
	Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:

		in the best case
		in the average case
		in the worst case

1. Write a function that sorts a doubly linked list of integers in ascending order using the [Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort) algorithm

	Prototype: void insertion_sort_list(listint_t **list);
	You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
	You’re expected to print the list after each time you swap two elements 	Write in the file 1-O, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:

		in the best case
		in the average case
		in the worst case

2. Write a function that sorts an array of integers in ascending order using the [Selection sort](https://en.wikipedia.org/wiki/Selection_sort) algorithm

	Prototype: void selection_sort(int *array, size_t size);
	You’re expected to print the array after each time you swap two elements	Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

		in the best case
		in the average case
		in the worst case

3. Write a function that sorts an array of integers in ascending order using the [Quick sort](https://en.wikipedia.org/wiki/Quicksort) algorithm

	Prototype: void quick_sort(int *array, size_t size);
	You must implement the Lomuto partition scheme.
	The pivot should always be the last element of the partition being sorted.
	You’re expected to print the array after each time you swap two elements

	Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

		in the best case
		in the average case
		in the worst case

4. Write a function that sorts an array of integers in ascending order using the [Shell sort](https://en.wikipedia.org/wiki/Shellsort) algorithm, using the Knuth sequence

	Prototype: void shell_sort(int *array, size_t size);
	You must use the following sequence of intervals (a.k.a the Knuth sequence):
	n+1 = n * 3 + 1
	1, 4, 13, 40, 121, ...
	You’re expected to print the array each time you decrease the interval

	No big O notations of the time complexity of the Shell sort (Knuth sequence) algorithm needed - as the complexity is dependent on the size of array and gap

5. Write a function that sorts a doubly linked list of integers in ascending order using the [Cocktail shaker](https://en.wikipedia.org/wiki/Cocktail_shaker_sort) sort algorithm

	Prototype: void cocktail_sort_list(listint_t **list);
	You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
	You’re expected to print the list after each time you swap two elements (See example below)
	Write in the file 101-O, the big O notations of the time complexity of the Cocktail shaker sort algorithm, with 1 notation per line:

		in the best case
		in the average case
		in the worst case


