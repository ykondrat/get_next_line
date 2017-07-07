# get_next_line 

get_next_line is a function that returns a line read from a file descriptor. “line” is a succession of characters that end with ’\n’ (ascii code
0x0a) or with End Of File (EOF).

It compile like this :

```
make -C libft/ fclean && make -C libft/
```

Then :

```
clang -Wall -Wextra -Werror -I libft/includes -o get_next_line.o -c get_next_line.c
```
```
clang -Wall -Wextra -Werror -I libft/includes -o main.o -c main.c
```
```
clang -o test_gnl main.o get_next_line.o -I libft/includes -L libft/ -lft
```