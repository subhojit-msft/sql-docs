---
description: "ISQLServerPreparedStatement Interface"
title: "ISQLServerPreparedStatement Interface | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
ms.assetid: cf87892e-5c34-4ac6-8258-c2a81e117b26
author: David-Engel
ms.author: v-davidengel
---
# ISQLServerPreparedStatement Interface
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Represents the basic implementation of JDBC prepared statement functionality. This interface was added in [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] JDBC Driver 3.0.  
  
 **Package:** com.microsoft.sqlserver.jdbc  
  
 **Extends:** java.sql.PreparedStatement, [ISQLServerStatement](../../../connect/jdbc/reference/isqlserverstatement-interface.md)  
  
## Syntax  
  
```  
  
public interface ISQLServerPreparedStatement  
```  
  
## Remarks  
 This interface is implemented by [SQLServerPreparedStatement Class](../../../connect/jdbc/reference/sqlserverpreparedstatement-class.md).  
  
 This interface exposes the following [!INCLUDE[jdbcNoVersion](../../../includes/jdbcnoversion_md.md)]-specific methods:  
  
|Method|For more information, see|  
|------------|-------------------------------|  
|public void setDateTimeOffset(int, microsoft.sql.DateTimeOffset)|[setDateTimeOffset](../../../connect/jdbc/reference/setdatetimeoffset-method-sqlserverpreparedstatement.md)|  
  
## See Also  
 [JDBC Driver API Reference](../../../connect/jdbc/reference/jdbc-driver-api-reference.md)  
  
  
