---
title: "msdyn_opportunitylinetransactionclassificatio Entity Reference (Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_opportunitylinetransactionclassificatio entity."
ms.date: 04/02/2019
ms.prod: d365ce-op
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
search.audienceType: 
  - developer

---
# msdyn_opportunitylinetransactionclassificatio Entity Reference

List of transaction classification heads, which are four broad cost categories of time, expense, material, and fee, that will be considered as costs when computing the profit of an opportunity line (Deprecated in v3.0)

**Added by**: Project Service Automation Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios(*msdyn_opportunitylinetransactionclassificatioid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios(*msdyn_opportunitylinetransactionclassificatioid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios(*msdyn_opportunitylinetransactionclassificatioid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios(*msdyn_opportunitylinetransactionclassificatioid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_opportunitylinetransactionclassificatios(*msdyn_opportunitylinetransactionclassificatioid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_opportunitylinetransactionclassificatios|
|DisplayCollectionName|Opportunity Line Transaction Classifications|
|DisplayName|Opportunity Line Transaction Classification (Deprecated)|
|EntitySetName|msdyn_opportunitylinetransactionclassificatios|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_opportunitylinetransactionclassificatios|
|LogicalName|msdyn_opportunitylinetransactionclassificatio|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_opportunitylinetransactionclassificatioid|
|PrimaryNameAttribute|msdyn_description|
|SchemaName|msdyn_opportunitylinetransactionclassificatio|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_BillingType](#BKMK_msdyn_BillingType)
- [msdyn_description](#BKMK_msdyn_description)
- [msdyn_Include](#BKMK_msdyn_Include)
- [msdyn_OpportunityLine](#BKMK_msdyn_OpportunityLine)
- [msdyn_opportunitylinetransactionclassificatioId](#BKMK_msdyn_opportunitylinetransactionclassificatioId)
- [msdyn_TransactionClassification](#BKMK_msdyn_TransactionClassification)
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


### <a name="BKMK_msdyn_BillingType"></a> msdyn_BillingType

|Property|Value|
|--------|-----|
|Description|Select whether the transaction classification identified on the opportunity line will be charged to the customer or not. Valid values are Chargeable, Non-chargeable and Complimentary.  |
|DisplayName|Billing Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_billingtype|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_BillingType Options

|Value|Label|
|-----|-----|
|192350000|Non Chargeable|
|192350001|Chargeable|
|192350002|Complimentary|
|192350003|Not Available|



### <a name="BKMK_msdyn_description"></a> msdyn_description

|Property|Value|
|--------|-----|
|Description|Type the name of the custom entity.|
|DisplayName|Description|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_description|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Include"></a> msdyn_Include

|Property|Value|
|--------|-----|
|Description|Select whether the transaction classification identified on the opportunity line will be used to map costs in the classification to the opportunity line to affect the gross margin calculation.|
|DisplayName|Map for Costs calculation?|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_include|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_Include Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: True



### <a name="BKMK_msdyn_OpportunityLine"></a> msdyn_OpportunityLine

|Property|Value|
|--------|-----|
|Description|Type the opportunity line that this transaction classification applies to.|
|DisplayName|Opportunity Line|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_opportunityline|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatioId"></a> msdyn_opportunitylinetransactionclassificatioId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Opportunity Line Transaction Classification|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_opportunitylinetransactionclassificatioid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_TransactionClassification"></a> msdyn_TransactionClassification

|Property|Value|
|--------|-----|
|Description|Select the transaction classifications that apply to the opportunity line. Select the transaction classifications are broadly 4 types: Select the time, Expense, Material and Fee|
|DisplayName|Transaction Classification|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_transactionclassification|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|

#### msdyn_TransactionClassification Options

|Value|Label|
|-----|-----|
|192350000|Time|
|192350001|Expense|
|192350002|Material|
|192350003|Milestone|
|192350004|Fee|
|690970000|Commission|
|690970001|Additional|
|690970002|Tax|



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
|Description|Status of the Opportunity Line Transaction Classification|
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
|Description|Reason for the status of the Opportunity Line Transaction Classification|
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

- [msdyn_opportunitylinetransactionclassificatio_SyncErrors](#BKMK_msdyn_opportunitylinetransactionclassificatio_SyncErrors)
- [msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord](#BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord)
- [msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord](#BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord)
- [msdyn_opportunitylinetransactionclassificatio_AsyncOperations](#BKMK_msdyn_opportunitylinetransactionclassificatio_AsyncOperations)
- [msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders](#BKMK_msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders)
- [msdyn_opportunitylinetransactionclassificatio_ProcessSession](#BKMK_msdyn_opportunitylinetransactionclassificatio_ProcessSession)
- [msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures](#BKMK_msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures)
- [msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses](#BKMK_msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses)
- [msdyn_opportunitylinetransactionclassificatio_Annotations](#BKMK_msdyn_opportunitylinetransactionclassificatio_Annotations)
- [msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass](#BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass)
- [msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass](#BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass)


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_SyncErrors"></a> msdyn_opportunitylinetransactionclassificatio_SyncErrors

**Added by**: System Solution Solution

Same as syncerror entity [msdyn_opportunitylinetransactionclassificatio_SyncErrors](syncerror.md#BKMK_msdyn_opportunitylinetransactionclassificatio_SyncErrors) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord"></a> msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|duplicaterecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_DuplicateMatchingRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord"></a> msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|baserecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_DuplicateBaseRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_AsyncOperations"></a> msdyn_opportunitylinetransactionclassificatio_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [msdyn_opportunitylinetransactionclassificatio_AsyncOperations](asyncoperation.md#BKMK_msdyn_opportunitylinetransactionclassificatio_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders"></a> msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_ProcessSession"></a> msdyn_opportunitylinetransactionclassificatio_ProcessSession

**Added by**: System Solution Solution

Same as processsession entity [msdyn_opportunitylinetransactionclassificatio_ProcessSession](processsession.md#BKMK_msdyn_opportunitylinetransactionclassificatio_ProcessSession) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|processsession|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_ProcessSession|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures"></a> msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses"></a> msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_Annotations"></a> msdyn_opportunitylinetransactionclassificatio_Annotations

**Added by**: System Solution Solution

Same as annotation entity [msdyn_opportunitylinetransactionclassificatio_Annotations](annotation.md#BKMK_msdyn_opportunitylinetransactionclassificatio_Annotations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|annotation|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_Annotations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass"></a> msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass

Same as msdyn_opportunitylineresourcecategory entity [msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass](msdyn_opportunitylineresourcecategory.md#BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_opportunitylineresourcecategory|
|ReferencingAttribute|msdyn_opportunitylinetransactionclassification|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_opportunitylineresourcecategory_OppLineTransClass|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|


### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass"></a> msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass

Same as msdyn_opportunitylinetransactioncategory entity [msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass](msdyn_opportunitylinetransactioncategory.md#BKMK_msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_opportunitylinetransactioncategory|
|ReferencingAttribute|msdyn_opportunitylinetransactionclassification|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_opportunitylinetransactionclassificatio_opportunitylinetransactioncategory_OppLineTransClass|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_opportunitylinetransactionclassificatio_createdby](#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdby)
- [lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby](#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby)
- [lk_msdyn_opportunitylinetransactionclassificatio_modifiedby](#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedby)
- [lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby](#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby)
- [user_msdyn_opportunitylinetransactionclassificatio](#BKMK_user_msdyn_opportunitylinetransactionclassificatio)
- [team_msdyn_opportunitylinetransactionclassificatio](#BKMK_team_msdyn_opportunitylinetransactionclassificatio)
- [business_unit_msdyn_opportunitylinetransactionclassificatio](#BKMK_business_unit_msdyn_opportunitylinetransactionclassificatio)


### <a name="BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdby"></a> lk_msdyn_opportunitylinetransactionclassificatio_createdby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_opportunitylinetransactionclassificatio_createdby](systemuser.md#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby"></a> lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedby"></a> lk_msdyn_opportunitylinetransactionclassificatio_modifiedby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_opportunitylinetransactionclassificatio_modifiedby](systemuser.md#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby"></a> lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_opportunitylinetransactionclassificatio_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_opportunitylinetransactionclassificatio"></a> user_msdyn_opportunitylinetransactionclassificatio

**Added by**: System Solution Solution

See systemuser Entity [user_msdyn_opportunitylinetransactionclassificatio](systemuser.md#BKMK_user_msdyn_opportunitylinetransactionclassificatio) One-To-Many relationship.

### <a name="BKMK_team_msdyn_opportunitylinetransactionclassificatio"></a> team_msdyn_opportunitylinetransactionclassificatio

**Added by**: System Solution Solution

See team Entity [team_msdyn_opportunitylinetransactionclassificatio](team.md#BKMK_team_msdyn_opportunitylinetransactionclassificatio) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_opportunitylinetransactionclassificatio"></a> business_unit_msdyn_opportunitylinetransactionclassificatio

**Added by**: System Solution Solution

See businessunit Entity [business_unit_msdyn_opportunitylinetransactionclassificatio](businessunit.md#BKMK_business_unit_msdyn_opportunitylinetransactionclassificatio) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_opportunitylinetransactionclassificatio?text=msdyn_opportunitylinetransactionclassificatio EntityType" />

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]