# Practical 09

## **Author**: Vivek Dobariya  
**Date**: April 8, 2025  

This project contains several Python programs and classes that demonstrate object-oriented programming concepts. The files include implementations of various classes (e.g., `Taxi`, `SilverServiceTaxi`, `UnreliableCar`, etc.), as well as test scripts and a program to simulate a taxi service.

## **File Descriptions**

### **1. `My Band.code.python`**
- **Purpose**: Simulates a band with musicians and their instruments.
- **Key Features**:
  - Implements a `Band` class to manage a group of musicians.
  - The `Musician` class allows adding instruments to musicians.
  - The `Guitar` class represents musical instruments with attributes like name, year, and cost.
  - Demonstrates object composition by associating musicians with instruments and a band.
  - Includes a `main()` function to create a band, add musicians, assign instruments, and display details.

### **2. `Silver Service Taxi.code.python`**
- **Purpose**: Implements a specialized version of the `Taxi` class with additional features.
- **Key Features**:
  - Inherits from the `Taxi` class.
  - Adds a `fanciness` attribute to calculate additional fare costs.
  - Includes a `flagfall` fee that is added to the total fare.
  - Overrides methods to account for the new `fanciness` multiplier and flagfall.

### **3. `Silver Service Taxi Test.py.python`**
- **Purpose**: Tests the functionality of the `SilverServiceTaxi` class.
- **Key Features**:
  - Creates instances of `SilverServiceTaxi`.
  - Tests the fare calculation and other methods.
  - Validates the behavior of the `flagfall` and `fanciness` attributes.

### **4. `Taxi Class.code.python`**
- **Purpose**: Implements a `Taxi` class that extends the `Car` class.
- **Key Features**:
  - Includes attributes for fare calculation, such as `price_per_km` and `current_fare_distance`.
  - Methods:
    - `get_fare()`: Calculates the fare based on the distance driven.
    - `start_fare()`: Resets the fare distance for a new trip.
    - `drive()`: Drives the car for a specified distance and updates the fare distance.
  - Overrides the `__str__()` method to provide detailed information about the taxi.

### **5. `Taxi Simulator.code.python`**
- **Purpose**: A program to simulate a taxi service where users can choose taxis, drive them, and calculate fares.
- **Key Features**:
  - Includes a list of `Taxi` and `SilverServiceTaxi` objects.
  - Allows users to:
    - Choose a taxi.
    - Drive a specified distance.
    - View trip costs and the total bill.
  - Handles invalid inputs gracefully (e.g., invalid taxi choice or incorrect distance entry).
  - Demonstrates the use of inheritance and polymorphism.

### **6. `Taxi Test.code.python`**
- **Purpose**: Tests the functionality of the `Taxi` class.
- **Key Features**:
  - Creates an instance of the `Taxi` class and drives it for a specified distance.
  - Prints the details of the taxi, including the fare and distance driven.
  - Validates the `get_fare()` and `drive()` methods.

### **7. `Unreliable Car.code.python`**
- **Purpose**: Implements a specialized version of the `Car` class that simulates unreliable behavior.
- **Key Features**:
  - Inherits from the `Car` class.
  - Adds a `reliability` attribute (percentage chance of successful operation).
  - Overrides the `drive()` method to randomly determine if the car can drive the requested distance based on its reliability.

### **8. `Unreliable Car Test.code.python`**
- **Purpose**: Tests the functionality of the `UnreliableCar` class.
- **Key Features**:
  - Creates instances of `UnreliableCar` with varying reliability.
  - Tests the `drive()` method to observe how reliability affects the distance driven.
  - Demonstrates the use of randomness in simulating unreliable behavior.

## **How to Run the Programs**
1. **Band Simulation**:
   - Run `My Band.code.python` to simulate a band and display details of musicians and their instruments.

2. **Taxi Simulator**:
   - Run `Taxi Simulator.code.python` to start the taxi simulation program.
   - Follow the prompts to choose taxis, drive them, and calculate fares.

3. **Class Tests**:
   - Run the test files (e.g., `Taxi Test.code.python`, `Silver Service Taxi Test.py.python`, `Unreliable Car Test.code.python`) to validate the functionality of their respective classes.

## **Key Concepts Demonstrated**
- Object-oriented programming principles:
  - Inheritance
  - Polymorphism
  - Encapsulation
  - Composition
- Use of Python's `super()` to call parent class methods.
- Overriding methods to add or modify functionality.
- Handling user input and validating data.
- Simulating real-world behaviors (e.g., unreliable cars, taxi fares).

## **Dependencies**
- Ensure all required classes (`Car`, `Taxi`, `SilverServiceTaxi`, `UnreliableCar`, `Musician`, `Guitar`, `Band`) are in the same directory or properly imported.

## **Conclusion**
This project provides a comprehensive demonstration of object-oriented programming in Python, with practical examples of class design, inheritance, and real-world problem-solving.
