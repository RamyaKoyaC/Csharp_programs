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
# Prime Number

```
using System;
namespace now 
{
	
public class Program
{
	
public static bool prime(int m)
{
   for (int i=2;i<m;i++)
   {
        if (m%i==0)
        {
        return false ;
        }
   }
return true;
}

public static void Main()
  {
   Console.WriteLine(prime(6));
   Console.ReadLine();
  }
}
}

```
# Fibonacci Series

```
using System;
namespace test
{
public static void fibo(int m)
{
 int a=0, b=1,c=0;
 Console.WriteLine("{0} {0}",a,b);
 for(int i=2; i<m; i++)
 {
 c=a+b;
 Console.WriteLine(c);
 b=c;
 a=b;
 }
 
 public static void Main()
 {
   fibo(5);
 }
 ```
