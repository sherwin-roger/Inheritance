# Inheritance

## Aim:

To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:

### Step 1: 
Create a base class.

### Step 2:
Create two child class.

### Step 3: 
Create a constructor in the base class and print a message.

### Step 4: 
create a function in child class to print a message.

## Program:
```c#

using System;
namespace Hello
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("Tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car\n");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter\n");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            scooter scooter = new scooter();
            scooter.display();
        }
    }
}

```
## Output:

![img](https://user-images.githubusercontent.com/75413726/172905385-3643392f-a384-4225-82c3-7c39d1bba31f.jpg)

## Result:

Thus, a C# program to print some messages using hierarchical inheritance was developed successfully.
