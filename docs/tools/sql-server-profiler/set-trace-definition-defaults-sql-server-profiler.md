---
title: "Set Trace Definition Defaults (SQL Server Profiler) | Microsoft Docs"
ms.custom: ""
ms.date: "03/14/2017"
ms.prod: "sql-non-specified"
ms.prod_service: "sql-non-specified"
ms.service: ""
ms.component: "sql-server-profiler"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "traces [SQL Server], defaults"
ms.assetid: ab9fc570-797d-411e-814f-1c46d2d5feae
caps.latest.revision: 23
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
ms.workload: "Inactive"
---
# Set Trace Definition Defaults (SQL Server Profiler)
[!INCLUDE[appliesto-ss-xxxx-xxxx-xxx-md](../../includes/appliesto-ss-xxxx-xxxx-xxx-md.md)]
  The trace definition default is the default trace template that is used for each provider or server. You can set default trace templates for [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] or for [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)].  
  
### To set trace definition defaults  
  
1.  On the **File** menu, select **Templates**, and then click **Edit Template.**  
  
2.  In the **Trace Template Properties** dialog box, on the **General**tab, select a server type from the **Select server type**list.  
  
3.  In the **Select template name**list, select the name of the template that you want to use as the trace definition default.  
  
4.  Select **Use as a default template for selected server type**.  
  
5.  If necessary, click the **Events Selection**tab to modify the template.  
  
6.  Click **Save**.  
  
## See Also  
 [SQL Server Profiler Templates](../../tools/sql-server-profiler/sql-server-profiler-templates.md)   
 [SQL Server Profiler](../../tools/sql-server-profiler/sql-server-profiler.md)  
  
  
