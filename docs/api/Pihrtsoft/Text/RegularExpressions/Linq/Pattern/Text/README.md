# Pattern\.Text Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Text(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Text_System_String_) | Appends a pattern that matches a specified text\. |
| [Text(String, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Text_System_String_System_Boolean_) | Appends a pattern that matches a specified text, ignoring or honoring its case\. |

## Text\(String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Text_System_String_"></a>

\
Appends a pattern that matches a specified text\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern Text(string value)
```

### Parameters

**value** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A text to append\.

### Returns

[Pattern](../README.md)

## Text\(String, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Text_System_String_System_Boolean_"></a>

\
Appends a pattern that matches a specified text, ignoring or honoring its case\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Text(string value, bool ignoreCase)
```

### Parameters

**value** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A text to append\.

**ignoreCase** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

true to ignore case during the matching; otherwise, false\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

