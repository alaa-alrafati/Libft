*This project has been created as part of the 42 curriculum by aalrofat.*

# 📚 libft

## 📝 Description
The **libft** project is a custom C library built from scratch to re-implement essential standard C library functions along with useful string, memory, and file-descriptor output utilities. The goal is to build a reliable foundation of core functions that can be reused across future C projects in the curriculum.

### 💡 What did I learn from the project
Re-implementing standard C functions from scratch gave me a deeper understanding of how memory, pointers, strings, and edge cases work under the hood in C. I learned how to handle memory allocation safely, avoid buffer issues, write clean and modular code following the Norminette, and build a static library (`libft.a`) using a `Makefile`.

## ⚙️ Instructions
1. `cd libft` (or navigate to the project directory)
2. `make` (compiles object files and creates `libft.a`)
3. **Useful Makefile rules**:
   - `make clean` : Removes object files (`.o`).
   - `make fclean` : Removes object files and `libft.a`.
   - `make re` : Rebuilds the library from scratch.
4. **Usage in a C project**: Include `libft.h` and link `libft.a` during compilation, for example:
   - `cc -Wall -Wextra -Werror main.c libft.a -o program`

## 🛠️ Implemented Functions
- **Character Checks & Conversions**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`
- **String Manipulation & Search**: `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`, `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`
- **Memory Management**: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
- **Conversion & File Descriptor Output**: `ft_atoi`, `ft_itoa`, `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

## 🔗 Resources
- [Linux man pages online](https://man7.org/linux/man-pages/)
- [Linux man pages (man 3)](https://man7.org/linux/man-pages/dir_section_3.html)
- [42 Norminette](https://github.com/42School/norminette)

### 🤖 AI Usage
- **Explaining Concepts**: Helped clarify edge cases and expected behavior for standard C functions and pointer arithmetic.
- **Code Organization**: Helped structure functions cleanly and keep code compliant with the Norminette.
- **Documentation**: Helped draft and refine the English in this README file.
