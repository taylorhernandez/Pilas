using  System;

class Class1
{
	public static void Main()
	{
		string p;
		int l;
		int i = 0;

		p = Console.ReadLine();
		l = p.Length;
		
		string[] derecho = new string[l];
		
		for (i = 0; i < l; i++)
		{
			derecho[i] = p.Substring(i, 1);
		}

		for (i = l-1; i >= 0; i--)
			Console.Write(derecho[i]);

		Console.Read();
	}
}
