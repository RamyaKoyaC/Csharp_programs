# Csharp_programs
All the basic programs of C#
#Function for even or odd in C#
```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace EvenOrOdd
{
    class EoO
    {
        public string EvenorOdd (int i)
        {
            
            
            if (i % 2 == 0)
                return ("even");
            else
                return ("odd"); 


        }
        static void Main(string[] args)
        {
            int a = 12; 
            
            EoO num = new EoO();
            string ret = num.EvenorOdd(a);
            Console.WriteLine("The number is {0}", ret);
            Console.ReadLine();
            
            


        }
    }
}
```
