# Patterns\.NotSpace Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotSpace()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSpace) | Returns a pattern that matches a character that is not a space\. |
| [NotSpace(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSpace_System_Int32_) | Returns a pattern that matches a specified number of characters that are not a space\. |

## NotSpace\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSpace"></a>

\
Returns a pattern that matches a character that is not a space\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotSpace()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotSpace\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSpace_System_Int32_"></a>

\
Returns a pattern that matches a specified number of characters that are not a space\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotSpace(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

