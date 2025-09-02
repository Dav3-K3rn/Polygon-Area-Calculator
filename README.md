# Polygon-Area-Calculator
# Rectangle and Square Classes in Python

This project implements two Python classes, **Rectangle** and **Square**, that demonstrate object-oriented programming concepts such as inheritance, method overriding, and encapsulation. The classes provide useful geometric methods such as calculating area, perimeter, diagonal length, ASCII drawing, and containment checks.

---

## 📌 Features

### `Rectangle`
- Initialize with a `width` and `height`.
- Methods:
  - `set_width(width)` → Update rectangle width.
  - `set_height(height)` → Update rectangle height.
  - `get_area()` → Returns the area.
  - `get_perimeter()` → Returns the perimeter.
  - `get_diagonal()` → Returns the diagonal length.
  - `get_picture()` → Returns an ASCII art representation (limited to 50×50).
  - `get_amount_inside(shape)` → Returns how many times another shape can fit inside the rectangle.
- String representation:  
  ```python
  Rectangle(width=10, height=5)
