```csharp
static Random rand = new Random();

static void Main()
{
	int[] a = new int[10];
	int[] b = new int[] {0, 1, 2, 3};
	int[] c = InitArray(10);
	int[] d = InitArray(10, 100);
	
	PrintArray(v1);
}

// Init toate elementele cu 0
static int[] InitArray(int n)
{ return new int[n]; }

// Init elemente random
static int[] InitArray(int n, int max)
{
	int[] v = new int[n];
	
	for (int i = 0; i < v.Length; i++)
		v[i] = rand.Next();
	
	return v;
}

// Afiseaza elementele unui vector
static void PrintArray(int[] v)
{
	for (int i = 0; i < v.Length; i++)
		Console.Write($"{v[i]} ");
	Console.WriteLine();
}
```

---

###
- [[LRSNO]]
- [[Cautare Binara]]