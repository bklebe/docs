---
title: QueryBuilder.SortByNullable<'T,'Q,'Key> Method (F#)
description: QueryBuilder.SortByNullable<'T,'Q,'Key> Method (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.technology: devlang-fsharp
ms.assetid: fa91741f-5e2a-4beb-a989-8770c4e6082d
---

# QueryBuilder.SortByNullable<'T,'Q,'Key> Method (F#)

A query operator that sorts the elements selected so far in ascending order by the given nullable sorting key.

**Namespace/Module Path**: Microsoft.FSharp.Linq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```fsharp
// Signature:
member this.SortByNullable : QuerySource<'T,'Q> * ('T -> Nullable<'Key>) -> QuerySource<'T,'Q> when 'Key : (IComparable) and 'Key : (new : unit ->  'Key) and 'Key : struct and 'Key :> ValueType

// Usage:
queryBuilder.SortByNullable (source, keySelector)
```

#### Parameters
*source*
Type: [QuerySource](https://msdn.microsoft.com/library/873589c1-c5dc-47d9-8abf-fee7258dfb00)&lt;'T,'Q&gt;


The input query.


*keySelector*
Type: 'T -&gt;
**System.Nullable&#96;1**&lt;'Key&gt;


Specifies the field to sort by.

## Return Value
The sorted query.

## Remarks
For more information and examples, see [Query Expressions (F#)](https://msdn.microsoft.com/library/ff72235c-3ad8-4215-8679-2754484823db).

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2

## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable

## See Also
[Linq.QueryBuilder Class](Linq.QueryBuilder-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Linq Namespace](Microsoft.FSharp.Linq-Namespace-%5BFSharp%5D.md)

[Query Expressions (F#)](https://msdn.microsoft.com/library/ff72235c-3ad8-4215-8679-2754484823db)