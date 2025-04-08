# Practical 08 - Kivy Code Overview

This README provides an overview of the code files created or modified during Practical 08. Each file is explained with its purpose and key features.

## **Code Files**

### **1. `box_layout_demo.py` and `box_layout.kv`**
- **Purpose**: This program demonstrates the use of Kivy's `BoxLayout` to create a simple GUI with buttons and text input.
- **Features**:
  - A text input field where users can enter their name.
  - Two buttons:
    - **Greet Button**: Displays a greeting message using the entered name.
    - **Clear Button**: Clears the text input field and resets the greeting label.
  - The layout is managed using a `BoxLayout` defined in the `.kv` file, which organizes the widgets vertically.

### **2. `squaring.py` and `squaring.kv`**
- **Purpose**: This program calculates the square of a number entered by the user and displays the result in a user-friendly GUI.
- **Features**:
  - A text input field for entering a number.
  - A button labeled "Square" that calculates the square of the entered number and displays it in a Label.
  - The output Label's text color is customized to pink for better aesthetics.
  - Widgets are arranged horizontally for a clean and compact layout.
  - An additional Label at the bottom provides instructions to the user.

### **3. `convert_miles_km.py` and `convert_miles_km.kv`**
- **Purpose**: This program converts a value in miles to kilometers and provides additional functionality for user interaction.
- **Features**:
  - A text input field where the user can enter a distance in miles.
  - A Label that dynamically displays the converted distance in kilometers.
  - Two buttons:
    - **Up Button**: Increments the value in the text input field by 1 mile.
    - **Down Button**: Decrements the value in the text input field by 1 mile.
  - Handles invalid inputs gracefully by setting the conversion output to `0.0` when the input is invalid or empty.
  - Uses a `StringProperty` to update the output Label dynamically whenever the input changes.

### **4. `dynamic_labels.py` and `dynamic_labels.kv`**
- **Purpose**: This program demonstrates how to dynamically create and display widgets (Labels) in a Kivy application.
- **Features**:
  - A Python list containing names is used as the data source.
  - For each name in the list, a Label is dynamically generated and added to the GUI.
  - The layout is managed using a `BoxLayout`, ensuring that all Labels are displayed in an organized manner.
  - Highlights the ability to create widgets programmatically in Kivy, which is useful for applications with dynamic or user-generated content.

## **Summary**
- Each program in this practical demonstrates a specific feature of the Kivy framework:
  - **`box_layout_demo.py`**: Basic layout management and event handling.
  - **`squaring.py`**: Simple calculations and customized layouts.
  - **`convert_miles_km.py`**: Real-world conversion application with dynamic updates.
  - **`dynamic_labels.py`**: Dynamic widget creation and layout management.
- Together, these programs provide a strong foundation for building interactive GUI applications using Kivy.
