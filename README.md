# Guia-While-Do-While-1
Guia While / Do-While #1


// 1)
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine("Enter INT number for the countdown: ");
            int numero;
            numero = int.Parse(Console.ReadLine());

            while (numero >= 0)
            {
                Console.WriteLine("Numero: " + numero);
                numero--;
            }


        }
    }
}

// 2)
