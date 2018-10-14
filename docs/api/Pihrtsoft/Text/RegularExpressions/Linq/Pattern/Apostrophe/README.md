# Pattern\.Apostrophe Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Apostrophe()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Apostrophe) | Appends a pattern that matches an apostrophe\. |
| [Apostrophe(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Apostrophe_System_Int32_) | Appends a pattern that matches a specified number of apostrophes\. |

## Apostrophe\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Apostrophe"></a>

### Summary

Appends a pattern that matches an apostrophe\.

```csharp
public QuantifiablePattern Apostrophe()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## Apostrophe\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Apostrophe_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of apostrophes\.

```csharp
public QuantifiedGroup Apostrophe(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
