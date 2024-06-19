# Readme
## Radhe Krishna Turtle Graphics

This program creates a graphical representation of Radha and Krishna using the Turtle graphics library in Python. The drawing includes a moon, Radha on the right side, Krishna on the left side, and a background. The title "Radhe Krishna" is also displayed on the drawing.

### Prerequisites

- Python 3.x
- Turtle graphics library (comes standard with Python)

### Running the Program

1. **Install Python 3.x**: If you don't have Python installed, you can download and install it from the official [Python website](https://www.python.org/).

2. **Run the Script**:
   - Save the provided code into a Python file, e.g., `radhe_krishna_drawing.py`.
   - Open a terminal or command prompt.
   - Navigate to the directory where you saved the script.
   - Run the script using the following command:
     ```bash
     python radhe_krishna_drawing.py
     ```

### Code Explanation

- **Background and Screen Setup**:
  - The background color is set to a shade of blue (`#56bf58`).
  - The title of the window is set to "Radhe Krishna".
  - The screen size is configured to 650 (width) by 580 (height).

- **Turtle Setup**:
  - A turtle object `t1` is created and its speed is set to 4 (slow).
  - The turtle is initially moved to the starting position to draw the base rectangle.

- **Drawing the Base**:
  - The base rectangle is drawn and filled with color `#ff99d1`.

- **Drawing the Moon**:
  - The moon is drawn using a circle segment and filled with color `#CDEEF1`.

- **Drawing Radha**:
  - The outline and fill for Radha are created with color `#012427`.

- **Drawing Krishna**:
  - The turban, morpankh (peacock feather), right hand, bansuri (flute), left hand, and dhoti (traditional attire) of Krishna are drawn using various turtle methods.

- **Adding Text**:
  - The text "Radhe Krishna...." is written on the screen in a green color (`#00a606`).

### Customization

- **Adjust Speed**:
  - You can adjust the drawing speed by changing the `t1.speed()` parameter. The available speeds are:
    - `'fastest'`: 0
    - `'fast'`: 10
    - `'normal'`: 6
    - `'slow'`: 3
    - `'slowest'`: 1

- **Change Colors**:
  - You can change the colors of different parts of the drawing by modifying the `fillcolor` and `color` methods.

- **Modify Text**:
  - The displayed text and its properties (font, size, style) can be changed in the `t1.write()` method.

### License

This code is open for personal and educational use. Feel free to modify and distribute it as needed.

### Contact

For any questions or feedback, please contact [your_email@example.com].