# Pattern\.SurroundCurlyBrackets Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [SurroundCurlyBrackets()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets) | Appends a pattern that matches a text consisting of left and right curly bracket, allowing zero or more characters that are not a right curly bracket between the brackets\. |
| [SurroundCurlyBrackets(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets_System_Object_) | Appends a pattern that matches specified pattern surrounded with left and right curly bracket\. |
| [SurroundCurlyBrackets(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets_System_Object___) | Appends a pattern that matches specified content surrounded with left and right curly bracket\. |

## SurroundCurlyBrackets\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets"></a>

\
Appends a pattern that matches a text consisting of left and right curly bracket, allowing zero or more characters that are not a right curly bracket between the brackets\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundCurlyBrackets()
```

### Returns

[Pattern](../README.md)

## SurroundCurlyBrackets\(Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets_System_Object_"></a>

\
Appends a pattern that matches specified pattern surrounded with left and right curly bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundCurlyBrackets(object content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[Pattern](../README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## SurroundCurlyBrackets\(Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundCurlyBrackets_System_Object___"></a>

\
Appends a pattern that matches specified content surrounded with left and right curly bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundCurlyBrackets(params object[] content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

[Pattern](../README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

