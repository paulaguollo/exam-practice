# 42 Porto C Exam Practice 

Practice repository for 42 Porto exams C language exercises organized by difficulty level, following the real exam structure.

---

## Tech

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![42](https://img.shields.io/badge/42_Porto-000000?style=flat&logo=42&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Structure

```
exam-practice/
├── Subjects/          # Official exam PDFs (C00–C04)
└── practice/
    ├── Level 00/      # Basics — I/O, loops, argv
    ├── Level 01/      # Strings and simple algorithms
    ├── Level 02/      # Memory, bits, string manipulation
    ├── Level 03/      # Math, linked lists, base conversion
    ├── Level 04/      # Sorting, recursion, advanced lists
    └── Level 05/      # Memory, stacks, parsers
```

---

## Exercises by level

| Level | Tech | Focus | Exercises | Status |
|-------|------|-------|-----------|--------|
| **00** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Basic I/O, loops, argv | `hello` `ft_countdown` `ft_print_numbers` `aff_a` `aff_z` `only_a` `only_z` `aff_first_param` `aff_last_param` `maff_alpha` `maff_revalpha` | ✅ Done |
| **01** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Strings, char manipulation | `ft_strlen` `ft_strcpy` `ft_putstr` `ft_swap` `repeat_alpha` `ulstr` `rot_13` `rotone` `first_word` `rev_print` `fizzbuzz` `search_and_replace` | ✅ Done |
| **02** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Memory, bits, parsing | `ft_atoi` `ft_strdup` `ft_strcmp` `ft_strrev` `inter` `union` `last_word` `wdmatch` `do_op` `max` `alpha_mirror` `swap_bits` `reverse_bits` `print_bits` `is_power_of_2` | ✅ Done |
| **03** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Math, lists, base conversion | `ft_range` `ft_rrange` `ft_atoi_base` `ft_list_size` `add_prime_sum` `pgcd` `lcm` `print_hex` `epur_str` `expand_str` `hidenp` `paramsum` `str_capitalizer` `rstr_capitalizer` `tab_mult` | ✅ Done |
| **04** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Sorting, recursion, lists | `ft_split` `ft_itoa` `ft_itoa_base` `ft_list_foreach` `ft_list_remove_if` `sort_list` `sort_int_tab` `rostring` `rev_wstr` `fprime` `flood_fill` `brainfuck` `check_mate` | ✅ Done |
| **05** | ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Memory, parsers, advanced logic | `print_memory` `rpn_calc` `brackets` `cycle_detector` `biggest_pal` `options` | ✅ Done |

---

## How to compile and run

```bash
# Clone the repo
git clone https://github.com/paulaguollo/exam-practice.git

# Navigate to an exercise
cd practice/Level\ 01/1-1-rot_13

# Read the subject
cat subject.en.txt

# Compile and test
gcc -Wall -Wextra -Werror rot_13.c -o rot_13 && ./rot_13
```

> **Tip:** Each folder is prefixed with `level-difficulty` (e.g. `1-2-fizzbuzz` = Level 01, difficulty 2). The higher the second number, the less likely it is to appear in the exam — but practice all of them anyway.

---

*Made during the C bootcamp at 42 Porto · Jan–Feb 2026*
