---
Description: As of Windows 7, cascading menus are created through the SubCommands registry entry, the ExtendedSubCommandsKey registry entry, or the IExplorerCommand interface.
title: Creating Static Cascading Menus
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Creating Static Cascading Menus

In Windows 7 and later, cascading menu implementation is supported through registry settings. Prior to Windows 7, the creation of cascading menus was possible only through the implementation of the [**IContextMenu**](https://msdn.microsoft.com/en-us/library/Bb776095(v=VS.85).aspx) interface. In Windows 7 and later, you should resort to Component Object Model (COM) code-based solutions only when the static methods are insufficient.

The following screen shot provides an example of a cascading menu.

![screen shot showing an example of a cascading menu](images/file-assoc/filecascademenu2ndex.png)

In Windows 7 and later, there are three ways to create cascading menus, which are described in the following sections.

-   [How to Create Cascading Menus with the SubCommands Registry Entry](how-to--create-cascading-menus-with-the-subcommands-registry-entry.md)
-   [How to Create Cascading Menus with the ExtendedSubCommandsKey Registry Entry](how-to-create-cascading-menus-with-the-extendedsubcommandskey-registry-entry.md)
-   [How to Create Cascading Menus with the IExplorerCommand Interface](how-to-create-cascading-menus-with-the-iexplorercommand-interface.md)

 

 


