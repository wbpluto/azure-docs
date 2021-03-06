---
title: Create your first Azure Function | Microsoft Docs
description: Build your first Azure Function, a serverless application, in less than two minutes.
services: functions
documentationcenter: na
author: ggailey777
manager: erikre
editor: ''
tags: ''

ms.assetid: 4a1669e7-233e-4ea2-9b83-b8624f2dbe59
ms.service: functions
ms.devlang: multiple
ms.topic: hero-article
ms.tgt_pltfrm: multiple
ms.workload: na
ms.date: 02/02/2016
ms.author: glenga

---
# Create your first Azure Function
## Overview
Azure Functions is an event-driven, compute-on-demand experience that extends the existing Azure application platform with capabilities to implement code triggered by events occurring in other Azure services, SaaS products, and on-premises systems. With Azure Functions, your applications scale based on demand and you pay only for the resources you consume. Azure Functions enables you to create scheduled or triggered units of code implemented in various programming languages. To learn more about Azure Functions, see the [Azure Functions Overview](functions-overview.md).

This topic shows you how to use the Azure Functions quickstart in the portal to create a simple "hello world"  JavaScript function that is invoked by an HTTP-trigger. You can also watch a short video to see how these steps are performed in the portal.

## Watch the video
The following video shows how to perform the basic steps in this tutorial. 

> [!VIDEO https://channel9.msdn.com/Series/Windows-Azure-Web-Sites-Tutorials/Create-your-first-Azure-Function-simple/player]
> 
> 

## Create a function from the quickstart
A function app hosts the execution of your functions in Azure. Follow these steps to create a function app with the new function. The function app is created with a default configuration. For an example of how to explicitly create your function app, see [the other Azure Functions quickstart tutorial](functions-create-first-azure-function-azure-portal.md).

Before you can create your first function, you need to have an active Azure account. If you don't already have an Azure account, [free accounts are available](https://azure.microsoft.com/free/).

1. Go to the [Azure Functions portal](https://functions.azure.com/signin) and sign-in with your Azure account.
2. Type a unique **Name** for your new function app or accept the generated one, select your preferred **Region**, then click **Create + get started**. Note that you must enter a valid name, which can contain only letters, numbers, and hyphens. Underscore (**_**) is not an allowed character.
3. In the **Quickstart** tab, click **WebHook + API** and **JavaScript**, then click **Create a function**. A new predefined JavaScript function is created. 
   
    ![](./media/functions-create-first-azure-function/function-app-quickstart-node-webhook.png)
4. (Optional) At this point in the quickstart, you can choose to take a quick tour of Azure Functions features in the portal. After you have completed or skipped the tour, you can test your new function by using the HTTP trigger.

## Test the function
[!INCLUDE [Functions quickstart test](../../includes/functions-quickstart-test.md)]

## Next steps
[!INCLUDE [Functions quickstart next steps](../../includes/functions-quickstart-next-steps.md)]

[!INCLUDE [Getting Started Note](../../includes/functions-get-help.md)]

