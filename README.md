# program-to-print-even-numbers-between-1-to-10
Using System;
Using System.IO;
Using System.Linq;
Using System.Collections.Generic;

Namespace CSharp_Shell
{

    Public class Program 
    {
        Public static void Main()
        {
			Int I;
			For(i=1;i<=10;i++)
			{
				If(i%2==0)
				{
					Console.WriteLine(i);
				}
			}
        }
    }
}
