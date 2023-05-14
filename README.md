# CS201-HW5
Sabanci University CS201 course homework 5

In this assignment, you will develop a library management program to handle a collection of
books. The main functionalities include adding books to the library, searching for a book by
author, searching for a book by title and displaying the books sorted by the author's last name.
If multiple books have the same author, they will be sorted by their titles. You will implement
the insertion sort algorithm to sort the books, the binary search algorithm to search for a book
by the author, and the linear search algorithm to search by title. This project aims to provide
practice working with structs and vectors. You can utilize the algorithms provided in your
lectures to complete this task.

If the user chooses to add a book, the program should prompt for the book's title, author, and
publication year. After the user enters the details, the program should add the book to the
library and re-sort the library.

If the user chooses to search for a book by an author, the program should prompt for the
author's full name. The search should be based on the author's last name and be
case-insensitive. If any books are found by the specified author, the program should display the
details of each book, including its title, author, publication year and position. If no books are
found by the specified author, the program should display an appropriate message.

If the user chooses to search for a book by title, the program should prompt for the book's title.
The search should be case-insensitive and based on the provided title. If any books with the
specified title are found, the program should display the details of each book, including its title,
author, publication year, and position in the sorted list. If no books are found with the specified
title, the program should display an appropriate message.

If the user chooses to display books, the program should display the entire library sorted by the
author's last name as case-insensitive. The output should include the book's title, author, and
publication year.

If the user chooses to quit, the program should display a farewell message and terminate.
Your program should continuously display the menu and prompt for input until the user chooses
to quit.

Assume every input is in correct format!!


