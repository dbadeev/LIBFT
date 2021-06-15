
# Libft
My first own library in C language.

The aim of this project is to code a C library regrouping usual functions that we’ll be allowed to use in all our future projects.

More details regarding that project are in  **Subject.pdf**.

# Contents

## Libc functions
ft_memset
ft_bzero
ft_memcpy
ft_memccpy
ft_memmove
ft_memchr
ft_memcmp
ft_strlen
ft_strdup
ft_strcpy -ft_strncpy
ft_strcat
ft_strlcat
ft_strchr
ft_strrchr
ft_strstr
ft_strnstr
ft_strcmp
ft_strncmp
ft_atoi
ft_isalpha
ft_isdigit
ft_isalnum
ft_isascii
ft_isprint
ft_toupper
ft_tolower

## Additional Functions
ft_memalloc
ft_memdel
ft_strnew
ft_strdel
ft_strclr
ft_striter
ft_striteri
ft_strmap
ft_strmapi
ft_strequ
ft_strnequ
ft_strsub
ft_strjoin
ft_strtrim
ft_strsplit
ft_itoa
ft_putchar
ft_putstr
ft_putendl
ft_putnbr
ft_putchar_fd
ft_putstr_fd
ft_putendl_fd
ft_putnbr_fd

## Bonus Functions
ft_lstnew
ft_lstdelone
ft_lstdel
ft_lstadd
ft_lstiter
ft_lstmap

## Personal Functions
ft_swap
ft_strrev
ft_quicksort
ft_pow
ft_min
ft_max
ft_isspace
ft_isupper
ft_islower
ft_intlen
ft_putnbrtab
ft_word_count
ft_lstappend
ft_strshorten
ft_strcutuntil
get_next_line
ft_abs
ft_lstlen
ft_putnbr_w.c
ft_putstr_w.c
ft_swapstr.c


## How to use
open a terminal and browse the Libft folder
run the Makefile using the command 'make' (this generates the library as "libft.a")
include "libft.h" header in your code and use any libft functions in your project
compile your code with the library using gcc -o myExecutable mySource.c libft.a
