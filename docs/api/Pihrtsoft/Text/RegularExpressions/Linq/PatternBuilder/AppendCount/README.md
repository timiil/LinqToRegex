# PatternBuilder\.AppendCount Method

[Home](../../../../../../README.md)

**Containing Type**: [PatternBuilder](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [AppendCount(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_) | Appends a quantifier that matches previous element specific number of times\. |
| [AppendCount(Int32, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Boolean_) | Appends a quantifier that matches previous element specific number of times\. |
| [AppendCount(Int32, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Int32_) | Appends a quantifier that matches previous element from minimal to maximum times\. |
| [AppendCount(Int32, Int32, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Int32_System_Boolean_) | Appends a quantifier that matches previous element from minimal to maximum times\. |

## AppendCount\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_"></a>

\
Appends a quantifier that matches previous element specific number of times\.

```csharp
public void AppendCount(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times the pattern must be matched\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

## AppendCount\(Int32, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Boolean_"></a>

\
Appends a quantifier that matches previous element specific number of times\.

```csharp
public void AppendCount(int exactCount, bool lazy)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times the pattern must be matched\.

**lazy** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the quantifier will be greedy or lazy\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

## AppendCount\(Int32, Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Int32_"></a>

\
Appends a quantifier that matches previous element from minimal to maximum times\.

```csharp
public void AppendCount(int minCount, int maxCount)
```

### Parameters

**minCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A minimal number of times the pattern must be matched\.

**maxCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A maximum number of times the pattern can be matched\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero or **maxCount** is less than **minCount**\.

## AppendCount\(Int32, Int32, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCount_System_Int32_System_Int32_System_Boolean_"></a>

\
Appends a quantifier that matches previous element from minimal to maximum times\.

```csharp
public void AppendCount(int minCount, int maxCount, bool lazy)
```

### Parameters

**minCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A minimal number of times the pattern must be matched\.

**maxCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A maximum number of times the pattern can be matched\.

**lazy** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the quantifier will be greedy or lazy\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero or **maxCount** is less than **minCount**\.

