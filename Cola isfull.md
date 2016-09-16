using System;
using System.Linq;
using System.Text;
using System.Collections;
namespace ConsoleApplication1
{
    class MainClass
    {
        class SalesPerson
        {
            string firstName, lastName;
            public string FirstName { get { return firstName; } set { firstName = value; } }
            public string LastName { get { return lastName; } set { lastName = value; } }

            public SalesPerson(string fName, string lName)
            {
                firstName = fName;
                lastName = lName;
            }

            public string fullNameMethod()
            {
                string x = firstName + " " + lastName;
                return x;
            }
        }

        class Program
        {
            static void Main(string[] args)
            {
                SalesPerson x = new SalesPerson("taylor", "hernandez");
                Console.WriteLine("las casillas estan llenas");
                Console.WriteLine("{0}", x.fullNameMethod());
                Console.ReadLine();
            }

        }
    }

}       
