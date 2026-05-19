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

            int nota;

            do
            {
                Console.WriteLine("Introduzca la Nota de Examen: ");

                nota = int.Parse(Console.ReadLine());
                if (nota > 0 && nota <= 10)
                {
                    Console.WriteLine("La nota "+nota+" es valida");
                }
                else
                { 
                Console.WriteLine("Error, "+nota+" no es valido ");
                }
            } while (nota < 1 || nota > 10);

        }
    }
}

// 3)
