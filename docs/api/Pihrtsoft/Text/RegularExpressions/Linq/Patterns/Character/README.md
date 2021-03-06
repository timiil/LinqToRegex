# Patterns\.Character Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Character(AsciiChar)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_) | Returns a pattern that matches a specified character\. |
| [Character(GeneralCategory)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_GeneralCategory_) | Returns a pattern that matches a character from a specified Unicode category\. |
| [Character(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_System_Char_) | Returns a pattern that matches a specified character\. |
| [Character(CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_) | Returns a pattern that matches a character from a specified [CharGrouping](../../CharGrouping/README.md)\. |
| [Character(NamedBlock)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_NamedBlock_) | Returns a pattern that matches a character from a specified Unicode block\. |
| [Character(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_System_String_) | Returns a pattern that matches a character from a specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\. |

## Character\(AsciiChar\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_"></a>

\
Returns a pattern that matches a specified character\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharPattern Character(Pihrtsoft.Text.RegularExpressions.Linq.AsciiChar value)
```

### Parameters

**value** &ensp; [AsciiChar](../../AsciiChar/README.md)

An enumerated constant that identifies ASCII character\.

### Returns

[CharPattern](../../CharPattern/README.md)

## Character\(GeneralCategory\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_GeneralCategory_"></a>

\
Returns a pattern that matches a character from a specified Unicode category\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharPattern Character(Pihrtsoft.Text.RegularExpressions.Linq.GeneralCategory category)
```

### Parameters

**category** &ensp; [GeneralCategory](../../GeneralCategory/README.md)

An enumerated constant that identifies Unicode category\.

### Returns

[CharPattern](../../CharPattern/README.md)

## Character\(Char\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_System_Char_"></a>

\
Returns a pattern that matches a specified character\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharPattern Character(char value)
```

### Parameters

**value** &ensp; [Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

### Returns

[CharPattern](../../CharPattern/README.md)

## Character\(CharGrouping\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_"></a>

\
Returns a pattern that matches a character from a specified [CharGrouping](../../CharGrouping/README.md)\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharGroup Character(Pihrtsoft.Text.RegularExpressions.Linq.CharGrouping value)
```

### Parameters

**value** &ensp; [CharGrouping](../../CharGrouping/README.md)

A content of a character group\.

### Returns

[CharGroup](../../CharGroup/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**value** is `null`\.

## Character\(NamedBlock\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_Pihrtsoft_Text_RegularExpressions_Linq_NamedBlock_"></a>

\
Returns a pattern that matches a character from a specified Unicode block\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharPattern Character(Pihrtsoft.Text.RegularExpressions.Linq.NamedBlock block)
```

### Parameters

**block** &ensp; [NamedBlock](../../NamedBlock/README.md)

An enumerated constant that identifies Unicode block\.

### Returns

[CharPattern](../../CharPattern/README.md)

## Character\(String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Character_System_String_"></a>

\
Returns a pattern that matches a character from a specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharGroup Character(string characters)
```

### Parameters

**characters** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A set of characters any one of which has to be matched\.

### Returns

[CharGroup](../../CharGroup/README.md)

### Exceptions

[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**characters** length is equal to zero\.

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**characters** is `null`\.

