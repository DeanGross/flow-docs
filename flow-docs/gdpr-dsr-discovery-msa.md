---
title: Microsoft Flow GDPR Data Subject Discovery Requests for Microsoft Accounts (MSA) | Microsoft Docs
description: Learn how to use Microsoft Flow to respond to GPDR Data Subject Discovery Requests for Microsoft Accounts.  
services: ''
suite: flow
documentationcenter: na
author: KentWeareMSFT
manager: KFile
editor: ''
tags: ''

ms.service: flow
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 5/16/2018
ms.author: keweare

---
# Respond to GDPR Data Subject Discovery Requests 

The first step in responding to a DSR request is to find the personal data that’s the subject of the request.
Here’s a summary of the Microsoft Flow resources that contain personal data for a user who authenticates with their Microsoft Account (MSA).

|Resource|Purpose|
|-----|-----|
|Run history|Provides the history of each flow’s execution for the past 28 days. This data includes start time, end time, status, and all input/output information for each flow run. Learn more about [flow run history](https://flow.microsoft.com/blog/download-history-recurrence/).|
|Activity feed| Provides a recap of each flow’s activities, including run status, failures, and notifications.|
|Flows|The workflow logic for a [flow](https://docs.microsoft.com/flow/get-started-logic-flow).|
|Connections|Used by connectors and allow connectivity to APIs, systems, databases, and more. Learn more about [connections](add-manage-connections.md).|

