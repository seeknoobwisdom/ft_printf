# 🖨️ ft_printf

`ft_printf` is a custom implementation of the standard C `printf` function, built as part of the **42 curriculum**.  
It supports formatted output with various conversion specifiers and flags, handling variable argument lists with precision.

![Language](https://img.shields.io/badge/C-100%25-blue)
![Project](https://img.shields.io/badge/42-ft_printf-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧩 About

The goal of `ft_printf` is to replicate the behavior of the C standard library’s `printf()` function as closely as possible, supporting a variety of format specifiers, flags, widths, and precisions.

It requires mastering:

- Variadic functions (`stdarg.h`)
- String parsing
- Formatting output with padding, alignment, precision
- Handling different data types and conversions

---

## 🚀 Features

- ✅ Supports standard format specifiers: `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`, `%%`
- ✅ Handles flags: `-`, `0`
- ✅ Supports field width and precision
- ✅ Properly prints pointers and unsigned numbers in hex
- ✅ No memory leaks, efficient output using `write`

---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/ft_printf.git
cd ft_printf
make
