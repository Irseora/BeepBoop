- `obj n = new obj;`
- (insertion, selection, bubble)
- *Cautare binara: `lo + (hi - lo) / 2`  pt. a evita overflow*
- $O(n \ log \ n)$ = liniaritmic
- Introduction to Algorithms - 
- Algorithms - 

```csharp
// Determina cate perechi de numere din vectorul arr au suma 0
public static int countFaster(int[] arr)
{
	int contor = 0;
	
	int n;
	
	n = arr.Length;
	
	Array.Sort(arr);
	
	int i = 0, j = arr.Length - 1;
	while (i < j)
	{
		if (arr[i] + arr[j] == 0)
		{
			contor++;
			i++; j--;
		}
		else if (arr[i] + arr[j] < 0)
			i++;
		else
			j--;
	}
	
	return contor;
}
```