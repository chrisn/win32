---
title: all
description: Determines if all components of the specified value are non-zero.
ms.assetid: 9ee079ff-cd2c-41f5-98cd-ea1f4215e7d5
keywords:
- all HLSL
topic_type:
- apiref
api_name:
- all
api_type:
- NA
ms.topic: reference
ms.date: 05/31/2018
api_location: 
---

# all

Determines if all components of the specified value are non-zero.



| *ret* all(*x*) |
|----------------|



 

## Parameters



| Item                                                   | Description                            |
|--------------------------------------------------------|----------------------------------------|
| <span id="x"></span><span id="X"></span>*x*<br/> | \[in\] The specified value.<br/> |



 

## Return Value

**True** if all components of the *x* parameter are non-zero; otherwise, **false**.

## Remarks

This function is similar to the [**any**](dx-graphics-hlsl-any.md) HLSL intrinsic function. The **any** function determines if any components of the specified value are non-zero, while the **all** function determines if all components of the specified value are non-zero.

## Type Description



| Name  | [**Template Type**](dx-graphics-hlsl-intrinsic-functions.md)                                                  | [**Component Type**](dx-graphics-hlsl-intrinsic-functions.md)                                                         | Size |
|-------|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|------|
| *x*   | [**scalar**](dx-graphics-hlsl-intrinsic-functions.md), **vector**, or **matrix** | [**float**](/windows/desktop/WinProg/windows-data-types), [**int**](/windows/desktop/WinProg/windows-data-types), [**bool**](/windows/desktop/WinProg/windows-data-types) | any  |
| *ret* | [**scalar**](dx-graphics-hlsl-intrinsic-functions.md)                            | [**bool**](/windows/desktop/WinProg/windows-data-types)                                                                                 | 1    |



 

## Minimum Shader Model

This function is supported in the following shader models.



| Shader Model                                                                       | Supported             |
|------------------------------------------------------------------------------------|-----------------------|
| [Shader Model 2 (DirectX HLSL)](dx-graphics-hlsl-sm2.md) and higher shader models | yes                   |
| [Shader Model 1 (DirectX HLSL)](dx-graphics-hlsl-sm1.md)                          | vs\_1\_1 and ps\_1\_4 |



 

## See also

<dl> <dt>

[**Intrinsic Functions (DirectX HLSL)**](dx-graphics-hlsl-intrinsic-functions.md)
</dt> </dl>

 

