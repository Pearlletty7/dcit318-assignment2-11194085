# dcit318-assignment2-11194085

I created three C# console applications to learn object-oriented programming concepts. Each application taught me different ways classes can work together and share behavior.

For the first application, I built an inheritance system with animals. I made a base Animal class that makes a generic sound, then created Dog and Cat classes that inherit from Animal but override the sound method. When I run the program, the dog barks and the cat meows, showing how child classes can change their parent's behavior.

In the second application, I worked with abstract classes and shapes. I created an abstract Shape class that forces any shape to have an area calculation method. Then I made Circle and Rectangle classes that each calculate their area differently. The circle uses the π formula while the rectangle multiplies length and width. This taught me how abstract classes can enforce rules that all child classes must follow.

For the third application, I implemented interfaces with moving objects. I created an IMovable interface that requires a Move method, then made Car and Bicycle classes that both implement this interface. Each class moves differently - the car prints "Car is moving" and the bicycle prints "Bicycle is moving". This showed me how different classes can share the same contract but implement it in their own way.

Through these applications, I learned how inheritance, abstract classes, and interfaces help organize code and make it more flexible. Each concept solves different problems in object-oriented programming.