---
title: "如何：创作 Windows 窗体的控件"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-winforms
ms.tgt_pltfrm: 
ms.topic: article
helpviewer_keywords:
- controls [Windows Forms], creating
- UserControl class [Windows Forms], Windows Forms
- custom controls [Windows Forms], creating
ms.assetid: 7570e982-545b-4c3a-a7c7-55581d313400
caps.latest.revision: "14"
author: dotnet-bot
ms.author: dotnetcontent
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: e37714f2c317456935f7b8694a083468dfa43a72
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="how-to-author-controls-for-windows-forms"></a>如何：创作 Windows 窗体的控件
控件表示用户和程序之间的图形链接。 控件可以提供或处理数据、接受用户输入、响应事件或执行连接用户和应用程序的其他功能（任意数量）。 因为控件本质上是具有图形界面的组件，所以它能提供组件所提供的所有功能并提供用户交互。 控件是针对特定目的而创建的，而创作控件只是另一种编程任务。 考虑到这一点，以下步骤概述了控件的创作过程。 链接提供有关各个步骤的附加信息。  
  
> [!NOTE]
>  如果想要创作在 Web 窗体上使用的自定义控件，请参阅[开发自定义 ASP.NET 服务器控件](http://msdn.microsoft.com/library/fbe26c16-cff4-4089-b3dd-877411f0c0ef)。  
>   
>  显示的对话框和菜单命令可能会与“帮助”中的描述不同，具体取决于你现用的设置或版本。 若要更改设置，请在 **“工具”** 菜单上选择 **“导入和导出设置”** 。 有关详细信息，请参阅 [在 Visual Studio 中自定义开发设置](http://msdn.microsoft.com/en-us/22c4debb-4e31-47a8-8f19-16f328d7dcd3)。  
  
### <a name="to-author-a-control"></a>创作控件  
  
1.  确定希望控件完成的操作或它在应用程序中所起的作用。 要考虑的因素有：  
  
    -   需要哪种图形界面？  
  
    -   此控件会处理哪些特定用户交互？  
  
    -   是否有现有控件提供所需功能？  
  
    -   通过组合几个 Windows 窗体控件可以获得所需功能吗？  
  
2.  如果控件需要一个对象模型，请确定如何在整个对象模型中分配功能，并在控件和任何子对象之间划分功能。 如果打算创作一个复杂的控件，或者想要并入一些功能，则对象模型可能会有用。  
  
3.  确定所需控件类型（例如，用户控件、自定义控件、继承的 Windows 窗体控件）。 有关详细信息，请参阅[控件类型建议](../../../../docs/framework/winforms/controls/control-type-recommendations.md)和[各种自定义控件](../../../../docs/framework/winforms/controls/varieties-of-custom-controls.md)。  
  
4.  将功能表示为控件及其子对象或子级结构的属性、方法和事件，并分配相应的访问级别（例如，公共、受保护等）。  
  
5.  如果需要为控件自定义绘制，请为其添加代码。 有关详细信息，请参阅[自定义控件的绘制和呈现](../../../../docs/framework/winforms/controls/custom-control-painting-and-rendering.md)。  
  
6.  如果你的控件继承自<xref:System.Windows.Forms.UserControl>，你可以通过生成控件项目并在运行测试其运行时行为**UserControl 测试容器**。 有关详细信息，请参阅[如何：测试 UserControl 的运行时行为](../../../../docs/framework/winforms/controls/how-to-test-the-run-time-behavior-of-a-usercontrol.md)。  
  
7.  还可以通过创建新项目（如 Windows 应用程序）并将其放入容器来测试和调试控件。 过程的演示包括在[演练：使用 Visual Basic 创作复合控件](../../../../docs/framework/winforms/controls/walkthrough-authoring-a-composite-control-with-visual-basic.md)中。  
  
8.  添加每个功能时，将功能添加到测试项目以执行新功能。  
  
9. 重复上述步骤，优化设计。  
  
10. 打包和部署控件。 有关详细信息，请参阅[部署应用程序、服务和组件](https://msdn.microsoft.com/library/wtzawcsz)。  
  
## <a name="see-also"></a>请参阅  
 [演练：使用 Visual Basic 创作复合控件](../../../../docs/framework/winforms/controls/walkthrough-authoring-a-composite-control-with-visual-basic.md)  
 [演练：使用 Visual Basic 从 Windows 窗体控件继承](../../../../docs/framework/winforms/controls/walkthrough-inheriting-from-a-windows-forms-control-with-visual-basic.md)  
 [如何：从 UserControl 类继承](../../../../docs/framework/winforms/controls/how-to-inherit-from-the-usercontrol-class.md)  
 [如何：从 Control 类继承](../../../../docs/framework/winforms/controls/how-to-inherit-from-the-control-class.md)  
 [如何：从现有 Windows 窗体控件继承](../../../../docs/framework/winforms/controls/how-to-inherit-from-existing-windows-forms-controls.md)  
 [如何：测试 UserControl 的运行时行为](../../../../docs/framework/winforms/controls/how-to-test-the-run-time-behavior-of-a-usercontrol.md)  
 [各种自定义控件](../../../../docs/framework/winforms/controls/varieties-of-custom-controls.md)
