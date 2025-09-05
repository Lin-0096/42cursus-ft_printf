<div align="center">
  <picture>
    <img src="https://raw.githubusercontent.com/ayogun/42-project-badges/main/badges/ftprintfm.png" alt="42 ft_printf badge">
  </picture>

  <p><a href="https://www.hive.fi/en/curriculum">Hive (42 School Network)</a> core curriculum project</p>
  <h1>ft_printf</h1>
</div>

`ft_printf` is a custom implementation of the C `printf` function as part of the 42 cursus. It supports formatted output with variadic arguments and several type specifiers.

---

## 🧩 Features & Format Specifiers

- Supports common format specifiers:
  - `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`, and `%%`
- Handles:
  - Integer and pointer formatting
  - Hexadecimal output in lowercase and uppercase
- Uses `stdarg.h` for variadic argument handling

---

## 🗂 Project Structure

```
ft_printf/
├── include/
│   └── ft_printf.h        # Function prototype and constants
├── src/
│   ├── ft_printf.c        # Entry point and format string parser
│   ├── handlers.c         # Handlers for each specifier type
│   ├── utils.c            # Helper functions (number conversion, padding)
│   └── bonus.c            # Optional or bonus features
├── Makefile               # Build rules
└── README.md              # This documentation
```

---

## ⚙️ How to Use

### 1. Compile and test `ft_printf`
```bash
cc -Wall -Wextra -Werror -I include src/ft_printf.c src/handlers.c src/utils.c -o ft_printf
```

### 2. Example usage
```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Char: %c, String: %s, Int: %d, Hex: %x\n", 'A', "Hello", 42, 255);
    return 0;
}
```

---

## 📚 Learning Outcomes

- Mastered variadic function handling via `va_list`, `va_start`, and `va_arg`
- Parsed complex format strings and applied format rules
- Recreated core functionality of C's `printf` from scratch
- Managed edge cases: null pointers, zero values, precision rules
- Structured modular code using reusable format and print utilities

---

**Developed by [Your Name]**  
[GitHub](https://github.com/Lin-0096)
