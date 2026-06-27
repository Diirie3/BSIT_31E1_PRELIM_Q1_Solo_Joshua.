Why did you use inheritance?
I used inheritance because it lets one class reuse the properties and methods of another class. It also avoids repeating the same code and makes the program more organized.
Why did you use interfaces?
I used interfaces because they define what a class can do without saying how it does it. This makes the code more flexible since different classes can implement the same interface in their own way.
Can Helicopter inherit from both Vehicle and Airplane? Why or why not?
No. In C#, a class can only inherit from one parent class. Since Airplane is already a type of Vehicle, the Helicopter can inherit from either Vehicle or Airplane, but not both.
Why can Helicopter implement both IFlyable and IDriveable?
Because C# allows a class to implement multiple interfaces. A helicopter can have the abilities to fly and drive, so it can implement both IFlyable and IDriveable.
If a Submarine can both sail and dive, how would you design it?
I would create a Submarine class that inherits from Vehicle and implements two interfaces: ISailable and IDiveable. This shows that the submarine is a vehicle that can both sail on the water and dive underwater.