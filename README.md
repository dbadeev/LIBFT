![](https://user-images.githubusercontent.com/50623941/135349015-b3809664-fa24-4062-a7c8-b3dec73fccee.png)
# Libft
My first own library in C language.

The aim of this project is to code a C library, regrouping usual functions, that we’ll be allowed to use in all our future projects.

More details regarding that project are in  **libft.en.pdf**

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

## My Functions
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

##
##

## Usage
### Compile
-  to compile **libft.a** run:
```make ``` OR ``` make libft ```
- to delete **tmp** files after compile (only **libft.a** will be remain) run: 
```make clean```
- to delete ALL files after compile run: ``` fclean``` 
- to update the configuration, if you change any **filename.c/h**  run: ``` make``` 
- to recompile all files run: ```make re``` 


## Include
To use **Libft** in project:

- ```#include <libft.h> ```
- compile files with ```-I /libft/includes```
- compile **libft**
- link binary with ``` -L /libft -lft ```
