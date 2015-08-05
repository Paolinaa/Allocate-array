using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _1_1_allocateArray
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] numbers =  {0, 1, 2, 3, 4, 5, 6, 7,8 ,9, 10, 11, 12,13, 14, 15, 16, 17, 18,19,20};
            for (int i = 0; i < numbers.Length ; i++)
            {
                Console.WriteLine ("numbers[{0}]={1}",i,numbers[i]*5);
            }
        }
    }
}
