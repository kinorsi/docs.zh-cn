---
title: "部署服务"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: article
ms.assetid: ac361bfb-017d-4da9-a2d7-fc0fb72d65bb
caps.latest.revision: "5"
author: dotnet-bot
ms.author: dotnetcontent
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: 6e32570b381d6cab4326a13246dfe053b5032589
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="deploying-services"></a>部署服务
本主题介绍如何将 [!INCLUDE[indigo1](../../../../includes/indigo1-md.md)] 应用程序部署到运行时环境。  
  
## <a name="choosing-the-hosting-environment-for-your-application"></a>为您的应用程序选择宿主环境  
 [!INCLUDE[indigo2](../../../../includes/indigo2-md.md)] 服务设计为在支持托管代码的任意 Windows 进程中运行。 要变为活动状态，服务必须承载于创建它并控制它的上下文和生存期的运行时环境中。 宿主选项包括在最简单的控制台应用程序内运行，也包括在服务器环境中运行。服务器环境包括 Windows 服务、Internet 信息服务 (IIS) 或由 Windows 激活服务 (WAS) 托管的辅助进程等等。 若要查看为不同的宿主选项你[!INCLUDE[indigo2](../../../../includes/indigo2-md.md)]应用程序，请参阅[托管服务](../../../../docs/framework/wcf/hosting-services.md)。  
  
## <a name="see-also"></a>请参阅  
 [承载](../../../../docs/framework/wcf/feature-details/hosting.md)  
 [托管服务](../../../../docs/framework/wcf/hosting-services.md)
