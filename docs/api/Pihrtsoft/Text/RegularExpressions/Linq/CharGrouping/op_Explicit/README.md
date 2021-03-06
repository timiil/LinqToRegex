# CharGrouping\.Explicit Operator

[Home](../../../../../../README.md)

**Containing Type**: [CharGrouping](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Operator | Summary |
| -------- | ------- |
| [Explicit(Char to CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_Char__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping) | Converts specified character to an instance of the [CharGrouping](../README.md) class\. |
| [Explicit(String to CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_String__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping) | Converts specified characters to an instance of the [CharGrouping](../README.md) class\. |

## Explicit\(Char to CharGrouping\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_Char__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping"></a>

\
Converts specified character to an instance of the [CharGrouping](../README.md) class\.

```csharp
public static explicit operator Pihrtsoft.Text.RegularExpressions.Linq.CharGrouping(char value)
```

### Parameters

**value** &ensp; [Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

### Returns

[CharGrouping](../README.md)

## Explicit\(String to CharGrouping\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_String__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping"></a>

\
Converts specified characters to an instance of the [CharGrouping](../README.md) class\.

```csharp
public static explicit operator Pihrtsoft.Text.RegularExpressions.Linq.CharGrouping(string characters)
```

### Parameters

**characters** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A set of Unicode characters\.

### Returns

[CharGrouping](../README.md)

### Exceptions

[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**characters** length is equal to zero\.

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**characters** is `null`\.

