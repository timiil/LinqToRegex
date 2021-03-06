# Pattern\.Alphanumeric Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Alphanumeric()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Alphanumeric) | Appends a pattern that matches an alphanumeric character\. Alphanumeric character is a latin alphabet letter or an arabic digit\. |
| [Alphanumeric(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Alphanumeric_System_Int32_) | Appends a pattern that matches a specified number of alphanumeric characters\. Alphanumeric character is a latin alphabet letter or an arabic digit\. |

## Alphanumeric\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Alphanumeric"></a>

\
Appends a pattern that matches an alphanumeric character\. Alphanumeric character is a latin alphabet letter or an arabic digit\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.CharGroup Alphanumeric()
```

### Returns

[CharGroup](../../CharGroup/README.md)

## Alphanumeric\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Alphanumeric_System_Int32_"></a>

\
Appends a pattern that matches a specified number of alphanumeric characters\. Alphanumeric character is a latin alphabet letter or an arabic digit\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup Alphanumeric(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

