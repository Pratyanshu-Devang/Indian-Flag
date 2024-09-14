# Flag Drawing with Python Turtle - README

## Overview

This Python program uses the `turtle` graphics library to draw a representation of the Indian national flag. It draws the three horizontal stripes (saffron, white, and green), the Ashoka Chakra (blue wheel) in the center, and 24 spokes in the Chakra.

## Requirements

To run this code, you need:

1. Python 3.x
2. `turtle` library (comes pre-installed with Python)

## Setup Instructions

1. Install Python 3.x if you haven’t already from [python.org](https://www.python.org/downloads/).
2. Copy the code provided into a Python file (e.g., `flag_drawing.py`).
3. Run the script using a Python interpreter.

### How to Run

- Open the terminal (or command prompt).
- Navigate to the directory where the Python file is saved.
- Run the Python file by typing:

```bash
python flag_drawing.py
```

This will open a new window, and the turtle will start drawing the flag.

## Code Explanation

1. **Turtle Initialization**: The `turtle` instance is created to draw the shapes, and the speed is set to the maximum (speed 0) for faster drawing.

2. **Flag Construction**:
   - **Orange Rectangle**: The first portion drawn is the top orange (saffron) stripe.
   - **White Stripe**: After the orange rectangle, the white section of the flag is drawn.
   - **Green Rectangle**: The green portion is drawn at the bottom of the flag.
   
3. **Ashoka Chakra**:
   - **Outer Blue Circle**: A large blue circle is drawn in the center of the white section.
   - **Inner White Circle**: A slightly smaller white circle is drawn inside the blue circle.
   - **Mini Blue Circles**: 24 small blue circles are drawn around the edge of the white circle.
   - **Small Blue Circle**: A small blue circle is drawn at the center.
   - **24 Spokes**: 24 lines (spokes) are drawn inside the Chakra, representing the spokes of the Ashoka Chakra.

4. **Display**: The `turtle.done()` function ensures that the output window stays open until it is manually closed.

## Customization

- **Speed**: You can adjust the speed of the turtle by modifying the `speed()` function.
- **Colors**: The flag colors can be changed by modifying the `t.color()` values.
  
## License

This project is open-source and can be freely modified and distributed for educational or personal use.

---

Feel free to explore the `turtle` library and customize the program further!
