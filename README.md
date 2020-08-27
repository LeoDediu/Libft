# Libft
My implementation of some of the Standard C Library functions including some additional ones.

Only the following libc functions are allowed : malloc(3), free(3) and write(2).

## General

1.  Libc Functions
2.  Additional Functions
3.  Bonus Functions (List operations)

Libc functions | Additional functions | Bonus Functions
:----------- | :-----------: | :-----------: 
memset		| ft_memalloc	| ft_lstnew
bzero		| ft_memdel		| ft_lstdelone
memcpy		| ft_strnew		| ft_lstdel	
memccpy		| ft_strdel		| ft_lstadd
memmove		| ft_strclr		| ft_lstiter
memchr		| ft_striter	| ft_lstmap
memcmp		| ft_striteri	|
strlen		| ft_strmap		|
strdup		| ft_strmapi	|
strcpy		| ft_strequ		|				
strncpy		| ft_strnequ	|			
strcat		| ft_strsub		|
strlcat		| ft_strjoin	|
strchr		| ft_strtrim	|
strrchr		| ft_strsplit	|
strstr		| ft_itoa		|
strnstr		| ft_putchar	|
strcmp		| ft_putstr		|
strncmp		| ft_putendl	|
atoi		| ft_putnbr		|
isalpha		| ft_putchar_fd	| 
isdigit		| ft_putstr_fd	|
isalnum		| ft_putendl_fd	|
isascii		| ft_putnbr_fd	|
isprint		||
toupper		| |
tolower		| |

## How does it work?

The goal is to create a library called **libft.a** from the source files for later use in C projects.

	cd libft
	make

Full description of the project you can find inside the **libft.en.pdf**