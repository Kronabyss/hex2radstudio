# Color Picker Rectangle (RadStudio Color Code)

This is a modern, dark-themed web tool for picking and converting colors, designed for use with RadStudio's color code system.

## Features

- **BarColor and BarColorStop:**
  - Pick two colors (BarColor and BarColorStop) using color pickers, RGB, or HSL sliders.
  - The rectangle at the top displays a vertical gradient: BarColorStop at the top and bottom, BarColor in the center, simulating a progress bar.
  - Instantly see the RadStudio decimal value for each color.

- **Hex to RadStudio Decimal Converter:**
  - Enter any hex color (e.g., `#FF8800` or `#F80`) to instantly convert it to the RadStudio decimal value using the formula:
    
    ```
    Decimal value = (B × 256²) + (G × 256) + R
    ```

- **Modern UI:**
  - Built with Tailwind CSS for a responsive, accessible, and visually appealing dark interface.

## Usage

1. Open `color-picker.html` in your web browser.
2. Use the color pickers, RGB, or HSL sliders to adjust BarColor and BarColorStop.
3. The rectangle at the top will update to show a vertical gradient between your chosen colors.
4. The RadStudio decimal value for each color is shown below its controls.
5. Use the Hex to RadStudio Decimal converter at the top to quickly convert any hex color code.

## About RadStudio Color Codes

RadStudio (Delphi/C++ Builder) uses a specific formula to represent colors as decimal values:

```
Decimal value = (B × 256²) + (G × 256) + R
```

Where R, G, and B are the red, green, and blue components (0-255).

---

**Author:** Krona.dev

**License:** MIT
