# Pattern\.Underscore Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Underscore()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Underscore) | Appends a pattern that matches an underscore\. |
| [Underscore(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Underscore_System_Int32_) | Appends a pattern that matches a specified number of underscores\. |

## Underscore\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Underscore"></a>

\
Appends a pattern that matches an underscore\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Underscore()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## Underscore\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Underscore_System_Int32_"></a>

\
Appends a pattern that matches a specified number of underscores\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup Underscore(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

