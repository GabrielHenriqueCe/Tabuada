using System;

public class Program
{
    static void Main(string [] args)
    {
		Console.WriteLine("Escolha um número para a tabuada");
		
		string n=Console.ReadLine();
		
		if (int.TryParse(n, out int x))
		   {
		Console.WriteLine($"Esta é a tabuada de {x}");
		for (int i=1; i<=10; i++)
		{
			Console.WriteLine($"{x} x {i} = {x*i}");
		}
		   }
		
		else 
		{
			Console.WriteLine("Tente um número");
		}
	}
}
