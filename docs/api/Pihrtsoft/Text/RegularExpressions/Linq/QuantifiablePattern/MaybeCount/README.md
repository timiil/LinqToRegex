# QuantifiablePattern\.MaybeCount\(Int32\) Method

[Home](../../../../../../README.md)

**Containing Type**: [QuantifiablePattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

\
Specifies that previous element must be matched at most specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedPattern MaybeCount(int maxCount)
```

### Parameters

**maxCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A maximum number of times the pattern can be matched\.

### Returns

[QuantifiedPattern](../../QuantifiedPattern/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**maxCount** is less than zero\.

