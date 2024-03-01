# TA-EXERCISE-1

Big O Notations
1. O(1)
2. O(n)
3. O(log n)
   Binary Search
4. O(n^2)
   Quicksort
5. O(n^2)
   Bubble Sort

Code Screenshots:<br>
<img src="ss code 1.jpg"><br>
<img src="ss code 2.jpg"><br>
<img src="ss code 3.jpg"><br>
Output:<br>
<img src="output code.jpg"><br>
Code Explaination:

Animal Class:
The Animal class encapsulates properties such as name and age (encapsulation), provides setters and getters method and declares an abstract method (makeSound) which makes all the sub classes to implement their own makeSound method (abstraction).

Dog, Cat Class:
The Dog and Cat class extends Animal indicates that the Dog and Cat class is a subclass of the Animal class, this means that the Dog and Cat class inherits all the non-private properties and methods of the animal class (inheritance), the Dog and Cat class also constructs a constructor for their own classes and implements the makeSound method for the their sound (abstraction). They also change the value of the initial makeSound method and each of them has different value (polymorphism).
