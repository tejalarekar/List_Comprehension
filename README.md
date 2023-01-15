# List_Comprehension -

List comprehension is a concise way to create a new list by applying an operation to each item in an existing list (or other iterable) and collecting the results. It is a syntactic construct that consists of an expression followed by a "for" clause, and then zero or more "if" clauses. The expression is evaluated for each item in the iterable, and the resulting value is included in the new list if it meets the conditions specified in the "if" clauses.

1. An example of list comprehension:

squared_numbers = [x**2 for x in [1, 2, 3, 4]
This creates a new list squared_numbers where each element is the square of the corresponding element of the original list [1, 2, 3, 4]

2. You can also add conditional statements in the list comprehension, like this:

squared_even_numbers = [x**2 for x in [1, 2, 3, 4] if x%2==0]
This creates a new list squared_even_numbers where each element is the square of the corresponding even element of the original list [1, 2, 3, 4]

List comprehension can be more readable and efficient than using a for loop to build a new list, and it is a powerful feature of the Python language.
