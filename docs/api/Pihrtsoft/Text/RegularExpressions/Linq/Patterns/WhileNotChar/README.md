# Patterns\.WhileNotChar Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [WhileNotChar(AsciiChar)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_) | Returns a pattern that matches zero or more characters that are not a specified character\. |
| [WhileNotChar(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_Char_) | Returns a pattern that matches zero or more characters that are not a specified character\. |
| [WhileNotChar(Char\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_Char___) | Returns a pattern that matches zero or more characters that are not contained in the specified characters |
| [WhileNotChar(CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_) | Returns a pattern that matches zero or more characters that are not matched by a specified [CharGrouping](../../CharGrouping/README.md)\. |
| [WhileNotChar(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_String_) | Returns a pattern that matches zero or more characters that are not contained in the specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\. |

## WhileNotChar\(AsciiChar\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_"></a>

### Summary

Returns a pattern that matches zero or more characters that are not a specified character\.

```csharp
public static QuantifiedPattern WhileNotChar(AsciiChar value)
```

### Parameters

**value**

An enumerated constant that identifies ASCII character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedPattern](../../QuantifiedPattern/README.md)

## WhileNotChar\(Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_Char_"></a>

### Summary

Returns a pattern that matches zero or more characters that are not a specified character\.

```csharp
public static QuantifiedPattern WhileNotChar(char value)
```

### Parameters

**value**

A Unicode character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedPattern](../../QuantifiedPattern/README.md)

## WhileNotChar\(Char\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_Char___"></a>

### Summary

Returns a pattern that matches zero or more characters that are not contained in the specified characters

```csharp
public static QuantifiedPattern WhileNotChar(params char[] characters)
```

### Parameters

**characters**

Unicode characters\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedPattern](../../QuantifiedPattern/README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**characters** is empty\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**characters** is `null`\.

## WhileNotChar\(CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_"></a>

### Summary

Returns a pattern that matches zero or more characters that are not matched by a specified [CharGrouping](../../CharGrouping/README.md)\.

```csharp
public static QuantifiedPattern WhileNotChar(CharGrouping value)
```

### Parameters

**value**

A set of Unicode characters\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedPattern](../../QuantifiedPattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**value** is `null`\.

## WhileNotChar\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_WhileNotChar_System_String_"></a>

### Summary

Returns a pattern that matches zero or more characters that are not contained in the specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\.

```csharp
public static QuantifiedPattern WhileNotChar(string characters)
```

### Parameters

**characters**

Unicode characters\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedPattern](../../QuantifiedPattern/README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**characters** length is equal to zero\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**characters** is `null`\.
