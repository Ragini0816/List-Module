# Custom List Module in Python (`MyList`)

This project implements a custom list class in Python called `MyList`, which behaves similarly to Python's built-in list but is built from scratch using object-oriented programming principles. It includes full support for list operations and operator overloading.

## Objective

To deepen understanding of data structures and OOP concepts by manually implementing a custom list class (`MyList`) that mimics Python’s native list functionality.

## Features

- Custom implementation of list operations:
  - `append`, `extend`, `insert`, `index`, `remove`, `pop`, `clear`, `count`, `sort`, `reverse`, `copy`
- Operator overloading:
  - `+`, `*`, `==`, `!=`, `<`, `<=`, `>`, `>=`, `[]` (getitem/setitem), `in`, `len()`
- Iterable and reversible
- Fully based on a defined `AbstractList` interface using Python's `ABC` module

## Technologies Used

- Python 3.x
- Jupyter Notebook

## How to Use

1. Clone this repository.
2. Open the `Manual_list.ipynb` notebook using Jupyter.
3. Explore how each method works by running the corresponding cells.

### Example Usage:

```python
mylist = MyList([1, 2, 3])
mylist.append(4)
print(mylist)             # Output: [1, 2, 3, 4]
print(mylist[2])          # Output: 3
mylist.remove(2)
print(len(mylist))        # Output: 3

### Project Structure :

AbstractList – defines all methods that must be implemented

MyList – implements all core list behavior with added operator overloads

Manual_list.ipynb – Jupyter notebook demonstrating all functionalities

### Author
Yegupati Ragini
