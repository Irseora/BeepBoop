```csharp
// Sortare in ordine crescatoare
Array.Sort(v);

/// <summary>
/// Cauta binar o cheie intr-un vector sortat crescator
/// Complexitate: O(?)
/// </summary>
/// <param name = "v"> vectorul sortat crescator </param>
/// <param name = "k"> cheia cautata </param>
/// <returns>
/// Indexul pe care se afla cheia,
/// sau -1 daca nu se afla in vector
/// </returns>
static void CautareBinara(int[] v, int k)
{
	int limJos = 0, limSus = v.Length - 1;
	
	while (limJos <= limSus)
	{
		int mijloc = (limJos + limSus) / 2;
		
		if (v[k] < mijloc)
			limJos = mijloc + 1;
		else if (v[k] > mijloc)
			limSus = mijloc - 1;
		else
			return mijloc;
	}
	
	return -1;
}
```

#### Approximate Search
- Implementati operatiile de cautare aproximativa:
  rank, predecesor, succesor & cel mai apropiat vecin