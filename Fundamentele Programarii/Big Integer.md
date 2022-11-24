#### Declaratie - Initializare
```csharp
BigInteger b1 = new BigInteger(123456);
BigInteger b2 = BigInteger.Parse("12345678901234567890");
BigInteger b3 = BigInteger.Parse("1234567890");
```

#### Operatii
```csharp
BigInteger b4 = b2 + b3;
BigInteger b5 = b2 << 1;  // Echivalent cu b2 * 2
if (b1 > b2) Console.Writeline($"{b1} > {b2}");
```