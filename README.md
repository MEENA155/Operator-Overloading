# Operator-Overloading

## Aim:
 To write a C# program to pass values through constructors(default and parameterized) and also overload equal operators by checking whether objects are equal using operator overloading. 
 
 ##Algorithm:
 
 
 
 ##Program:
 using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Timers;

namespace ConsoleApp4
{
    class Program
    {
        protected int pri_number = 100;
        public int value = 20;
        public string name = "Kiran";
    }
    class ChildExample : Program
    {
        public void Display()
        {
            Console.WriteLine("Inside the class values are {0},{1},{2}", value, name, pri_number);
        }
    }
    class example
    {
        public static void Main(String[] args)

        {
            ChildExample e1= new ChildExample();
            e1.Display();
        }
    }
  
}
 
 ##Output:
 
 
 ##Result:
