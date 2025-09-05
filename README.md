<div align="center">
<picture>
  <img alt="Get Next line project" src="https://github.com/ayogun/42-project-badges/blob/main/badges/ft_printfe.png" />
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

## 📚 Learning Outcomes

- Mastered variadic function handling via `va_list`, `va_start`, and `va_arg`
- Parsed complex format strings and applied format rules
- Recreated core functionality of C's `printf` from scratch
- Managed edge cases: null pointers, zero values, precision rules
- Structured modular code using reusable format and print utilities
