---
title: TaskSettings.RestartCount property
description: For scripting, gets or sets the number of times that the Task Scheduler will attempt to restart the task.
ms.assetid: ec77a7bf-52d8-4f0f-ab47-f0555b666a70
keywords:
- RestartCount property Task Scheduler
- RestartCount property Task Scheduler , TaskSettings object
- TaskSettings object Task Scheduler , RestartCount property
topic_type:
- apiref
api_name:
- TaskSettings.RestartCount
api_location:
- taskschd.dll
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# TaskSettings.RestartCount property

For scripting, gets or sets the number of times that the Task Scheduler will attempt to restart the task.

This property is read/write.

## Syntax


```VB
TaskSettings.RestartCount As Integer
```



## Property value

The number of times that the Task Scheduler will attempt to restart the task.

## Remarks

When reading or writing XML for a task, this setting is specified in the [**Count**](taskschedulerschema-count-restarttype-element.md) element of the Task Scheduler schema.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                          |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                    |
| Type library<br/>             | <dl> <dt>Taskschd.tlb</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Taskschd.dll</dt> </dl> |



## See also

<dl> <dt>

[Task Scheduler](task-scheduler-start-page.md)
</dt> </dl>

 

 




