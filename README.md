Libft

Introduction

C programming can be challenging without access to standard functions. libft is designed to deepen understanding by reimplementing these essential functions and providing a reliable toolkit for future C projects. Expand and adapt libft throughout your studies to ensure compatibility and utility across various assignments.

Project Overview

This project involves recreating several standard C library functions as well as additional utility functions that are not found in libc. libft will serve as a handy tool for building your C projects, adhering to the coding norms and standards of your curriculum.

Features

Libc Functions: Recreate standard libc functions such as strlen, memset, and atoi.

Additional Functions: Implement supplementary utilities like ft_substr, ft_strjoin, and ft_split which extend the basic libc offerings.

Memory Management: Functions like ft_calloc and ft_strdup to manage dynamic memory allocation.

String Manipulation: Functions to modify and handle strings such as ft_strtrim and ft_strmapi.

Output Functions: Custom functions to handle output to file descriptors, including ft_putstr_fd and ft_putendl_fd.

Technical Considerations

No global variables.

Static functions are used for helper utilities.

All source files must compile with flags -Wall -Wextra -Werror.

Use ar to create the library; using libtool is forbidden.

The final library, libft.a, is situated at the root of your repository.
