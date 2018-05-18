---
title: CLUSCTL\_RESOURCE\_TYPE\_GET\_CLASS\_INFO control code
description: Retrieves the class and subclass of a resource type.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 'db811070-9de6-4368-b9b5-ac17259d68a1'
ms.prod: 'windows-server-dev'
ms.technology: 'failover-clustering'
ms.tgt_platform: multiple
keywords: ["CLUSCTL_RESOURCE_TYPE_GET_CLASS_INFO control code Failover Cluster"]
topic_type:
- apiref
api_name:
- CLUSCTL_RESOURCE_TYPE_GET_CLASS_INFO
api_location:
- ClusAPI.h
api_type:
- HeaderDef
---

# CLUSCTL\_RESOURCE\_TYPE\_GET\_CLASS\_INFO control code

Retrieves the class and subclass of a [resource type](resource-types.md). A resource type class identifies resource types of similar capability. Applications use this [control code](about-control-codes.md) as a parameter to the [**ClusterResourceTypeControl**](clusterresourcetypecontrol.md) function, and [resource DLLs](resource-dlls.md) receive the control code as a parameter to the [**ResourceTypeControl**](resourcetypecontrol.md) function.

A resource DLL receives the CLUSCTL\_RESOURCE\_TYPE\_GET\_CLASS\_INFO control code when an application requests the resource type class of a resource type.


```C++
ClusterResourceTypeControl( hCluster,                             // cluster handle
                            lpszResTypeName,                      // resource type name
                            hHostNode,                            // optional host node
                            CLUSCTL_RESOURCE_TYPE_GET_CLASS_INFO, // this control code
                            NULL,                                 // input buffer (not used)
                            0,                                    // input buffer size (not used)
                            lpOutBuffer,                          // output buffer: CLUS_RESOURCE_TYPE_CLASS_INFO structure
                            cbOutBufferSize,                      // allocated buffer size (bytes)
                            lpcbBytesReturned );                  // actual size of resulting data (bytes)
```



## Parameters

The following control code function and DLL support parameter is specific to this control code. For complete parameter descriptions, see [**ClusterResourceTypeControl**](clusterresourcetypecontrol.md) or [**ResourceTypeControl**](resourcetypecontrol.md).

<dl> <dt>

*lpOutBuffer* 
</dt> <dd>

On a successful return, points to a [**CLUS\_RESOURCE\_CLASS\_INFO**](clus-resource-class-info.md) structure containing resource type class information for the resource type.

</dd> </dl>

## Return value

[**ClusterResourceTypeControl**](clusterresourcetypecontrol.md) returns one of the following values.

<dl> <dt>

**ERROR\_SUCCESS**
</dt> <dd>

0

The operation completed successfully. The *lpcbBytesReturned* parameter points to the actual size of the returned data.

</dd> <dt>

**ERROR\_MORE\_DATA**
</dt> <dd>

234 (0xEA)

More data is available. The output buffer pointed to by *lpOutBuffer* was not large enough to hold the data resulting from the operation. The *lpcbBytesReturned* parameter points to the size required for the output buffer.

</dd> <dt>

**[System error code](https://msdn.microsoft.com/library/windows/desktop/ms681381)**
</dt> <dd>

If any other value is returned, then the operation failed. The value of *lpcbBytesReturned* is unreliable.

</dd> </dl>

## Remarks

ClusAPI.h defines the 32 bits of CLUSCTL\_RESOURCE\_TYPE\_GET\_CLASS\_INFO as follows.



| Component                 | Bit location     | Value                                             |
|---------------------------|------------------|---------------------------------------------------|
| Object code<br/>    | 24�31<br/> | **CLUS\_OBJECT\_RESOURCE\_TYPE** (0x2)<br/> |
| Global bit<br/>     | 23<br/>    | **CLUS\_NOT\_GLOBAL** (0x0)<br/>            |
| Modify bit<br/>     | 22<br/>    | **CLUS\_NO\_MODIFY** (0x0)<br/>             |
| User bit<br/>       | 21<br/>    | **CLCTL\_CLUSTER\_BASE** (0x0)<br/>         |
| Type bit<br/>       | 20<br/>    | External (0x0)<br/>                         |
| Operation code<br/> | 0�23<br/>  | **CLCTL\_GET\_CLASS\_INFO** (0xd)<br/>      |
| Access code<br/>    | 0�1<br/>   | **CLUS\_ACCESS\_READ** (0x1)<br/>           |



�

For more information, see [Control Code Architecture](control-code-architecture.md).

### Resource DLL Support

Optional. If you do not support it, return **ERROR\_INVALID\_FUNCTION** to let the Resource Monitor provide default handling. The Resource Monitor will specify **CLUS\_RESCLASS\_UNKNOWN** as the class and zero as the subclass.

For more information on the [**ResourceTypeControl**](resourcetypecontrol.md) entry point, see [Implementing ResourceTypeControl](implementing-resourcetypecontrol.md).

## Requirements



|                                     |                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                            |
| Minimum supported server<br/> | Windows Server�2008 Enterprise, Windows Server�2008 Datacenter<br/>            |
| Header<br/>                   | <dl> <dt>ClusAPI.h</dt> </dl> |



## See also

<dl> <dt>

[External Resource Type Control Codes](external-resource-type-control-codes.md)
</dt> <dt>

[**ClusterResourceTypeControl**](clusterresourcetypecontrol.md)
</dt> <dt>

[**ResourceTypeControl**](resourcetypecontrol.md)
</dt> </dl>

�

�




