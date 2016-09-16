using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Collections;
namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)
        {
            Queue cola = new Queue();

            cola.Enqueue("Guatemala");
            cola.Enqueue("Honduras");
            cola.Enqueue("Canada");
            cola.Enqueue("Costa Rica");
            cola.Enqueue("Panama");
            cola.Enqueue("Argentina");
            cola.Enqueue("China");



            for (int i = 0; i < 1; i++)
            {
                Console.WriteLine("Elementos totales que se encuentran en la cola: " + cola.Count);
                Console.WriteLine("");

                Console.WriteLine("Elemento retirado de la cola: " + cola.Dequeue());
                Console.WriteLine("el proximo elemento que queda en la cola es: " + cola.Peek());
                Console.WriteLine("");
                Console.WriteLine("");
            }

            Console.WriteLine("Elementos totales que se encuentran en la cola: " + cola.Count);
            Console.ReadKey();
        }
    }
}

