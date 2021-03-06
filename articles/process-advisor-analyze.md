---
title: Analyze processes | Microsoft Docs
description: How to use the analyze processes feature in process advisor.
services: ''
suite: flow
documentationcenter: na
author: nijemcevic 
manager: kvivek
editor: ''
tags: ''
ms.service: power-automate
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 12/09/2020
ms.author: tatn
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---
# Analyze processes

[!INCLUDE [cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

On the left-side navigation pane in Power Automate, select **Process advisor (preview)** > **Processes**, and then select your process to go to the **Details** screen. This is where you access most of your process management activities.

> [!NOTE]
> Before you can view analytics, your Power Platform administrator has to [enable the TDS endpoint setting](/power-platform/admin/settings-features) for your organization in the [Power Platform admin center](https://admin.powerplatform.microsoft.com/).

## Analyze feature

Some key things to do here are to view the status of the recordings, and analyze your process. The **Analyze** option in the command bar gets you started.

- After the process is analyzed, the process map and related analytics are available when you select **Analytics** in the command bar.
- The process status on the **Details** pane shows the status of the analysis and whether the process has been analyzed before.
- Analysis happens at the process level for all recordings that are ready to be analyzed.
- Pay attention to the recording status, which you can find under the **Status** column of the **Recordings** pane, only recordings with specific status will be considered for analysis.

Here's a short video on how to navigate the analyze feature: [Analyze feature](https://go.microsoft.com/fwlink/?linkid=2147426)

## Recording status

Each recording can have one of the following statuses:

- **In progress**: recording is in progress, but it is also possible that the recording has not yet started. Since recording happens in the desktop client, the web portal will not know about its status until it has been saved. It is also possible to see this status after recording has been saved since some processing is required after recording to make it ready to view.
- **Failed**: an error occurred during recording processing. Please create a new recording.
- **Not analyzed**: the recording has been processed, and is available to view and edit, but it has not been marked as ready to analyze.
- **Ready to analyze**: the recording has been marked as ready to analyze and will be considered the next time you analyze the process.
- **Analyzed**: the recording has been analyzed and is part of the analyzed output that can be viewed through the **Analytics** screen.

In addition, analyzed recordings may have one of the following icons next to it:

- ![Not ready](media/process-advisor-analyze/icon-not-ready.png "This recording is not ready") Indicates that even though the recording was analyzed, it has been marked not ready to analyze, and will not be included if the process is analyzed again.
- ![Modified](media/process-advisor-analyze/icon-modified.png "This recording has been modified") Indicates that the recording has been modified and may be out of sync with the previous analysis. Analyzing again will synchronize the recording with the analysis output and the process map.


[!INCLUDE[footer-include](includes/footer-banner.md)]