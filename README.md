# FileProcessor Task:
This is a task to make a FileProcessor using factory pattern in C# .Net core.

# Design Pattern:
A design pattern is general solution to a problem following some pattern. It is not a specific piect of code, but rather a template used to solve a particular problem. Making code more efficient and maintainable.

# Factory Pattern:
Factory Pattern is a design pattern used in Software Development to create object. Instead of instantiating objects directly using a constructor,the Factory Pattern provides an interface for creating objects in a super class, but allows subclasses to alter the type of objects that will be created. Factory pattern have some item as follows:
1. Model Class
2. Concrete Class
3. Interface
4. Factory Class
5. Controller

# Making an .NET Core File Processing From Directory:

# Step: 1
Make a Model class in which (FileName,WordCount,LineCount,Summary) properties will be made.
# Step: 2
Define an interface for processing text files.
# Step: 3
Create a concrete implementation of the file processor.
# Step: 4
Create a factory to generate file processors. This allows for scalability if you have different types of file processors in the future.
# Step: 5
Create a controller to handle file processing requests.
# Step: 6
Run the application

.rar file attached in the repository
