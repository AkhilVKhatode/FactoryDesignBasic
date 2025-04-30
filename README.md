# FactoryDesignBasic

# Vehicle Factory Design Pattern in Python

This repository demonstrates the **Factory Design Pattern** in Python. The Factory Design Pattern is a creational pattern used to create objects without specifying the exact class of the object that will be created. In this example, we create different types of vehicles using a factory method.

## Classes

1. **Vehicle (Abstract Class)**  
   An abstract base class that defines the structure for all vehicle classes. It contains two abstract methods: `start()` and `stop()`, which need to be implemented by any subclass.

2. **Car, Truck, Bike (Concrete Classes)**  
   These classes inherit from `Vehicle` and provide concrete implementations of the `start()` and `stop()` methods.

3. **VehicleFactory (Factory Class)**  
   A factory class with a static method `get_vehicle(vehicle_type)` that creates and returns instances of `Car`, `Truck`, or `Bike` based on the input string.

## Example Output
When you run the program, you will see the following output:
```
Car is starting...
Car is stopping...
Truck is starting...
Truck is stopping...
Bike is starting...
Bike is stopping...
```

Purpose
This example is meant to showcase how the Factory Design Pattern works in Python and how it can be used to create different objects based on input without hardcoding the instantiation of specific classes. It helps in reducing code duplication and enhancing maintainability when dealing with complex systems requiring object creation.
