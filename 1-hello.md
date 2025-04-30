1. Print Hello and Name

Write a C# Sharp program to print Hello and your name in a separate line.
Expected Output :
Hello: Alexandra Abramov

# Solution:
```
            Console.WriteLine("What's your name?");
            string name = Console.ReadLine();
            Console.WriteLine("Hello: " + name);
```