B. Class Hierarchy

Superclass and Subclasses
The abstract class Vehicle is the superclass in the system. It contains common fields such as brand and year, as well as abstract methods for starting and stopping the engine. The classes Car, Motorcycle, and Truck are subclasses that extend the Vehicle class and add their own specific fields.

Overridden Methods
The methods startEngine() and stopEngine() are declared as abstract in the Vehicle class. Each subclass overrides these methods to provide its own implementation based on the vehicle type.

Access Modifiers
Access modifiers are used to control access to class members. The fields in the Vehicle class are declared as protected so they can be accessed by subclasses. The fields in the Driver class are private to ensure data encapsulation. Public methods are used to allow interaction with the objects.

C. Composition and Aggregation

Each Vehicle object has a Driver object, which represents composition. At the same time, one Driver can be associated with multiple Vehicle objects, which represents aggregation.

D. Instructions to Compile and Run

To compile all Java files, use the following command:
javac *.java

To run the program, use the following command:
java Main

SCREENSHOTS
<img width="462" height="339" alt="screen1" src="https://github.com/user-attachments/assets/c5484ebc-9ea2-4446-9abd-54e8d445ea50" />
