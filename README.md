# 42 School Projects

This monorepo contains all my projects from the 42 school curriculum, organized by milestone.

## Repository Structure

```
common_core/
    ├── ms-0/
    │   └── libft/
    ├── ms-1/
    │   ├── ft_printf/
    │   └── get_next_line/
    └── ms-2/
        ├── push_swap/
        └── python_piscine/
        └── a-maze-ing/
```

## Projects Overview

### Milestone 0

#### libft
The first project at 42, libft is a custom implementation of the C standard library. It includes reimplementations of common functions such as string manipulation, memory management, and linked list operations. This library serves as a foundation for many subsequent projects.

**Key functions**: ft_strlen, ft_strdup, ft_atoi, ft_memcpy, ft_calloc, and many more.

### Milestone 1

#### ft_printf
A recreation of the printf function from the C standard library. This project teaches variadic functions, formatted output, and type handling. The implementation supports various format specifiers including %c, %s, %p, %d, %i, %u, %x, and %X.

**Skills learned**: Variadic functions, format parsing, output formatting.

#### get_next_line
A function that reads a line from a file descriptor, handling multiple file descriptors simultaneously. This project focuses on static variables, buffer management, and memory efficiency.

**Skills learned**: File I/O, static variables, memory management, buffer handling.

### Milestone 2

#### push_swap
A sorting algorithm project using two stacks and a limited set of operations. The goal is to sort a stack of integers with the minimum number of operations. This project requires developing an efficient sorting algorithm with strict constraints.

**Operations**: sa, sb, ss, pa, pb, ra, rb, rr, rra, rrb, rrr.

**Skills learned**: Algorithm optimization, sorting algorithms, complexity analysis and group project management.

#### python_piscine
A collection of Python modules from the Python piscine at 42. This monorepo contains exercises covering Python basics, object-oriented programming, data manipulation, and more.

**Skills learned**: The Python programming language, advanced OOP principle including inheritence, abstract classes and duck-typing, polymorphism and various design patterns.

#### a-maze-ing
A maze generation project with a vialsualizer using the 42 school's graphical librairy, the MiniLibX.

**Skills learned**: Maze generation algorithms, graphical programming, Python dependency management.

## Cloning the Repository

To clone this repository with all submodules:

```bash
git clone --recursive git@github.com:Gitmard/ft.git
```

If you've already cloned the repository without the `--recursive` flag:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To update all submodules to their latest commits:

```bash
./update_submodules.sh
```

Or manually:

```bash
git submodule update --remote --merge
```

## Individual Project Access

Each project is maintained as an independent repository and can be accessed separately:

- [libft](https://github.com/ardsimm/libft)
- [ft_printf](https://github.com/ardsimm/ft_printf)
- [get_next_line](https://github.com/ardsimm/get_next_line)
- [push_swap](https://github.com/ardsimm/ft_push_swap)
- [python_piscine](https://github.com/ardsimm/python_piscine_ft)
- [a-maze-ing](https://github.com/ardsimm/a-maze-ing)

## License

These projects are part of the 42 school curriculum. Please refer to individual project repositories for specific license information.

## About 42

42 is a programming school with a peer-to-peer learning methodology. Students work on projects at their own pace, learning through practice and collaboration.
