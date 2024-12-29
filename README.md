# 📚 Libft  

Libft is a custom C library designed to provide a comprehensive set of utility functions that extend the capabilities of the standard C library. It includes implementations of common operations, string manipulation, memory handling, linked list management, and formatted printing. This library serves as a foundational toolset for various C projects.  

## 🛠 Features  

### Core Functions  
- **Character checks and conversions**: `ft_isalpha`, `ft_isdigit`, `ft_tolower`, etc.  
- **String manipulation**: `ft_strlen`, `ft_strjoin`, `ft_substr`, etc.  
- **Memory management**: `ft_memcpy`, `ft_memset`, `ft_calloc`, etc.  
- **File descriptors**: `ft_putchar_fd`, `ft_putstr_fd`, etc.  

### Advanced Modules  
- **Linked List Utilities**: Manage linked lists with functions like `ft_lstadd_back`, `ft_lstclear`, `ft_lstmap`.  
- **Get Next Line (GNL)**: Efficiently read lines from a file descriptor.  
- **ft_printf**: A formatted output function similar to `printf`.  

### Bonus Features  
Includes additional linked list operations and utilities to enhance functionality.  

## 🚀 Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/libft.git
   cd libft

2. Compile the library using the Makefile:  
    ```bash
    make

Here’s the content formatted properly in Markdown for a README.md file:

## 📂 Directory Structure  
    .
    ├── Makefile                # Build and cleaning rules
    ├── libft.h                 # Main header file
    ├── ft_printf/              # ft_printf implementation
    │   ├── ft_printf.h         # Header for ft_printf
    │   ├── src/                # Source files for printf
    │   └── utils/              # Utility functions for printf
    ├── Core Functions          # Source files for core utility functions
    ├── Bonus Functions         # Linked list utilities
    └── GNL                     # get_next_line implementation


## 🧩 Usage  

To use the library in your project, include `libft.h` in your source code and link the compiled `libft.a` during compilation:  
```bash
gcc -Wall -Wextra -Werror main.c -L. -lft -o my_program
