# Patterns\.NotAsterisk Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotAsterisk()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotAsterisk) | Returns a pattern that matches a character that is not an asterisk\. |
| [NotAsterisk(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotAsterisk_System_Int32_) | Returns a pattern that matches a specified number of characters that are not an asterisk\. |

## NotAsterisk\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotAsterisk"></a>

### Summary

Returns a pattern that matches a character that is not an asterisk\.

```csharp
public static QuantifiablePattern NotAsterisk()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotAsterisk\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotAsterisk_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of characters that are not an asterisk\.

```csharp
public static QuantifiedGroup NotAsterisk(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
