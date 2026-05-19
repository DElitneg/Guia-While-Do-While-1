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

            int valor;
            int ahorro;
            ahorro = 0;

            do
            {
                Console.WriteLine("El programa se detendra al insertar 0 ");
                Console.WriteLine("Introduzca el valor a sumar: ");
                valor = int.Parse(Console.ReadLine());
                ahorro += valor;
            } while (valor != 0);
            Console.WriteLine("El total acumulado es: " + ahorro);

        }
    }
}

// 4)
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

            int valor;
            int contador;
            int multiplicador;
            int tabla;
            tabla = 0;
            contador = 1;
            multiplicador = 1;

            Console.WriteLine("Introduzca el numero para mostrar su tabla: ");
            valor = int.Parse(Console.ReadLine());

            do
            {
                tabla = valor * multiplicador;
                Console.WriteLine(valor+"x"+multiplicador+" = "+tabla);

                multiplicador = multiplicador + 1;
                contador = contador + 1;

            } while (contador < 13);
           
        }
    }
}

// 5)
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

            String clave;
            String entrada;
            Console.WriteLine("Clave de acceso?: ");
            clave = Convert.ToString(Console.ReadLine());
            do
            {
                Console.WriteLine("Introduzca la clave de acceso: ");
                entrada = Convert.ToString(Console.ReadLine());
                if (clave == entrada)
                {
                    Console.WriteLine("Accesso permitido");
                }
                else
                {
                    Console.WriteLine("Clave no valida");
                }
            } while (clave != entrada);

        }
    }
}

// 6)
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
            int numero;
            int contador;            
            contador = 1;
            Console.WriteLine("Enter INT number for the countdown: ");            
            numero = int.Parse(Console.ReadLine());
            while (contador < numero)
            {
                if(contador%2 == 0)
                {
                    Console.WriteLine(contador);                    
                }
                contador++;                
            }

        }
    }
}

// 7)
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
            int contador;        
            int promedio;
            promedio = 0;
            contador = 1;
                    
            do
            {
                Console.WriteLine("Introduzca el numero para mostrar su tabla: ");
                nota = int.Parse(Console.ReadLine());
                promedio += nota;       
                contador = contador + 1;
            } while (contador < 6);
            int promediowd;
            promediowd = promedio / 10;
            Console.WriteLine("El promedio es de " + promedio + "/50 o ");

        }
    }
}
// sin terminar
