# LED Matrix Designer

An interactive web-based tool for designing LED matrix patterns and generating Arduino-compatible code. Perfect for creating custom displays for LED matrix projects.

## Features

- 🎨 Visual LED matrix designer with clickable pixels
- 📏 Adjustable matrix dimensions (up to 32x32)
- 🎯 Interactive drawing tools:
  - Click to toggle individual pixels
  - Click and drag to draw continuously
  - Keyboard navigation support
- 🛠️ Matrix manipulation tools:
  - Clear All
  - Fill All
  - Invert Pattern
- 🎨 Customizable active LED color
- 💻 Real-time Arduino code generation
- 📋 Copy-to-clipboard functionality
- 📝 Editable code output with live preview
- 📱 Responsive design for mobile and desktop

## Usage

1. Open the [LED Matrix Designer](https://led-matrix.nothans.com) in your web browser
2. Set your desired matrix dimensions (rows and columns)
3. Click on pixels to create your design
4. Customize the variable name for the generated code
5. Copy the generated code for use in your Arduino project

## Generated Code Format

The tool generates Arduino-compatible code in the following format:

```cpp
byte design[8][12] = {
  { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 },
  { 0, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0 },
  { 1, 1, 1, 1, 0, 0, 0, 0, 1, 1, 1, 1 },
  { 1, 1, 1, 1, 0, 0, 0, 0, 1, 1, 1, 1 },
  { 0, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0 },
  { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 },
  { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 },
  { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }
};
```

## Screenshots

| LED Matrix Designer App | Arduino UNO R4 WiFi |
|-------------|---------------------|
| ![FED Matrix Designer App](/screenshots/cheerlights_icon.png) | ![Arduino UNO R4 WiFi](/screenshots/cheerlights_icon_on_uno_r4_wifi.png) |
