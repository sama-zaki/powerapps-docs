---
title: "msdyn_analysisresult Entity Reference (Common Data Service)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_analysisresult entity in Common Data Service."
ms.date: 11/07/2019
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
---
# msdyn_analysisresult Entity Reference



**Added by**: Power Apps Checker Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_analysisresults(*msdyn_analysisresultid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_analysisresults<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_analysisresults(*msdyn_analysisresultid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_analysisresults(*msdyn_analysisresultid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_analysisresults<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_analysisresults(*msdyn_analysisresultid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_analysisresults(*msdyn_analysisresultid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_analysisresults|
|DisplayCollectionName|Analysis Results|
|DisplayName|Analysis Result|
|EntitySetName|msdyn_analysisresults|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_analysisresults|
|LogicalName|msdyn_analysisresult|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_analysisresultid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_analysisresult|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_AnalysisComponentId](#BKMK_msdyn_AnalysisComponentId)
- [msdyn_AnalysisComponentType](#BKMK_msdyn_AnalysisComponentType)
- [msdyn_AnalysisJobId](#BKMK_msdyn_AnalysisJobId)
- [msdyn_analysisresultId](#BKMK_msdyn_analysisresultId)
- [msdyn_Category](#BKMK_msdyn_Category)
- [msdyn_ComponentType](#BKMK_msdyn_ComponentType)
- [msdyn_EntityName](#BKMK_msdyn_EntityName)
- [msdyn_FileUri](#BKMK_msdyn_FileUri)
- [msdyn_HasResolution](#BKMK_msdyn_HasResolution)
- [msdyn_helplink](#BKMK_msdyn_helplink)
- [msdyn_Level](#BKMK_msdyn_Level)
- [msdyn_Line](#BKMK_msdyn_Line)
- [msdyn_Member](#BKMK_msdyn_Member)
- [msdyn_Message](#BKMK_msdyn_Message)
- [msdyn_MessageArguments](#BKMK_msdyn_MessageArguments)
- [msdyn_MessageId](#BKMK_msdyn_MessageId)
- [msdyn_Module](#BKMK_msdyn_Module)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_ReturnStatus](#BKMK_msdyn_ReturnStatus)
- [msdyn_RuleId](#BKMK_msdyn_RuleId)
- [msdyn_RuleReferenceUri](#BKMK_msdyn_RuleReferenceUri)
- [msdyn_Severity](#BKMK_msdyn_Severity)
- [msdyn_Snippet](#BKMK_msdyn_Snippet)
- [msdyn_SolutionHealthMessage](#BKMK_msdyn_SolutionHealthMessage)
- [msdyn_Type](#BKMK_msdyn_Type)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_AnalysisComponentId"></a> msdyn_AnalysisComponentId

|Property|Value|
|--------|-----|
|Description|The associated Analysis Component that contains the issue described by the Analysis Result.|
|DisplayName|Analysis Component|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_analysiscomponentid|
|RequiredLevel|None|
|Targets|msdyn_analysiscomponent|
|Type|Lookup|


### <a name="BKMK_msdyn_AnalysisComponentType"></a> msdyn_AnalysisComponentType

|Property|Value|
|--------|-----|
|Description||
|DisplayName|AnalysisComponentType|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_analysiscomponenttype|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_AnalysisComponentType Options

|Value|Label|
|-----|-----|
|192350000|Organization Health|
|192350001|Component Health|



### <a name="BKMK_msdyn_AnalysisJobId"></a> msdyn_AnalysisJobId

|Property|Value|
|--------|-----|
|Description|The parent Analysis Job that produced the Analysis Result|
|DisplayName|Analysis Job|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_analysisjobid|
|RequiredLevel|None|
|Targets|msdyn_analysisjob|
|Type|Lookup|


### <a name="BKMK_msdyn_analysisresultId"></a> msdyn_analysisresultId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Analysis Result|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_analysisresultid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_Category"></a> msdyn_Category

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Category|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_category|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_Category Options

|Value|Label|
|-----|-----|
|192350000|Performance|
|192350001|Upgrade Readiness|
|192350002|Usage|
|192350003|Security|
|192350004|Design|
|192350005|Online Migration|
|192350006|Maintainability|
|192350007|Supportability|
|192350008|Accessibility|



### <a name="BKMK_msdyn_ComponentType"></a> msdyn_ComponentType

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Component Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_componenttype|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_ComponentType Options

|Value|Label|
|-----|-----|
|192350000|Web Resources|
|192350001|Plug-In|
|192350002|Configuration|



### <a name="BKMK_msdyn_EntityName"></a> msdyn_EntityName

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Entity Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_entityname|
|MaxLength|150|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_FileUri"></a> msdyn_FileUri

|Property|Value|
|--------|-----|
|Description||
|DisplayName|File Uri|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_fileuri|
|MaxLength|2000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_HasResolution"></a> msdyn_HasResolution

|Property|Value|
|--------|-----|
|Description||
|DisplayName|HasResolution|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_hasresolution|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_HasResolution Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_helplink"></a> msdyn_helplink

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Help Link|
|FormatName|Url|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_helplink|
|MaxLength|4000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Level"></a> msdyn_Level

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Level|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_level|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_Level Options

|Value|Label|
|-----|-----|
|192350000|Error|
|192350001|Warning|



### <a name="BKMK_msdyn_Line"></a> msdyn_Line

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Line|
|Format|None|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_line|
|MaxValue|2147483647|
|MinValue|0|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_Member"></a> msdyn_Member

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Member|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_member|
|MaxLength|1000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Message"></a> msdyn_Message

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Message|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_message|
|MaxLength|4000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_MessageArguments"></a> msdyn_MessageArguments

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Message Arguments|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_messagearguments|
|MaxLength|4000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_MessageId"></a> msdyn_MessageId

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Message Id|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_messageid|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Module"></a> msdyn_Module

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Module|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_module|
|MaxLength|1000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|--------|-----|
|Description|The name of the custom entity.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|200|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_ReturnStatus"></a> msdyn_ReturnStatus

|Property|Value|
|--------|-----|
|Description|The return status of a rule run: pass, fail, or configuration error|
|DisplayName|Return Status|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_returnstatus|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_ReturnStatus Options

|Value|Label|
|-----|-----|
|192350000|Pass|
|192350001|Fail|
|192350002|Config Error|
|192350003|Resolved|
|192350004|Warning|



### <a name="BKMK_msdyn_RuleId"></a> msdyn_RuleId

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Rule Id|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_ruleid|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_RuleReferenceUri"></a> msdyn_RuleReferenceUri

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Rule Reference Uri|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_rulereferenceuri|
|MaxLength|2000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Severity"></a> msdyn_Severity

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Severity|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_severity|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_Severity Options

|Value|Label|
|-----|-----|
|192350000|Low|
|192350001|Medium|
|192350002|High|
|192350003|Critical|



### <a name="BKMK_msdyn_Snippet"></a> msdyn_Snippet

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Snippet|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_snippet|
|MaxLength|4000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_SolutionHealthMessage"></a> msdyn_SolutionHealthMessage

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Message|
|Format|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_solutionhealthmessage|
|MaxLength|8000|
|RequiredLevel|None|
|Type|Memo|


### <a name="BKMK_msdyn_Type"></a> msdyn_Type

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Type|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_type|
|MaxLength|1000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|--------|-----|
|Description|Status of the Analysis Result|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### statecode Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Active|1|Active|
|1|Inactive|2|Inactive|



### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the Analysis Result|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### statuscode Options

|Value|Label|State|
|-----|-----|-----|
|1|Active|0|
|2|Inactive|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_AnalysisComponentIdName](#BKMK_msdyn_AnalysisComponentIdName)
- [msdyn_AnalysisJobIdName](#BKMK_msdyn_AnalysisJobIdName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_AnalysisComponentIdName"></a> msdyn_AnalysisComponentIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_analysiscomponentidname|
|MaxLength|200|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_AnalysisJobIdName"></a> msdyn_AnalysisJobIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_analysisjobidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
|DisplayName|Owning Business Unit|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the team that owns the record.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_analysisresult_SyncErrors](#BKMK_msdyn_analysisresult_SyncErrors)
- [msdyn_analysisresult_DuplicateMatchingRecord](#BKMK_msdyn_analysisresult_DuplicateMatchingRecord)
- [msdyn_analysisresult_DuplicateBaseRecord](#BKMK_msdyn_analysisresult_DuplicateBaseRecord)
- [msdyn_analysisresult_AsyncOperations](#BKMK_msdyn_analysisresult_AsyncOperations)
- [msdyn_analysisresult_MailboxTrackingFolders](#BKMK_msdyn_analysisresult_MailboxTrackingFolders)
- [msdyn_analysisresult_ProcessSession](#BKMK_msdyn_analysisresult_ProcessSession)
- [msdyn_analysisresult_BulkDeleteFailures](#BKMK_msdyn_analysisresult_BulkDeleteFailures)
- [msdyn_analysisresult_PrincipalObjectAttributeAccesses](#BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses)
- [msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult](#BKMK_msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult)


### <a name="BKMK_msdyn_analysisresult_SyncErrors"></a> msdyn_analysisresult_SyncErrors

**Added by**: System Solution Solution

Same as syncerror entity [msdyn_analysisresult_SyncErrors](syncerror.md#BKMK_msdyn_analysisresult_SyncErrors) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_DuplicateMatchingRecord"></a> msdyn_analysisresult_DuplicateMatchingRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_analysisresult_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_analysisresult_DuplicateMatchingRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|duplicaterecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_DuplicateMatchingRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_DuplicateBaseRecord"></a> msdyn_analysisresult_DuplicateBaseRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_analysisresult_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_analysisresult_DuplicateBaseRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|baserecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_DuplicateBaseRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_AsyncOperations"></a> msdyn_analysisresult_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [msdyn_analysisresult_AsyncOperations](asyncoperation.md#BKMK_msdyn_analysisresult_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_MailboxTrackingFolders"></a> msdyn_analysisresult_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [msdyn_analysisresult_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_analysisresult_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_ProcessSession"></a> msdyn_analysisresult_ProcessSession

**Added by**: System Solution Solution

Same as processsession entity [msdyn_analysisresult_ProcessSession](processsession.md#BKMK_msdyn_analysisresult_ProcessSession) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|processsession|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_ProcessSession|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_BulkDeleteFailures"></a> msdyn_analysisresult_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [msdyn_analysisresult_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_analysisresult_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses"></a> msdyn_analysisresult_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [msdyn_analysisresult_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_analysisresult_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult"></a> msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult

Same as msdyn_analysisresultdetail entity [msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult](msdyn_analysisresultdetail.md#BKMK_msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_analysisresultdetail|
|ReferencingAttribute|msdyn_analysisresult|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|msdyn_msdyn_analysisresult_msdyn_analysisresultdetail_AnalysisResult|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: RemoveLink<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_analysisresult_createdby](#BKMK_lk_msdyn_analysisresult_createdby)
- [lk_msdyn_analysisresult_createdonbehalfby](#BKMK_lk_msdyn_analysisresult_createdonbehalfby)
- [lk_msdyn_analysisresult_modifiedby](#BKMK_lk_msdyn_analysisresult_modifiedby)
- [lk_msdyn_analysisresult_modifiedonbehalfby](#BKMK_lk_msdyn_analysisresult_modifiedonbehalfby)
- [user_msdyn_analysisresult](#BKMK_user_msdyn_analysisresult)
- [team_msdyn_analysisresult](#BKMK_team_msdyn_analysisresult)
- [business_unit_msdyn_analysisresult](#BKMK_business_unit_msdyn_analysisresult)
- [msdyn_analysiscomponent_msdyn_analysisresult](#BKMK_msdyn_analysiscomponent_msdyn_analysisresult)
- [msdyn_analysisjob_msdyn_analysisresult](#BKMK_msdyn_analysisjob_msdyn_analysisresult)


### <a name="BKMK_lk_msdyn_analysisresult_createdby"></a> lk_msdyn_analysisresult_createdby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_analysisresult_createdby](systemuser.md#BKMK_lk_msdyn_analysisresult_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_analysisresult_createdonbehalfby"></a> lk_msdyn_analysisresult_createdonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_analysisresult_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_analysisresult_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_analysisresult_modifiedby"></a> lk_msdyn_analysisresult_modifiedby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_analysisresult_modifiedby](systemuser.md#BKMK_lk_msdyn_analysisresult_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_analysisresult_modifiedonbehalfby"></a> lk_msdyn_analysisresult_modifiedonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_analysisresult_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_analysisresult_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_analysisresult"></a> user_msdyn_analysisresult

**Added by**: System Solution Solution

See systemuser Entity [user_msdyn_analysisresult](systemuser.md#BKMK_user_msdyn_analysisresult) One-To-Many relationship.

### <a name="BKMK_team_msdyn_analysisresult"></a> team_msdyn_analysisresult

**Added by**: System Solution Solution

See team Entity [team_msdyn_analysisresult](team.md#BKMK_team_msdyn_analysisresult) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_analysisresult"></a> business_unit_msdyn_analysisresult

**Added by**: System Solution Solution

See businessunit Entity [business_unit_msdyn_analysisresult](businessunit.md#BKMK_business_unit_msdyn_analysisresult) One-To-Many relationship.

### <a name="BKMK_msdyn_analysiscomponent_msdyn_analysisresult"></a> msdyn_analysiscomponent_msdyn_analysisresult

See msdyn_analysiscomponent Entity [msdyn_analysiscomponent_msdyn_analysisresult](msdyn_analysiscomponent.md#BKMK_msdyn_analysiscomponent_msdyn_analysisresult) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisjob_msdyn_analysisresult"></a> msdyn_analysisjob_msdyn_analysisresult

See msdyn_analysisjob Entity [msdyn_analysisjob_msdyn_analysisresult](msdyn_analysisjob.md#BKMK_msdyn_analysisjob_msdyn_analysisresult) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_analysisresult?text=msdyn_analysisresult EntityType" />