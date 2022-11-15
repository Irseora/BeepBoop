```csharp
using System.Threading;

// ...

static Random rand = new Random();

static void Main()
{
	// Firul de executie asteapta 10 ms
	// Thread.Sleep(10);
	// Random rand = new Random();
	
	int n = 100;
	int[] v = new int[n];
	for (int i = 0; i < v.Length; i++)
		v[i] = rand.Next();
}


```