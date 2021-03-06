# Pattern\.Options Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Options(RegexOptions)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_) | Appends a pattern that applies specified options\. |
| [Options(RegexOptions, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Object_) | Appends a pattern that applies specified options to a specified pattern\. |
| [Options(RegexOptions, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Object___) | Appends a pattern that applies specified options to a specified pattern\. |
| [Options(RegexOptions, RegexOptions)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_) | Appends a pattern that applies and disables specified options to a specified pattern\. |
| [Options(RegexOptions, RegexOptions, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_System_Object_) | Appends a pattern that applies and disables specified options to a specified pattern\. |
| [Options(RegexOptions, RegexOptions, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_System_Object___) | Appends a pattern that applies and disables specified options to a specified pattern\. |

## Options\(RegexOptions\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_"></a>

\
Appends a pattern that applies specified options\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern Options(System.Text.RegularExpressions.RegexOptions applyOptions)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

### Returns

[Pattern](../README.md)

## Options\(RegexOptions, Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Object_"></a>

\
Appends a pattern that applies specified options to a specified pattern\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Options(System.Text.RegularExpressions.RegexOptions applyOptions, object content)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## Options\(RegexOptions, Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Object___"></a>

\
Appends a pattern that applies specified options to a specified pattern\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Options(System.Text.RegularExpressions.RegexOptions applyOptions, params object[] content)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## Options\(RegexOptions, RegexOptions\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_"></a>

\
Appends a pattern that applies and disables specified options to a specified pattern\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern Options(System.Text.RegularExpressions.RegexOptions applyOptions, System.Text.RegularExpressions.RegexOptions disableOptions)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

**disableOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are disabled\.

### Returns

[Pattern](../README.md)

## Options\(RegexOptions, RegexOptions, Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_System_Object_"></a>

\
Appends a pattern that applies and disables specified options to a specified pattern\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Options(System.Text.RegularExpressions.RegexOptions applyOptions, System.Text.RegularExpressions.RegexOptions disableOptions, object content)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

**disableOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are disabled\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## Options\(RegexOptions, RegexOptions, Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Options_System_Text_RegularExpressions_RegexOptions_System_Text_RegularExpressions_RegexOptions_System_Object___"></a>

\
Appends a pattern that applies and disables specified options to a specified pattern\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Options(System.Text.RegularExpressions.RegexOptions applyOptions, System.Text.RegularExpressions.RegexOptions disableOptions, params object[] content)
```

### Parameters

**applyOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are applied\.

**disableOptions** &ensp; [RegexOptions](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions)

A bitwise combination of the enumeration values that are disabled\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

