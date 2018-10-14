# Patterns\.AnyExceptLinefeed Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [AnyExceptLinefeed()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_AnyExceptLinefeed) | Returns a pattern that matches any character except linefeed\. |
| [AnyExceptLinefeed(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_AnyExceptLinefeed_System_Int32_) | Returns a pattern that matches any character except linefeed specified number of times\. |

## AnyExceptLinefeed\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_AnyExceptLinefeed"></a>

### Summary

Returns a pattern that matches any character except linefeed\.

```csharp
public static QuantifiablePattern AnyExceptLinefeed()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## AnyExceptLinefeed\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_AnyExceptLinefeed_System_Int32_"></a>

### Summary

Returns a pattern that matches any character except linefeed specified number of times\.

```csharp
public static QuantifiedGroup AnyExceptLinefeed(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
