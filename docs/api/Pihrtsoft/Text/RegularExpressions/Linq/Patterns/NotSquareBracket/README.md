# Patterns\.NotSquareBracket Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotSquareBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSquareBracket) | Returns a pattern that matches a character that is neither left nor right square bracket\. |
| [NotSquareBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSquareBracket_System_Int32_) | Returns a pattern that matches a character that is neither left nor right square bracket specified number of times\. |

## NotSquareBracket\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSquareBracket"></a>

\
Returns a pattern that matches a character that is neither left nor right square bracket\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharGroup NotSquareBracket()
```

### Returns

[CharGroup](../../CharGroup/README.md)

## NotSquareBracket\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotSquareBracket_System_Int32_"></a>

\
Returns a pattern that matches a character that is neither left nor right square bracket specified number of times\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotSquareBracket(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

