# Pattern\.ArabicDigit Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [ArabicDigit()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_ArabicDigit) | Appends a pattern that matches an arabic digit\. |
| [ArabicDigit(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_ArabicDigit_System_Int32_) | Appends a pattern that matches a specified number of arabic digits\. |

## ArabicDigit\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_ArabicDigit"></a>

### Summary

Appends a pattern that matches an arabic digit\.

```csharp
public QuantifiablePattern ArabicDigit()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## ArabicDigit\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_ArabicDigit_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of arabic digits\.

```csharp
public QuantifiedGroup ArabicDigit(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
