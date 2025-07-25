using System;

public class Program
{
    static void Main(string [] args)
    {
		Console.WriteLine("Escolha um número de 1 a 9 para a tabuada");
		
		string n=Console.ReadLine();
		
		if (int.TryParse(n, out int x) && x>0 && x<10)
		   {
		Console.WriteLine($"Esta é a tabuada de {x}");
		for (int i=1; i<=10; i++)
		{
			Console.WriteLine($"{x} x {i} = {x*i}");
		}
		   }
		
		else 
		{
			Console.WriteLine("Tente um número entre 1 e 9");
		}
	}
}
