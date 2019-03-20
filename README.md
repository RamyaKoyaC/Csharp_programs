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

# Giving the input at runtime

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
            int a = int.Parse(Console.ReadLine()); 
            
            EoO num = new EoO();
            string ret = num.EvenorOdd(a);
            Console.WriteLine("The number is {0}", ret);
            Console.ReadLine();
            
            


        }
    }
}
```
# Program for Multiple of 3 and 5 and should print Three and Five instead
```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _35Test
{
    class Program
    {
        static void Main(string[] args)
        {
            for (int i = 1; i <= 250; i++)
            {

                if (i % 3 == 0 && i % 5 == 0)
                {
                    Console.WriteLine("ThreeFive");
                }

                else if (i % 5 == 0)
                {
                    Console.WriteLine("Five");
                }


                else if (i % 3 == 0)
                {


                    Console.WriteLine("Three");
                }

                else
                {



                    Console.WriteLine(i);
                }
                        
                
            }
            Console.ReadLine();

        }

        
        }
}
```
