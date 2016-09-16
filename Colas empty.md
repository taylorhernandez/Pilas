using System;
using System.Linq;
using System.Text;
using System.Collections;
namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args){
            Test2();
        }

        private void Test1()
        {
            string test1 = string.Empty;
            string test11 = test1;
        }

        private static void Test2()
        {
            string test2 = "";
            string test22 = test2;
            Console.WriteLine();
                Console.ReadKey();
           
        }
    }
}
