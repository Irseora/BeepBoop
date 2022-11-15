```csharp
static void Main()
{
	// Init vector v w/ 10 random elements, 0-99
	int[] v = InitArray(10, 100)
	
	if ((int pos = CautareLineara(v, k)) != -1)
		Console.WriteLine($"{k} este pe pozitia {pos}");
	else
		Console.Writeline($"{k} nu este in vector");
}

/// <summary>
/// Cauta linear o cheie intr-un vector, O(n)
/// </summary>
/// <param name = "v"> vectorul in care se cauta </param>
/// <param name = "k"> cheia cautata </param>
/// <returns>
/// Indexul pe care se afla cheia,
/// sau -1 daca nu se afla in vector
/// </returns>
static int CautareLineara()
{
	for (int i = 0; i < v.Length; i++)
		if (v[i] == k)
			return i;
	
	return -1;
}
```