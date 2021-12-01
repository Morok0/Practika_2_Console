Программа 1 
using System;

namespace практика_1
{
    class Program
    {
        static void Main(string[] args)
        {
            double x = 0.0;
            double y = 0.0;
            Console.WriteLine("Введите Х:");
            double.TryParse(Console.ReadLine(), out x);
            Console.WriteLine("Введите Y:");
            double.TryParse(Console.ReadLine(), out y);
            if (x * x + y * y < 100 && x * x + y * y > 25 && y >= 0)
            {
                Console.WriteLine("Точка находится внути закрашенной области");
            }
            else if (x * x + y * y == 100 || x * x + y * y == 25 && y >= 0)
            {
                Console.WriteLine("Точка находится на границе закрашенной области");
            }
            else
            {
                Console.WriteLine("Точка находится ВНЕ закрашенной области");
            }


            Console.ReadKey();
        }
    }
}
 
Программа 2: 
using System;

namespace практика_1
{
class Program
    {
        static void Main(string[] args)
        {
            int n;
            Console.Write("введите количество дней: ");
            n = int.Parse(Console.ReadLine());
            if (n <= 31)
            {
                switch (n)
                {
                    case 1: Console.WriteLine("До конца месяца: 30"); break;
                    case 2: Console.WriteLine("До конца месяца: 29"); break;
                    case 3: Console.WriteLine("До конца месяца: 28"); break;
                    case 4: Console.WriteLine("До конца месяца: 27"); break;
                    case 5: Console.WriteLine("До конца месяца: 26"); break;
                    case 6: Console.WriteLine("До конца месяца: 25"); break;
                    case 7: Console.WriteLine("До конца месяца: 24"); break;
                    case 8: Console.WriteLine("До конца месяца: 23"); break;
                    case 9: Console.WriteLine("До конца месяца: 22"); break;
                    case 10: Console.WriteLine("До конца месяца: 21"); break;
                    case 11: Console.WriteLine("До конца месяца: 20"); break;
                    case 12: Console.WriteLine("До конца месяца: 19"); break;
                    case 13: Console.WriteLine("До конца месяца: 18"); break;
                    case 14: Console.WriteLine("До конца месяца: 17"); break;
                    case 15: Console.WriteLine("До конца месяца: 16"); break;
                    case 16: Console.WriteLine("До конца месяца: 15"); break;
                    case 17: Console.WriteLine("До конца месяца: 14"); break;
                    case 18: Console.WriteLine("До конца месяца: 13"); break;
                    case 19: Console.WriteLine("До конца месяца: 12"); break;
                    case 20: Console.WriteLine("До конца месяца: 11"); break;
                    case 21: Console.WriteLine("До конца месяца: 10"); break;
                    case 22: Console.WriteLine("До конца месяца: 9"); break;
                    case 23: Console.WriteLine("До конца месяца: 8"); break;
                    case 24: Console.WriteLine("До конца месяца: 7"); break;
                    case 25: Console.WriteLine("До конца месяца: 6"); break;
                    case 26: Console.WriteLine("До конца месяца: 5"); break;
                    case 27: Console.WriteLine("До конца месяца: 4"); break;
                    case 28: Console.WriteLine("До конца месяца: 3"); break;
                    case 29: Console.WriteLine("До конца месяца: 2"); break;
                    case 30: Console.WriteLine("До конца месяца: 1"); break;
                    case 31: Console.WriteLine("До конца месяца: 0"); break;
                    default:
                        Console.WriteLine("ВЫ ОШИБЛИСЬ"); break;
                        
                }
            }
            else
            {
                Console.WriteLine("число превышает количество дней в месяце ");
            }
            Console.ReadKey();
        }
    }
}


Программа 3: 
using System; 
using System;

namespace практика_1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Выведение чисел в определённом порядке\n\n");
            Console.WriteLine("Способ через While:\n");
            int i = 10;
            while (i <= 25)
            {
                Console.WriteLine(i + " " + (i + 0.4) );
                i++;
            }
            Console.WriteLine("\nСпособ через Do While:\n");
            int j = 10;
            do
            {
                Console.WriteLine(j + " " + (j + 0.4) );
                j++;
            } while (j <= 25);
            Console.WriteLine("\nСпособ через For:\n");
     
            for (int k = 10; k <= 25; k++)
            {
                Console.WriteLine(k + " " + (k + 0.4) );
            }


            Console.ReadKey();
        }
    }
}
 
Программа 4: 
using System;

namespace практика_1
{
    class Program
    {
        static void Main(string[] args)
        {
            for (int j = 1; j <= 5; j++)
            {
                Console.WriteLine();
                for (int i = -10; i <= 12; i++)
                    {
                    Console.Write(" " + i);
                    }
            }
           
            Console.ReadKey();
        }
    }
}

