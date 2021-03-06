---
title: Nullable.decimal<^T> Function (F#)
description: Nullable.decimal<^T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 36366a96-5c1f-486d-9c1f-cd9c46d6cd87 
---

# Nullable.decimal<^T> Function (F#)

Converts the argument to **T:System.Decimal** using a direct conversion for all primitive numeric types. The operation requires an appropriate static conversion method on the input type.

**Namespace/Module Path**: Microsoft.FSharp.Linq.Nullable

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
decimal : Nullable<^T> -> Nullable<decimal> when ^T with static member op_Explicit and ^T : (new : unit ->  ^T) and ^T : struct and ^T :> ValueType

// Usage:
Nullable.decimal value
```

#### Parameters
*value*
Type: **T:System.Nullable&#96;1**&lt;^T&gt;


The input value.




## Return Value
The converted decimal.


## Remarks
This function is named **ToDecimal** in the .NET assembly. If accessing the member from a .NET language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.Nullable Module &#40;F&#35;&#41;](Linq.Nullable-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq-Namespace-%5BFSharp%5D.md)

[Operators.decimal&#60;^T&#62; Function &#40;F&#35;&#41;](Operators.decimal%5B%5ET%5D-Function-%5BFSharp%5D.md)

