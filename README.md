Question :1
====================
Imagine you’re working at an ice cream parlor that serves multiple types of ice creams, such as Vanilla, Chocolate, and Strawberry. Each type of ice cream has a unique recipe, but they all share a similar preparation process. 
The parlor wants to add more flavors in the future, so they need a system that allows new flavors to be incorporated easily without modifying the existing codebase.
How would you implement this scenario using the Factory Design Pattern in C#? Design a solution that allows the ice cream parlor to create different types of ice cream based on customer requests.

Question: 2 
=================
Implement a Generic Stack class that can store elements of any data type. The stack should support the Push, Pop ,Peek, Count, IsEmpty operations and ensure proper error handling: 
Key Considerations:
•	The stack should be generic and able to store elements of any type.
•	For example, when trying to pop or peek from an empty stack, an appropriate exception should be thrown (e.g., InvalidOperationException).
•	Dynamic Resizing: The internal storage should dynamically resize if the stack grows too large. For example, you could double the size of the array when the stack is full.

Question: 3 
=================
You have a collection of Student objects , each student has the following properties Id, Name, Age , GPA , Courses You also have a separate list of Course objects, each containing Name, Credits
Find the Student with the Highest GPA , Sort Students by Age, Calculate the Average GPA

Question: 4
=================
You have two asynchronous methods FetchDataFromAPI1() and FetchDataFromAPI2(). Both methods return Task<string>. 
Write an example of how you would run both methods concurrently and wait for both to complete, using await.Write a scenario where you would use Task.WhenAll() Task.WhenAny()

Question: 5
=================
Write a C# program that boxes different types of value types (e.g., int, double, char) into an object and then unboxes them back to their original types. Demonstrate any necessary casting.
