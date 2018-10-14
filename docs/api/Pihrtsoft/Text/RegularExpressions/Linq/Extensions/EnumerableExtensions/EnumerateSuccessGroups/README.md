# EnumerableExtensions\.EnumerateSuccessGroups Method

[Home](../../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.Extensions\.[EnumerableExtensions](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EnumerateSuccessGroups(IEnumerable\<Match>)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__) | Returns an enumerable collection of groups that have at least one capture\. |
| [EnumerateSuccessGroups(IEnumerable\<Match>, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_Int32_) | Returns an enumerable collection of groups that have a specified name and have at least one capture\. |
| [EnumerateSuccessGroups(IEnumerable\<Match>, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_String_) | Returns an enumerable collection of groups thas have a specified name and have at least one capture\. |

## EnumerateSuccessGroups\(IEnumerable\<Match>\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__"></a>

### Summary

Returns an enumerable collection of groups that have at least one capture\.

```csharp
public static IEnumerable<Group> EnumerateSuccessGroups(this IEnumerable<Match> matches)
```

### Parameters

**matches**

The sequence to enumerate\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** is `null`\.

## EnumerateSuccessGroups\(IEnumerable\<Match>, Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_Int32_"></a>

### Summary

Returns an enumerable collection of groups that have a specified name and have at least one capture\.

```csharp
public static IEnumerable<Group> EnumerateSuccessGroups(this IEnumerable<Match> matches, int groupNumber)
```

### Parameters

**matches**

The sequence to enumerate\.

**groupNumber**

A number of the group\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** is `null`\.

## EnumerateSuccessGroups\(IEnumerable\<Match>, String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateSuccessGroups_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_String_"></a>

### Summary

Returns an enumerable collection of groups thas have a specified name and have at least one capture\.

```csharp
public static IEnumerable<Group> EnumerateSuccessGroups(this IEnumerable<Match> matches, string groupName)
```

### Parameters

**matches**

The sequence to enumerate\.

**groupName**

A name of the group\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Group](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.group)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** or **groupName** is `null`\.
