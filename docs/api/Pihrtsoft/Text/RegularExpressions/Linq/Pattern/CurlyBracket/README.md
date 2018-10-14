# Pattern\.CurlyBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [CurlyBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket) | Appends a pattern that matches left or right curly bracket\. |
| [CurlyBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket_System_Int32_) | Appends a pattern that matches left or right curly bracket specified number of times\. |

## CurlyBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket"></a>

### Summary

Appends a pattern that matches left or right curly bracket\.

```csharp
public CharGroup CurlyBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGroup](../../CharGroup/README.md)

## CurlyBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket_System_Int32_"></a>

### Summary

Appends a pattern that matches left or right curly bracket specified number of times\.

```csharp
public QuantifiedGroup CurlyBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.
