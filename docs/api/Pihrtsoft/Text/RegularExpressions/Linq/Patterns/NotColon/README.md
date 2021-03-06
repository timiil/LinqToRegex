# Patterns\.NotColon Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotColon()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotColon) | Returns a pattern that matches a character that is not a colon\. |
| [NotColon(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotColon_System_Int32_) | Returns a pattern that matches a specified number of characters that are not a colon\. |

## NotColon\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotColon"></a>

\
Returns a pattern that matches a character that is not a colon\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotColon()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotColon\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotColon_System_Int32_"></a>

\
Returns a pattern that matches a specified number of characters that are not a colon\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotColon(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

