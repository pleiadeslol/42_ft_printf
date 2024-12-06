# ft_printf - A Custom Implementation of printf

The **ft_printf** project involves recreating the C library's versatile `printf()` function. This is an essential exercise to understand variadic functions, formatting output, and building a robust, extensible codebase.

## 🚀 Features

### Mandatory Part
The `ft_printf` function supports the following conversions:

- `%c` - Prints a single character.
- `%s` - Prints a string.
- `%p` - Prints a pointer address in hexadecimal format.
- `%d` - Prints a signed decimal integer.
- `%i` - Prints a signed decimal integer.
- `%u` - Prints an unsigned decimal integer.
- `%x` - Prints a number in lowercase hexadecimal format.
- `%X` - Prints a number in uppercase hexadecimal format.
- `%%` - Prints a percent sign.

### Key Details
- **Prototype:** `int ft_printf(const char *format, ...);`
- Mimics the behavior of the standard `printf` function, excluding buffer management.
- Handles variable-length argument lists using `va_start`, `va_arg`, and `va_end`.


## 📂 Files and Structure
- **Source Files:** `ft_printf.c` and helper files for specific formatting.
- **Header File:** `ft_printf.h`
- **Makefile:** Includes rules for `all`, `clean`, `fclean`, and `re`.

## 🔧 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/pleiadeslol/42_ft_printf.git
   cd 42_ft_printf
