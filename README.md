# Design Principles Lab - Part 2

This repository contains Part 2 of a series focusing on the application of solid design principles in Java. It extends the foundational concepts introduced in Part 1 and explores additional design principles through various practical examples.

## Purpose

The goal of this second part is to delve deeper into the design principles by implementing more complex scenarios and demonstrating advanced techniques. This includes the Dependency Inversion Principle, Interface Segregation Principle, and practical examples of handling format exceptions and message formatting.

## Technologies and Packages Used

- **Java**: The primary language used for all examples, illustrating advanced design principles.
- **JUnit**: Used for unit testing to ensure that each class and method performs as expected.
- **Maven**: Handles project dependency management and builds processes.
- **Jackson**: For processing JSON, demonstrating real-world applications of design principles in handling data formats.

## Project Structure

- `dependency`: Contains classes like `ElectricSocketWithSwitch`, `LightBulb`, `Radio`, and `Tv`, illustrating the Dependency Inversion Principle.
- `exercise`: Features classes such as `Message`, `Formatter`, `JSONFormatter`, and `TextFormatter` to show different strategies for data formatting.
- `segregation`: Includes interfaces and classes like `Toy`, `ToyHouse`, `ToyPlane`, illustrating the Interface Segregation Principle by separating capabilities into distinct interfaces.

### Key Components:

- **Dependency Inversion Principle**: Demonstrated by the classes in the `dependency` package, which decouple high-level components from low-level components through abstractions.
- **Interface Segregation Principle**: Showcased in the `segregation` package, where interfaces are designed to be specific to the client's needs, reducing the side-effects of changes in unrelated systems.
- **Exception Handling in Formatting**: `FormatException` class and its usage in `exercise` package to handle errors in data processing securely and robustly.

## Running the Project

To run and test the implementations, please follow these steps:

1. Ensure Java and Maven are installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Execute the following command to compile and run the project:
   ```bash
   mvn clean install
