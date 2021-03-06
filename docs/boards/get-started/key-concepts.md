---
title: Key concepts and terminology for Azure Boards
titleSuffix: Azure Boards & TFS 
description: Key definitions for objects and items used to plan and track work by using Azure Boards
ms.custom: boards-get-started
ms.technology: devops-new-user 
ms.prod: devops
ms.assetid: 
ms.manager: douge
ms.author: kaelli
author: KathrynEE
ms.topic: reference
monikerRange: '>= tfs-2013'
ms.date: 09/05/2018  
---

# Key concepts and terms used for Azure Boards

[!INCLUDE [temp](../_shared/version-vsts-tfs-all-versions.md)]

Here are definitions of key concepts and artifacts used in Azure Boards. For more information, see also: 
- [Kanban key concepts](../boards/kanban-key-concepts.md)
- [Sprints and scrum key concepts](../sprints/scrum-key-concepts.md)
- [Work item field index](../work-items/guidance/work-item-field.md)
- [Project management and navigation glossary](../../project/navigation/glossary.md)  

## Agile methods
The goal of Agile engineering best processes is to rapidly deliver high-quality software. Agile uses a business approach that aligns development with customer needs and company goals. Frequent inspection and adaptation are necessary. Teamwork, self-organization, and accountability are critical to project success.  

## Agile tools
This suite of web-based tools is used to track work and support Agile methodologies. Agile tools support Scrum and Kanban, the core Agile methods that are used by software development teams today. To learn more, see [What is Azure Boards?](what-is-azure-boards.md).

[!INCLUDE [temp](../../_shared/glossary-terms/area-paths.md)] 

## Bug
A bug is a type of work item that records a potential source of dissatisfaction with the product. Bug is the common name of a work item type that's used to track code defects.  

[!INCLUDE [temp](../../_shared/glossary-terms/collections.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/dashboards.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/favorites.md)] 

## Field 
Fields are used to track a piece of information about the work to perform. Values you assign to a field are stored in the work-tracking data store. You can use the data store to query and generate charts to view status and trends. Your project contains 100 or more data fields. To update data, you [modify the data field within a work item](plan-track-work.md). Each work item is associated with a work item type (WIT). The data you can track corresponds to the fields assigned to the WIT. For a definition of each predefined field, see [Work item field index](../work-items/guidance/work-item-field.md). 

[!INCLUDE [temp](../../_shared/glossary-terms/follow.md)] 

## Inheritance process model 
The Inheritance process model is used to customize work-tracking objects and Agile tools for a project through the user interface. This process model is available only for accounts hosted on the Azure DevOps Services cloud platform. Projects inherit the customizations made to a process. To learn more, see [Inheritance process model](../../organizations/settings/work/inheritance-process-model.md).


[!INCLUDE [temp](../../_shared/glossary-terms/iterations.md)] 

## Kanban board 
A Kanban board is an interactive, electronic signboard that supports visualization of the flow of work from concept to completion and lean methods. To learn more, see [Kanban basics](../boards/kanban-quickstart.md).

 
## Link type
A link type specifies an object used to form link relationships between different WITs. To learn more, see [Link work items to support traceability and manage dependencies](../queries/link-work-items-support-traceability.md) and [LinkTypes elements reference](../../reference/xml/link-type-element-reference.md).  

## Pick list

A pick list specifies an enumerated set of values that appear within a drop-down menu in a work item form. Values also appear in the **Value** column within the query editor. The method you use to customize a pick list varies. It depends on the field and the process model. To learn more, see [Customize work](../../reference/customize-work.md). 

[!INCLUDE [temp](../../_shared/glossary-terms/plans.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/portfolio-backlog.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/process.md)]  

## Product backlog 
A product backlog is an interactive list of work items. It corresponds to a team's project plan or roadmap for what the team plans to deliver. You use a product backlog to prioritize work, forecast work by sprints, and quickly link work to portfolio backlog items. You can define your backlog items and then manage their status by using the Kanban board. 

Each product backlog can be customized by a team. To learn more, see [Create your backlog](../backlogs/create-your-backlog.md). 


[!INCLUDE [temp](../../_shared/glossary-terms/product-backlog.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/projects.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/queries.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/sprints.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/sprint-backlogs.md)]  

[!INCLUDE [temp](../../_shared/glossary-terms/taskboard.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/teams.md)] 

## User story
A user story is a type of work item that defines the applications, requirements, and elements that teams plan to create. Product owners typically define and stack rank user stories. A user story is defined with the Agile process. To learn more, see [Agile process work item types and workflow](../work-items/guidance/agile-process-workflow.md). 

[!INCLUDE [temp](../../_shared/glossary-terms/widgets.md)] 

[!INCLUDE [temp](../../_shared/glossary-terms/work-item-types.md)] 

## Workflow 

A workflow is an integral aspect of a work item. It's defined by its corresponding work item type. The workflow determines the logical progression and regression of work items. It tracks the status of work as the work progresses from a New or Active state to a Closed or Completed state. It also specifies the values that appear in the State and Reason drop-down menus. To learn more, see [Workflow states and state categories](../work-items/workflow-and-state-categories.md).

