# ejercicio-1
using System;
 
public class Ejemplo_03_02_03a
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
        float Suma;
 
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
        Suma = primerNumero + segundoNumero;
 
        Console.WriteLine("La Suma de {0} y {1} es {2}", 
          primerNumero, segundoNumero, Suma);
    }
	 }



