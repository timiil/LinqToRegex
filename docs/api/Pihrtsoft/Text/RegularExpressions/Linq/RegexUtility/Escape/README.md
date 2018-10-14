# RegexUtility\.Escape Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[RegexUtility](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Escape(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_) | Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\. The character is considered not to be in the character group\. |
| [Escape(Char, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_System_Boolean_) | Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\. |
| [Escape(String)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_) | Converts a specified text to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\. The text is considered not to be in the character group\. |
| [Escape(String, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_System_Boolean_) | Converts a specified input to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\. |

## Escape\(Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_"></a>

### Summary

Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\.
The character is considered not to be in the character group\.

```csharp
public static string Escape(char value)
```

### Parameters

**value**

A Unicode character\.

### Returns

System\.[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

## Escape\(Char, Boolean\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_System_Boolean_"></a>

### Summary

Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\.

```csharp
public static string Escape(char value, bool inCharGroup)
```

### Parameters

**value**

A Unicode character\.

**inCharGroup**

Indicates whether the character is considered to be inside or outside of the character group\.

### Returns

System\.[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

## Escape\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_"></a>

### Summary

Converts a specified text to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\.
The text is considered not to be in the character group\.

```csharp
public static string Escape(string input)
```

### Parameters

**input**

The text to be converted\.

### Returns

System\.[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

## Escape\(String, Boolean\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_System_Boolean_"></a>

### Summary

Converts a specified input to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\.

```csharp
public static string Escape(string input, bool inCharGroup)
```

### Parameters

**input**

The text to be converted\.

**inCharGroup**

Indicates whether the text is considered to be inside or outside of the character group\.

### Returns

System\.[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.
