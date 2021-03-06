---
title: "如何：将现有的控件重新分配给不同的父控件"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-winforms
ms.tgt_pltfrm: 
ms.topic: article
helpviewer_keywords:
- container controls [Windows Forms], Windows Forms
- layout [Windows Forms], resizing
- layout [Windows Forms], child controls
ms.assetid: 5a5723ff-34e0-4b6f-a57b-be4ebe35cb34
caps.latest.revision: "7"
author: dotnet-bot
ms.author: dotnetcontent
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: 3186dcf3b1f56799709f1e1976a55288065352b6
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="how-to-reassign-existing-controls-to-a-different-parent"></a>如何：将现有的控件重新分配给不同的父控件
可以将你窗体中的控件分配到新容器控件。  
  
> [!NOTE]
>  显示的对话框和菜单命令可能会与“帮助”中的描述不同，具体取决于你现用的设置或版本。 若要更改设置，请在 **“工具”** 菜单上选择 **“导入和导出设置”** 。 有关详细信息，请参阅 [在 Visual Studio 中自定义开发设置](http://msdn.microsoft.com/en-us/22c4debb-4e31-47a8-8f19-16f328d7dcd3)。  
  
### <a name="to-reassign-existing-controls-to-a-different-parent"></a>若要将现有的控件重新分配给不同的父控件  
  
1.  将三个 <xref:System.Windows.Forms.Button> 控件从“工具箱”  拖到窗体上。  
  
     将其相邻放置，但不用对齐它们。  
  
2.  在“工具箱” 中，单击 <xref:System.Windows.Forms.FlowLayoutPanel> 控件图标。  
  
     请勿将该图标拖动到窗体上。  
  
3.  将鼠标指针移至靠近这 3 个 <xref:System.Windows.Forms.Button> 控件。  
  
     指针更改为十字线时就会附上 <xref:System.Windows.Forms.FlowLayoutPanel> 控件图标。  
  
4.  单击并按住鼠标按钮。  
  
5.  拖动鼠标指针以绘制 <xref:System.Windows.Forms.FlowLayoutPanel> 控件的轮廓。  
  
6.  在这三个 <xref:System.Windows.Forms.Button> 控件周围绘制轮廓。  
  
7.  释放鼠标按钮。  
  
     这三种 <xref:System.Windows.Forms.Button> 控件现在插入到 <xref:System.Windows.Forms.FlowLayoutPanel> 控件中。  
  
## <a name="see-also"></a>请参阅  
 <xref:System.Windows.Forms.FlowLayoutPanel>  
 <xref:System.Windows.Forms.TableLayoutPanel>  
 [在 Windows 窗体上排列控件](../../../../docs/framework/winforms/controls/arranging-controls-on-windows-forms.md)  
 [演练：使用 TableLayoutPanel 在 Windows 窗体上排列控件](../../../../docs/framework/winforms/controls/walkthrough-arranging-controls-on-windows-forms-using-a-tablelayoutpanel.md)  
 [演练：使用对齐线在 Windows 窗体上排列控件](../../../../docs/framework/winforms/controls/walkthrough-arranging-controls-on-windows-forms-using-snaplines.md)
