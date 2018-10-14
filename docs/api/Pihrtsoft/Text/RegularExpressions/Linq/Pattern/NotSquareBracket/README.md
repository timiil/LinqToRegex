# Pattern\.NotSquareBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotSquareBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotSquareBracket) | Appends a pattern that matches a character that is neither left nor right square bracket\. |
| [NotSquareBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotSquareBracket_System_Int32_) | Appends a pattern that matches a character that is neither left nor right square bracket specified number of times\. |

## NotSquareBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotSquareBracket"></a>

### Summary

Appends a pattern that matches a character that is neither left nor right square bracket\.

```csharp
public CharGroup NotSquareBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGroup](../../CharGroup/README.md)

## NotSquareBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotSquareBracket_System_Int32_"></a>

### Summary

Appends a pattern that matches a character that is neither left nor right square bracket specified number of times\.

```csharp
public QuantifiedGroup NotSquareBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
