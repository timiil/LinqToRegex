# Patterns\.DisallowGroup Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [DisallowGroup(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_DisallowGroup_System_Int32_) | Returns a pattern that requires previously defined group with a specified number not to be matched\. Otherwise, a match will fail\. |
| [DisallowGroup(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_DisallowGroup_System_String_) | Returns a pattern that requires previously defined group with a specified name not to be matched\. Otherwise, a match will fail\. |

## DisallowGroup\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_DisallowGroup_System_Int32_"></a>

\
Returns a pattern that requires previously defined group with a specified number not to be matched\. Otherwise, a match will fail\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.Pattern DisallowGroup(int groupNumber)
```

### Parameters

**groupNumber** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of the group\.

### Returns

[Pattern](../../Pattern/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**groupNumber** is less than zero\.

## DisallowGroup\(String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_DisallowGroup_System_String_"></a>

\
Returns a pattern that requires previously defined group with a specified name not to be matched\. Otherwise, a match will fail\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.Pattern DisallowGroup(string groupName)
```

### Parameters

**groupName** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A name of the group\.

### Returns

[Pattern](../../Pattern/README.md)

### Exceptions

[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**groupName** is not a valid regex group name\.

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**groupName** is `null`\.

