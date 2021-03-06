---
title: "Create your own messages (Microsoft Dataverse) | Microsoft Docs" # Intent and product brand in a unique string of 43-59 chars including spaces
description: "Microsoft Dataverse provides messages that can be called from the web services. You can create your own messages and call them from your apps." # 115-145 characters including spaces. This abstract displays in the search result.
ms.custom: ""
ms.date: 03/13/2021
ms.reviewer: "pehecke"
ms.service: powerapps
ms.topic: "article"
author: "JimDaly" # GitHub ID
ms.author: "jdaly" # MSFT alias of Microsoft employees only
manager: "ryjones" # MSFT alias of manager or PM counterpart
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
---
# Create your own messages

Microsoft Dataverse exposes APIs using *messages*. There are many messages available for you to use. Custom messages are typically used to add new domain specific functionality to combine multiple message requests into a single request. For example, in a support call center, you may want to combine the `Create`, `Assign`, and `Update` messages into a single new `Escalate` message.

There are now two ways to define custom messages:


|Custom message method  |Description  |
|---------|---------|
|Custom Process Action|Also known as simply *Custom Actions*, these have been part of Dataverse for many years. Custom Process Actions provide a no-code way to define a custom message using the Workflow designer. The logic in these workflows can also be extended with code by using custom workflow activities. More information: [Use Custom Process Actions with code](workflow-custom-actions.md)|
|Custom API| Extends the concept of custom actions to provide developers with capabilities not limited by the workflow designer. More information: [Create and use Custom APIs](custom-api.md)|

Many developers have been creating Custom Process Actions simply to create new messages without implementing any logic in the workflow. Instead, they register plug-ins for the message created by the custom action to implement all of their logic. The Custom API feature makes this pattern a first class capability for developers to extend Dataverse.

## Compare Custom Process Action and Custom API

The following table describes some of the different capabilities.


|Capability |Custom Process Action  |Custom API  |Description  |
|---------|---------|---------|---------|
|Declarative logic with workflow |Yes|No|Workflow Actions can have logic defined without writing code using the Classic Workflow designer. <br />Custom APIs require a plug-in written in .NET to implement logic that is applied on the server.|
|Require specific privilege|No|Yes|With Custom API you can designate that a user must have a specific privilege to call the message. If the user doesn’t have that privilege through their security roles or team membership, an error will be returned.|
|Define main operation logic with code|Yes|Yes|With Custom Process Actions the main operation processes the Workflow definition which may include custom workflow activities. The code in these custom workflow activities is processed in the main operation together with any other logic in the workflow.<br /><br />With Custom API the message creator simply associates their plug-in type with the Custom API to provide the main operation logic.|
|Block Extension by other plug-ins|No|Yes|All messages defined using Custom Process Actions are extensible. This means any 3rd party developer can apply additional logic in a plug-in registered on the `PreValidation`, `PreOperation`, or `PostOperation` stages of the message to change the behavior.<br /><br />If a 3rd party plug-in step is synchronous, it means that logic or errors in plug-ins that extend your message can cause the message defined by a Custom Process Action to fail. With a Custom API you can block this.|
|Make message private|No|Yes|When you create a message using a Custom Process Action, it is exposed publicly in the endpoint for anyone else to discover and use. If someone else takes a dependency on the message you created, their code will be broken if you remove, rename, or change the input or output parameter signature in the future.<br /><br />If you do not intend for your message to be used by anyone else, you can mark it as a private message. This will indicate that you do not support others using the message you create, and it will not be included in definitions of available functions or actions exposed by the Web API $metadata service definition. Classes for calling these messages will not be generated using code generation tools, but you will still be able to use it.|
|Localizable names and descriptions|No|Yes|While Custom Process Actions provide for a friendly name for the custom action and any input and output parameters it uses, these values are not localizable. With Custom API you can provide localizable names and descriptions. These localized strings can then be bound to controls that provide a UI to use the message.|
|Create OData Function|No|Yes| The Dataverse Web API is an OData web service. OData provides for two types of operations: *Actions* & *Functions*.<br /><ul><li>An **Action** is an operation that makes changes to data in the system. It is invoked using the Http POST method and parameters are passed in the body of the request.</li><li>A **Function** is an operation that makes no change to data, for example an operation that simply retrieves data. It is invoked using an Http GET method and the parameters are passed in the URL of the request</li></ul>Custom Process Actions are always Actions. Custom API provides the option to define custom Functions.<br />There is nothing to prevent you from defining all operations as Actions if you wish.  But some operations may be best expressed using a GET request available by defining a function. <br />**Note**: The Power Automate Common Data Service (current environment) connector only exposes Actions currently.|
|Create a global operation not bound to an entity|Yes|Yes|Both provide the ability to define a global message not bound to an entity.|
|Bind an operation to an entity|Yes|Yes|Both provide the ability to pass a reference to a specific entity record by binding it to an entity.|
|Bind an operation to an entity collection|No|Yes|Binding an operation to an entity collection allows for another way to define the signature for the Custom API. While this does not pass a collection of entities as an input parameter, is restricts the context of the operation to that type of entity collection. Use this when your operation works with a collection of a specific type of entities or your operation will return a collection of that type.|
|Compose or modify a custom API by editing a solution|No|Yes|ISVs who build and maintain products that work with the Power Platform apply ALM practices that involve solutions. The data within a solution is commonly checked into a source code repository and checked out by a developer applying changes.<br /><br />A Custom Process Action is defined by a XAML Windows Workflow Foundation document which is transported as part of a solution. However, creating new or editing existing workflow definitions outside of the workflow designer is not supported.<br /><br />Custom API definitions are solution aware components included in a solution through a set of folders and XML documents. These files and the file structure enable transport the API from one environment to another. Because these are plain text files, changes can be made to them, or new APIs can be defined by working with these files. This method of defining Custom APIs is supported. More information: [Create a Custom API with solution files](create-custom-api-solution.md).|
|Subject to 2 minute time limit|No|Yes|A plug-in that implements the main operation for a Custom API is subject to the 2 minute time limit to complete execution.<br /><br />A Custom Process Action is not technically limited to two minutes. If a step in the Workflow logic contains a custom workflow activity, *that part* will be limited to two minutes. But the entire workflow cannot run indefinitely. There are other limitations that will cause long-running Custom Process Actions to fail. More information: [Watch out for long running actions](workflow-custom-actions.md#watch-out-for-long-running-actions)|




## Next Steps

[Use Custom Process Actions with code](workflow-custom-actions.md)<br />
[Create and use Custom APIs](custom-api.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]