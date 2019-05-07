# ![LOGO](logo.png) Azure Log Analytics **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Log Analytics API (version 2015-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/operationalinsights-OperationalInsights/2015-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:35+03:00

## API Description

Azure Log Analytics API reference

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available OperationalInsights Rest API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Gets the workspaces in a subscription.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets workspaces in a resource group.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a workspace instance.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name of the workspace.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a workspace instance.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name of the workspace.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name of the workspace.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name of the workspace.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the first page of data source instances in a workspace with the link to the next page.

*Tags:* `DataSources`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - The workspace that contains the data sources.
* `$filter` - _required_ - The filter to apply on the operation.
* `$skiptoken` - _optional_ - Starting point of the collection of data source instances.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a data source instance.

*Tags:* `DataSources`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that contains the datasource.
* `dataSourceName` - _required_ - Name of the datasource.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a datasource instance.

*Tags:* `DataSources`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that contains the datasource.
* `dataSourceName` - _required_ - Name of the datasource
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a data source.

*Tags:* `DataSources`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that will contain the datasource
* `dataSourceName` - _required_ - The name of the datasource resource.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Disables an intelligence pack for a given workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `intelligencePackName` - _required_ - The name of the intelligence pack to be disabled.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Enables an intelligence pack for a given workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `intelligencePackName` - _required_ - The name of the intelligence pack to be enabled.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the linked services instances in a workspace.

*Tags:* `LinkedServices`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that contains the linked services.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a linked service instance.

*Tags:* `LinkedServices`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that contains the linkedServices resource
* `linkedServiceName` - _required_ - Name of the linked service.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a linked service instance.

*Tags:* `LinkedServices`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that contains the linkedServices resource
* `linkedServiceName` - _required_ - Name of the linked service.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a linked service.

*Tags:* `LinkedServices`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace that will contain the linkedServices resource
* `linkedServiceName` - _required_ - Name of the linkedServices resource
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Gets a list of management groups connected to a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the shared keys for a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics Workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of usage metrics for a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-operationalinsights-operational-insights-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
