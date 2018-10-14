# Pattern\.NotLeftCurlyBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotLeftCurlyBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftCurlyBracket) | Appends a pattern that matches a character that is not a left curly bracket\. |
| [NotLeftCurlyBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftCurlyBracket_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a left curly bracket\. |

## NotLeftCurlyBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftCurlyBracket"></a>

### Summary

Appends a pattern that matches a character that is not a left curly bracket\.

```csharp
public QuantifiablePattern NotLeftCurlyBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotLeftCurlyBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftCurlyBracket_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of characters that are not a left curly bracket\.

```csharp
public QuantifiedGroup NotLeftCurlyBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
