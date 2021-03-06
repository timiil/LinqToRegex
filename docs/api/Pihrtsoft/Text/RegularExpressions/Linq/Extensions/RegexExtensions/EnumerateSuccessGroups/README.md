# RegexExtensions\.EnumerateSuccessGroups Method

[Home](../../../../../../../README.md)

**Containing Type**: [RegexExtensions](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EnumerateSuccessGroups(Regex, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_) | Searches the specified input string and returns enumerable collection of groups that have at least one capture\. |
| [EnumerateSuccessGroups(Regex, String, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_System_Int32_) | Searches the specified input string and returns enumerable collection of groups that have a specified number and have at least one capture\. |
| [EnumerateSuccessGroups(Regex, String, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_System_String_) | Searches the specified input string and returns enumerable collection of groups that have a specified name and have at least one capture\. |

## EnumerateSuccessGroups\(Regex, String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_"></a>

\
Searches the specified input string and returns enumerable collection of groups that have at least one capture\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Group> EnumerateSuccessGroups(this System.Text.RegularExpressions.Regex regex, string input)
```

### Parameters

**regex** &ensp; [Regex](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex)

The regular expression to be matched\.

**input** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

The string to search for a match\.

### Returns

[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

## EnumerateSuccessGroups\(Regex, String, Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_System_Int32_"></a>

\
Searches the specified input string and returns enumerable collection of groups that have a specified number and have at least one capture\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Group> EnumerateSuccessGroups(this System.Text.RegularExpressions.Regex regex, string input, int groupNumber)
```

### Parameters

**regex** &ensp; [Regex](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex)

The regular expression to be matched\.

**input** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

The string to search for a match\.

**groupNumber** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of the group\.

### Returns

[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

## EnumerateSuccessGroups\(Regex, String, String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateSuccessGroups_System_Text_RegularExpressions_Regex_System_String_System_String_"></a>

\
Searches the specified input string and returns enumerable collection of groups that have a specified name and have at least one capture\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Group> EnumerateSuccessGroups(this System.Text.RegularExpressions.Regex regex, string input, string groupName)
```

### Parameters

**regex** &ensp; [Regex](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex)

The regular expression to be matched\.

**input** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

The string to search for a match\.

**groupName** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A name of the group\.

### Returns

[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** or **groupName** is `null`\.

