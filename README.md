# libft
A custom C library re-implementing standard libc functions. This is the first C programming project from the 42 school curriculum.


Part 1: Standard `libc` Functions
A re-implementation of functions found in standard C libraries like `<string.h>`, `<stdlib.h>`, and `<ctype.h>`.

* **Memory:** `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`
* **Strings:** `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`
* **Character:** `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`
* **Conversion:** `ft_atoi`
* **Memory Allocation:** `ft_calloc`

Part 2: Additional Helper Functions
Useful functions that are not in the standard `libc` but are incredibly helpful for future projects.

* `ft_substr`: Extracts a substring from a string.
* `ft_strjoin`: Concatenates two strings into a new string.
* `ft_strtrim`: Trims characters from the beginning and end of a string.
* `ft_split`: Splits a string into an array of strings based on a delimiter.
* `ft_itoa`: Converts an integer into a string.
* `ft_strmapi`: Applies a function to each character of a string to create a new string.
* `ft_striteri`: Applies a function to each character of a string.
* `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`: Output functions that write to a specific file descriptor.

Bonus Part: Linked List Functions
A set of functions to create, manage, and manipulate chained lists.

* `ft_lstnew`: Creates a new list element.
* `ft_lstadd_front`: Adds an element to the beginning of a list.
* `ft_lstsize`: Counts the number of elements in a list.
* `ft_lstlast`: Returns the last element of a list.
* `ft_lstadd_back`: Adds an element to the end of a list.
* `ft_lstdelone`: Deletes a single element from a list.
* `ft_lstclear`: Deletes and frees all elements in a list.
* `ft_lstiter`: Applies a function to each element in a list.
* `ft_lstmap`: Creates a new list by applying a function to each element of an existing list.
