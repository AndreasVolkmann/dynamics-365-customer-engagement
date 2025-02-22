---
title: "msdyn_quoteinvoicingproduct Entity Reference (Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_quoteinvoicingproduct entity."
ms.date: 04/02/2019

ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
search.audienceType: 
  - developer

---
# msdyn_quoteinvoicingproduct Entity Reference



**Added by**: Field Service Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts(*msdyn_quoteinvoicingproductid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts(*msdyn_quoteinvoicingproductid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts(*msdyn_quoteinvoicingproductid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts(*msdyn_quoteinvoicingproductid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_quoteinvoicingproducts(*msdyn_quoteinvoicingproductid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_quoteinvoicingproducts|
|DisplayCollectionName|Quote Invoicing Products|
|DisplayName|Quote Invoicing Product|
|EntitySetName|msdyn_quoteinvoicingproducts|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_quoteinvoicingproducts|
|LogicalName|msdyn_quoteinvoicingproduct|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_quoteinvoicingproductid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_quoteinvoicingproduct|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_InternalFlags](#BKMK_msdyn_InternalFlags)
- [msdyn_LineOrder](#BKMK_msdyn_LineOrder)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_Product](#BKMK_msdyn_Product)
- [msdyn_Quantity](#BKMK_msdyn_Quantity)
- [msdyn_quoteinvoicingproductId](#BKMK_msdyn_quoteinvoicingproductId)
- [msdyn_QuoteInvoicingSetup](#BKMK_msdyn_QuoteInvoicingSetup)
- [msdyn_Unit](#BKMK_msdyn_Unit)
- [msdyn_UnitPrice](#BKMK_msdyn_UnitPrice)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
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


### <a name="BKMK_msdyn_InternalFlags"></a> msdyn_InternalFlags

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Internal Flags|
|Format|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_internalflags|
|MaxLength|1048576|
|RequiredLevel|None|
|Type|Memo|


### <a name="BKMK_msdyn_LineOrder"></a> msdyn_LineOrder

|Property|Value|
|--------|-----|
|Description|Shows the order of this product within the quote invoicing setup.|
|DisplayName|Line Order|
|Format|None|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_lineorder|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


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


### <a name="BKMK_msdyn_Product"></a> msdyn_Product

|Property|Value|
|--------|-----|
|Description|The product associated with the transaction.|
|DisplayName|Product|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_product|
|RequiredLevel|ApplicationRequired|
|Targets|product|
|Type|Lookup|


### <a name="BKMK_msdyn_Quantity"></a> msdyn_Quantity

|Property|Value|
|--------|-----|
|Description|Enter the quantity to bill.|
|DisplayName|Quantity|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_quantity|
|MaxValue|100000000000|
|MinValue|0|
|Precision|2|
|RequiredLevel|ApplicationRequired|
|Type|Decimal|


### <a name="BKMK_msdyn_quoteinvoicingproductId"></a> msdyn_quoteinvoicingproductId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Quote Invoicing Produc|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_quoteinvoicingproductid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_QuoteInvoicingSetup"></a> msdyn_QuoteInvoicingSetup

|Property|Value|
|--------|-----|
|Description|The invoicing setup this product belongs to.|
|DisplayName|Quote Invoicing Setup|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_quoteinvoicingsetup|
|RequiredLevel|ApplicationRequired|
|Targets|msdyn_quoteinvoicingsetup|
|Type|Lookup|


### <a name="BKMK_msdyn_Unit"></a> msdyn_Unit

|Property|Value|
|--------|-----|
|Description|The unit that determines the pricing for this product|
|DisplayName|Unit|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_unit|
|RequiredLevel|ApplicationRequired|
|Targets|uom|
|Type|Lookup|


### <a name="BKMK_msdyn_UnitPrice"></a> msdyn_UnitPrice

|Property|Value|
|--------|-----|
|Description|Enter the amount you want to charge the customer per unit.|
|DisplayName|Unit Price|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_unitprice|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1|
|RequiredLevel|ApplicationRequired|
|Type|Money|


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
|Description|Status of the Quote Invoicing Produc|
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
|Description|Reason for the status of the Quote Invoicing Produc|
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


### <a name="BKMK_TransactionCurrencyId"></a> TransactionCurrencyId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the currency associated with the entity.|
|DisplayName|Currency|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|transactioncurrencyid|
|RequiredLevel|None|
|Targets|transactioncurrency|
|Type|Lookup|


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
- [ExchangeRate](#BKMK_ExchangeRate)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_Amount](#BKMK_msdyn_Amount)
- [msdyn_amount_Base](#BKMK_msdyn_amount_Base)
- [msdyn_ProductName](#BKMK_msdyn_ProductName)
- [msdyn_QuoteInvoicingSetupName](#BKMK_msdyn_QuoteInvoicingSetupName)
- [msdyn_UnitName](#BKMK_msdyn_UnitName)
- [msdyn_unitprice_Base](#BKMK_msdyn_unitprice_Base)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [TransactionCurrencyIdName](#BKMK_TransactionCurrencyIdName)
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


### <a name="BKMK_ExchangeRate"></a> ExchangeRate

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Exchange rate for the currency associated with the entity with respect to the base currency.|
|DisplayName|Exchange Rate|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|exchangerate|
|MaxValue|100000000000|
|MinValue|0.0000000001|
|Precision|10|
|RequiredLevel|None|
|Type|Decimal|


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


### <a name="BKMK_msdyn_Amount"></a> msdyn_Amount

|Property|Value|
|--------|-----|
|Description|Total sales amount for the product line.|
|DisplayName|Amount|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_amount|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_msdyn_amount_Base"></a> msdyn_amount_Base

|Property|Value|
|--------|-----|
|Description|Value of the Amount in base currency.|
|DisplayName|Amount (Base)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_amount_base|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_msdyn_ProductName"></a> msdyn_ProductName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_productname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_QuoteInvoicingSetupName"></a> msdyn_QuoteInvoicingSetupName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_quoteinvoicingsetupname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_UnitName"></a> msdyn_UnitName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_unitname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_unitprice_Base"></a> msdyn_unitprice_Base

|Property|Value|
|--------|-----|
|Description|Value of the Unit Price in base currency.|
|DisplayName|Unit Price (Base)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_unitprice_base|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


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


### <a name="BKMK_TransactionCurrencyIdName"></a> TransactionCurrencyIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|transactioncurrencyidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


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

- [msdyn_quoteinvoicingproduct_SyncErrors](#BKMK_msdyn_quoteinvoicingproduct_SyncErrors)
- [msdyn_quoteinvoicingproduct_DuplicateMatchingRecord](#BKMK_msdyn_quoteinvoicingproduct_DuplicateMatchingRecord)
- [msdyn_quoteinvoicingproduct_DuplicateBaseRecord](#BKMK_msdyn_quoteinvoicingproduct_DuplicateBaseRecord)
- [msdyn_quoteinvoicingproduct_AsyncOperations](#BKMK_msdyn_quoteinvoicingproduct_AsyncOperations)
- [msdyn_quoteinvoicingproduct_MailboxTrackingFolders](#BKMK_msdyn_quoteinvoicingproduct_MailboxTrackingFolders)
- [msdyn_quoteinvoicingproduct_ProcessSession](#BKMK_msdyn_quoteinvoicingproduct_ProcessSession)
- [msdyn_quoteinvoicingproduct_BulkDeleteFailures](#BKMK_msdyn_quoteinvoicingproduct_BulkDeleteFailures)
- [msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses](#BKMK_msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses)


### <a name="BKMK_msdyn_quoteinvoicingproduct_SyncErrors"></a> msdyn_quoteinvoicingproduct_SyncErrors

**Added by**: System Solution Solution

Same as syncerror entity [msdyn_quoteinvoicingproduct_SyncErrors](syncerror.md#BKMK_msdyn_quoteinvoicingproduct_SyncErrors) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_DuplicateMatchingRecord"></a> msdyn_quoteinvoicingproduct_DuplicateMatchingRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_quoteinvoicingproduct_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_quoteinvoicingproduct_DuplicateMatchingRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|duplicaterecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_DuplicateMatchingRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_DuplicateBaseRecord"></a> msdyn_quoteinvoicingproduct_DuplicateBaseRecord

**Added by**: System Solution Solution

Same as duplicaterecord entity [msdyn_quoteinvoicingproduct_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_quoteinvoicingproduct_DuplicateBaseRecord) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|baserecordid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_DuplicateBaseRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_AsyncOperations"></a> msdyn_quoteinvoicingproduct_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [msdyn_quoteinvoicingproduct_AsyncOperations](asyncoperation.md#BKMK_msdyn_quoteinvoicingproduct_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_MailboxTrackingFolders"></a> msdyn_quoteinvoicingproduct_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [msdyn_quoteinvoicingproduct_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_quoteinvoicingproduct_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_ProcessSession"></a> msdyn_quoteinvoicingproduct_ProcessSession

**Added by**: System Solution Solution

Same as processsession entity [msdyn_quoteinvoicingproduct_ProcessSession](processsession.md#BKMK_msdyn_quoteinvoicingproduct_ProcessSession) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|processsession|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_ProcessSession|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_BulkDeleteFailures"></a> msdyn_quoteinvoicingproduct_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [msdyn_quoteinvoicingproduct_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_quoteinvoicingproduct_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses"></a> msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_quoteinvoicingproduct_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_quoteinvoicingproduct_createdby](#BKMK_lk_msdyn_quoteinvoicingproduct_createdby)
- [lk_msdyn_quoteinvoicingproduct_createdonbehalfby](#BKMK_lk_msdyn_quoteinvoicingproduct_createdonbehalfby)
- [lk_msdyn_quoteinvoicingproduct_modifiedby](#BKMK_lk_msdyn_quoteinvoicingproduct_modifiedby)
- [lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby](#BKMK_lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby)
- [user_msdyn_quoteinvoicingproduct](#BKMK_user_msdyn_quoteinvoicingproduct)
- [team_msdyn_quoteinvoicingproduct](#BKMK_team_msdyn_quoteinvoicingproduct)
- [business_unit_msdyn_quoteinvoicingproduct](#BKMK_business_unit_msdyn_quoteinvoicingproduct)
- [TransactionCurrency_msdyn_quoteinvoicingproduct](#BKMK_TransactionCurrency_msdyn_quoteinvoicingproduct)
- [msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup](#BKMK_msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup)
- [msdyn_product_msdyn_quoteinvoicingproduct_Product](#BKMK_msdyn_product_msdyn_quoteinvoicingproduct_Product)
- [msdyn_uom_msdyn_quoteinvoicingproduct_Unit](#BKMK_msdyn_uom_msdyn_quoteinvoicingproduct_Unit)


### <a name="BKMK_lk_msdyn_quoteinvoicingproduct_createdby"></a> lk_msdyn_quoteinvoicingproduct_createdby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_quoteinvoicingproduct_createdby](systemuser.md#BKMK_lk_msdyn_quoteinvoicingproduct_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_quoteinvoicingproduct_createdonbehalfby"></a> lk_msdyn_quoteinvoicingproduct_createdonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_quoteinvoicingproduct_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_quoteinvoicingproduct_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_quoteinvoicingproduct_modifiedby"></a> lk_msdyn_quoteinvoicingproduct_modifiedby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_quoteinvoicingproduct_modifiedby](systemuser.md#BKMK_lk_msdyn_quoteinvoicingproduct_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby"></a> lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_quoteinvoicingproduct_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_quoteinvoicingproduct"></a> user_msdyn_quoteinvoicingproduct

**Added by**: System Solution Solution

See systemuser Entity [user_msdyn_quoteinvoicingproduct](systemuser.md#BKMK_user_msdyn_quoteinvoicingproduct) One-To-Many relationship.

### <a name="BKMK_team_msdyn_quoteinvoicingproduct"></a> team_msdyn_quoteinvoicingproduct

**Added by**: System Solution Solution

See team Entity [team_msdyn_quoteinvoicingproduct](team.md#BKMK_team_msdyn_quoteinvoicingproduct) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_quoteinvoicingproduct"></a> business_unit_msdyn_quoteinvoicingproduct

**Added by**: System Solution Solution

See businessunit Entity [business_unit_msdyn_quoteinvoicingproduct](businessunit.md#BKMK_business_unit_msdyn_quoteinvoicingproduct) One-To-Many relationship.

### <a name="BKMK_TransactionCurrency_msdyn_quoteinvoicingproduct"></a> TransactionCurrency_msdyn_quoteinvoicingproduct

**Added by**: System Solution Solution

See transactioncurrency Entity [TransactionCurrency_msdyn_quoteinvoicingproduct](transactioncurrency.md#BKMK_TransactionCurrency_msdyn_quoteinvoicingproduct) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup"></a> msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup

See msdyn_quoteinvoicingsetup Entity [msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup](msdyn_quoteinvoicingsetup.md#BKMK_msdyn_msdyn_quoteinvoicingsetup_msdyn_quoteinvoicingproduct_QuoteInvoicingSetup) One-To-Many relationship.

### <a name="BKMK_msdyn_product_msdyn_quoteinvoicingproduct_Product"></a> msdyn_product_msdyn_quoteinvoicingproduct_Product

**Added by**: Product Management Solution

See product Entity [msdyn_product_msdyn_quoteinvoicingproduct_Product](product.md#BKMK_msdyn_product_msdyn_quoteinvoicingproduct_Product) One-To-Many relationship.

### <a name="BKMK_msdyn_uom_msdyn_quoteinvoicingproduct_Unit"></a> msdyn_uom_msdyn_quoteinvoicingproduct_Unit

**Added by**: Product Management Solution

See uom Entity [msdyn_uom_msdyn_quoteinvoicingproduct_Unit](uom.md#BKMK_msdyn_uom_msdyn_quoteinvoicingproduct_Unit) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_quoteinvoicingproduct?text=msdyn_quoteinvoicingproduct EntityType" />

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]