
# Libft
My first own library in C language.

The aim of this project is to code a C library, regrouping usual functions, that we’ll be allowed to use in all our future projects.

More details regarding that project are in  **Subject.pdf**.

# Contents

## Libc functions
### _Memory_
- ft_bzero
- ft_memset
- ft_memcpy
- ft_memccpy
- ft_memmove
- ft_memdel
- ft_memchr
- ft_memcmp
- ft_memalloc
- ft_memrealloc
- ft_memdel
### _Strings_
- ft_strlen
- ft_strdup
- ft_strcpy 
- ft_strncpy
- ft_strcat
- ft_strncat
- ft_strchr
- ft_strrchr
- ft_strstr
- ft_strnstr
- ft_strcmp
- ft_strncmp
### _Convert_
- ft_atoi
- ft_toupper
- ft_tolower
### _Check_
- ft_isalpha
- ft_isdigit
- ft_isalnum
- ft_isascii
- ft_isprint


## Additional Functions
### _Strings_
- ft_strnew
- ft_strdel
- ft_strclr
- ft_striter
- ft_striteri
- ft_strmap
- ft_strmapi
- ft_strequ
- ft_strnequ
- ft_strsub
- ft_strjoin
- ft_strtrim
- ft_strsplit
- ft_strlcat
- ### _Convert_
- ft_itoa
### _I/O_
- ft_putchar
- ft_putstr
- ft_putendl
- ft_putnbr
- ft_putchar_fd
- ft_putstr_fd
- ft_putendl_fd
- ft_putnbr_fd

## Bonus Functions
### _Lists_
- ft_lstnew
- ft_lstdelone
- ft_lstdel
- ft_lstadd
- ft_lstiter
- ft_lstmap

## Personal Functions
### _Check_
- ft_istabeolsp
### _Lists_
- ft_lst_elemcpy
 - ft_lstdup
### _Int_
 - ft_digcount_base
 - ft_powint
### _Pointers_
- ft_swap



## Usage
open a terminal and browse the Libft folder
run the Makefile using the command 'make' (this generates the library as "libft.a")
include "libft.h" header in your code and use any libft functions in your project
compile your code with the library using gcc -o myExecutable mySource.c libft.a
