﻿#  resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

**TODO: Documentation is missing please add the `\[ODataDescription()\]` and/or `\[ODataLongDescription()\]` attributes.**
## Methods
|Method|Return Type|Description|
|---|---|---|
|[List deviceConfigurationDeviceStatuses](../api/intune_deviceconfig_deviceconfigurationdevicestatus_list.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|List properties and relationships of the [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) objects.|
|[Get deviceConfigurationDeviceStatus](../api/intune_deviceconfig_deviceconfigurationdevicestatus_get.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md)|Read properties and relationships of the [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) object.|
|[Create deviceConfigurationDeviceStatus](../api/intune_deviceconfig_deviceconfigurationdevicestatus_create.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md)|Create a new [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) object.|
|[Delete deviceConfigurationDeviceStatus](../api/intune_deviceconfig_deviceconfigurationdevicestatus_delete.md)|None|Deletes a [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md).|
|[Update deviceConfigurationDeviceStatus](../api/intune_deviceconfig_deviceconfigurationdevicestatus_update.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md)|Update the properties of a [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) object.|

## Properties
|Property|Type|Description|
|---|---|---|
|id|String|Key of the entity.|
|deviceDisplayName|String|Device name of the DevicePolicyStatus.|
|userName|String|The User Name that is being reported|
|deviceModel|String|The device model that is being reported|
|platform|Int32|Not yet documented|
|status|String|Compliance status of the policy report. Possible values are: `unknown`, `notApplicable`, `compliant`, `remediated`, `nonCompliant`, `error`, `conflict`.|
|lastReportedDateTime|DateTimeOffset|Last modified date time of the policy report.|
|userPrincipalName|String|UserPrincipalName.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceConfigurationDeviceStatus"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.deviceConfigurationDeviceStatus",
  "id": "String (identifier)",
  "deviceDisplayName": "String",
  "userName": "String",
  "deviceModel": "String",
  "platform": 1024,
  "status": "String",
  "lastReportedDateTime": "String (timestamp)",
  "userPrincipalName": "String"
}
```



