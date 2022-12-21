Requesting a Cloud Shell.Succeeded. 
Connecting terminal...

Welcome to Azure Cloud Shell

Type "az" to use Azure CLI
Type "help" to learn about Cloud Shell


MOTD: Install modules from PowerShell Gallery: Install-Module <module name>

VERBOSE: Authenticating to Azure ...
VERBOSE: Building your Azure drive ...
PS /home/cloud> az group list
[
  {
    "id": "/subscriptions/964df7ca-3ba4-48b6-a695-1ed9db5723f8/resourceGroups/72-40e161b5-accessing-and-using-the-azure-cloud-sh",
    "location": "centralus",
    "managedBy": null,
    "name": "72-40e161b5-accessing-and-using-the-azure-cloud-sh",
    "properties": {
      "provisioningState": "Succeeded"
    },
    "tags": null,
    "type": "Microsoft.Resources/resourceGroups"
  }
]
PS /home/cloud> az storage account list
[
  {
    "accessTier": "Hot",
    "allowBlobPublicAccess": false,
    "allowCrossTenantReplication": null,
    "allowSharedKeyAccess": null,
    "allowedCopyScope": null,
    "azureFilesIdentityBasedAuthentication": null,
    "blobRestoreStatus": null,
    "creationTime": "2022-12-21T15:21:32.087700+00:00",
    "customDomain": null,
    "defaultToOAuthAuthentication": null,
    "dnsEndpointType": null,
    "enableHttpsTrafficOnly": true,
    "enableNfsV3": null,
    "encryption": {
      "encryptionIdentity": null,
      "keySource": "Microsoft.Storage",
      "keyVaultProperties": null,
      "requireInfrastructureEncryption": null,
      "services": {
        "blob": {
          "enabled": true,
          "keyType": "Account",
          "lastEnabledTime": "2022-12-21T15:21:32.994165+00:00"
        },
        "file": {
          "enabled": true,
          "keyType": "Account",
          "lastEnabledTime": "2022-12-21T15:21:32.994165+00:00"
        },
        "queue": null,
        "table": null
      }
    },
    "extendedLocation": null,
    "failoverInProgress": null,
    "geoReplicationStats": null,
    "id": "/subscriptions/964df7ca-3ba4-48b6-a695-1ed9db5723f8/resourceGroups/72-40e161b5-accessing-and-using-the-azure-cloud-sh/providers/Microsoft.Storage/storageAccounts/cloudchaseddemoshelllab",
    "identity": null,
    "immutableStorageWithVersioning": null,
    "isHnsEnabled": null,
    "isLocalUserEnabled": null,
    "isSftpEnabled": null,
    "keyCreationTime": {
      "key1": "2022-12-21T15:21:32.150223+00:00",
      "key2": "2022-12-21T15:21:32.150223+00:00"
    },
    "keyPolicy": null,
    "kind": "StorageV2",
    "largeFileSharesState": null,
    "lastGeoFailoverTime": null,
    "location": "centralindia",
    "minimumTlsVersion": "TLS1_2",
    "name": "cloudchaseddemoshelllab",
    "networkRuleSet": {
      "bypass": "AzureServices",
      "defaultAction": "Allow",
      "ipRules": [],
      "resourceAccessRules": null,
      "virtualNetworkRules": []
    },
    "primaryEndpoints": {
      "blob": "https://cloudchaseddemoshelllab.blob.core.windows.net/",
      "dfs": "https://cloudchaseddemoshelllab.dfs.core.windows.net/",
      "file": "https://cloudchaseddemoshelllab.file.core.windows.net/",
      "internetEndpoints": null,
      "microsoftEndpoints": null,
      "queue": "https://cloudchaseddemoshelllab.queue.core.windows.net/",
      "table": "https://cloudchaseddemoshelllab.table.core.windows.net/",
      "web": "https://cloudchaseddemoshelllab.z29.web.core.windows.net/"
    },
    "primaryLocation": "centralindia",
    "privateEndpointConnections": [],
    "provisioningState": "Succeeded",
    "publicNetworkAccess": null,
    "resourceGroup": "72-40e161b5-accessing-and-using-the-azure-cloud-sh",
    "routingPreference": null,
    "sasPolicy": null,
    "secondaryEndpoints": null,
    "secondaryLocation": null,
    "sku": {
      "name": "Standard_LRS",
      "tier": "Standard"
    },
    "statusOfPrimary": "available",
    "statusOfSecondary": null,
    "storageAccountSkuConversionStatus": null,
    "tags": {
      "ms-resource-usage": "azure-cloud-shell"
    },
    "type": "Microsoft.Storage/storageAccounts"
  }
]
PS /home/cloud> az vm list             
[]
PS /home/cloud> az vm create '
>> --name LabVM '
the following arguments are required: --name/-n, --resource-group/-g

Examples from AI knowledge base:
az vm create --name MyVm --resource-group MyResourceGroup --image RedHat:RHEL:7-RAW:7.4.2018010506
Create a default RedHat VM with automatic SSH authentication using an image URN.

az vm create --name MyVm --resource-group rg1 --image debian --assign-identity /subscriptions/99999999-1bf0-4dda-aec3-cb9272f09590/resourcegroups/myRG/providers/Microsoft.ManagedIdentity/userAssignedIdentities/myID
Create a debian VM with a user assigned identity.

az group create --location westus --resource-group MyResourceGroup
Create a new resource group in the West US region.

https://docs.microsoft.com/en-US/cli/azure/vm#az_vm_create
Read more about the command in reference docs
PS /home/cloud> az vm create `
>> --name LabVM `
>> --resource-group 72-40e161b5-accessing-and-using-the-azure-cloud-sh `
>> --image UbunutLTS `
>> --admin-usernmae azureuser `
>> --generate-ssh-keys
unrecognized arguments: --admin-usernmae azureuser

Examples from AI knowledge base:
az vm create --name MyVm --resource-group MyResourceGroup --image RedHat:RHEL:7-RAW:7.4.2018010506
Create a default RedHat VM with automatic SSH authentication using an image URN.

az vm create --name MyVm --resource-group rg1 --image debian --assign-identity /subscriptions/99999999-1bf0-4dda-aec3-cb9272f09590/resourcegroups/myRG/providers/Microsoft.ManagedIdentity/userAssignedIdentities/myID
Create a debian VM with a user assigned identity.

az vm list
List all VMs.

https://docs.microsoft.com/en-US/cli/azure/vm#az_vm_create
Read more about the command in reference docs
PS /home/cloud> az vm create `
>> --name LabVM `
>> --resource-group 72-40e161b5-accessing-and-using-the-azure-cloud-sh `
>> --image UbunutLTS `
>> --admin-username azureuser `
>> --generate-ssh-keys
Invalid image "UbunutLTS". Use a valid image URN, custom image name, custom image id, VHD blob URI, or pick an image from ['CentOS', 'Debian', 'Flatcar', 'openSUSE-Leap', 'RHEL', 'SLES', 'UbuntuLTS', 'Win2022Datacenter', 'Win2022AzureEditionCore', 'Win2019Datacenter', 'Win2016Datacenter', 'Win2012R2Datacenter', 'Win2012Datacenter', 'Win2008R2SP1'].
See vm create -h for more information on specifying an image.
PS /home/cloud> az vm create `
>> --name LabVM `
>> --resource-group 72-40e161b5-accessing-and-using-the-azure-cloud-sh `
>> --image UbuntuLTS `
>> --admin-username azureuser `
>> --generate-ssh-keys
SSH key files '/home/cloud/.ssh/id_rsa' and '/home/cloud/.ssh/id_rsa.pub' have been generated under ~/.ssh to allow SSH access to the VM. If using machines without permanent storage, back up your keys to a safe location.
Starting Build 2023 event, "az vm/vmss create" command will deploy Trusted Launch VM by default. To know more about Trusted Launch, please visit https://docs.microsoft.com/en-us/azure/virtual-machines/trusted-launch
It is recommended to use parameter "--public-ip-sku Standard" to create new VM with Standard public IP. Please note that the default public IP used for VM creation will be changed from Basic to Standard in the future.
{
  "fqdns": "",
  "id": "/subscriptions/964df7ca-3ba4-48b6-a695-1ed9db5723f8/resourceGroups/72-40e161b5-accessing-and-using-the-azure-cloud-sh/providers/Microsoft.Compute/virtualMachines/LabVM",
  "location": "centralus",
  "macAddress": "00-0D-3A-9E-E2-AD",
  "powerState": "VM running",
  "privateIpAddress": "10.0.0.4",
  "publicIpAddress": "13.89.33.206",
  "resourceGroup": "72-40e161b5-accessing-and-using-the-azure-cloud-sh",
  "zones": ""
}
PS /home/cloud> Get-AzResource
Get-AzResource                             Get-AzResourceMoverMoveCollection          
Get-AzResourceGroup                        Get-AzResourceMoverMoveResource            
Get-AzResourceGroupDeployment              Get-AzResourceMoverRequiredForResources    
Get-AzResourceGroupDeploymentOperation     Get-AzResourceMoverUnresolvedDependency    
Get-AzResourceGroupDeploymentWhatIfResult  Get-AzResourceProvider                     
Get-AzResourceLock                         Get-AzResourceProviderAction               
Get-AzResourceManagementPrivateLink        
PS /home/cloud> Get-AzResourceGroup

ResourceGroupName : 72-40e161b5-accessing-and-using-the-azure-cloud-sh
Location          : centralus
ProvisioningState : Succeeded
Tags              : 
ResourceId        : /subscriptions/964df7ca-3ba4-48b6-a695-1ed9db5723f8/resourceGroups/72-40e161b5-acce
                    ssing-and-using-the-azure-cloud-sh


PS /home/cloud> Get-AzStoreageAccount
WARNING: Get-AzStoreageAccount is not found. The most similar Azure PowerShell commands are:
        Get-AzStorageAccount
        Set-AzStorageAccount
        Get-AzStorageAccountKey
WARNING: The intelligent recommendation feature is in preview. Help us improve it by sharing your experience: https://go.microsoft.com/fwlink/?linkid=2202436
Get-AzStoreageAccount: The term 'Get-AzStoreageAccount' is not recognized as a name of a cmdlet, function, script file, or executable program.
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
PS /home/cloud> Get-AzStorageAccount 

StorageAccountName      ResourceGroupName                                  PrimaryLocation SkuName
------------------      -----------------                                  --------------- -------     
cloudchaseddemoshelllab 72-40e161b5-accessing-and-using-the-azure-cloud-sh centralindia    Standard_LRS

PS /home/cloud> Get-AzVM            

ResourceGroupName                                   Name  Location          VmSize OsType        NIC Pr
                                                                                                     ov
                                                                                                     is
                                                                                                     io
                                                                                                     ni
                                                                                                     ng
                                                                                                     St
                                                                                                     at
                                                                                                      e
-----------------                                   ----  --------          ------ ------        --- --
72-40E161B5-ACCESSING-AND-USING-THE-AZURE-CLOUD-SH LabVM centralus Standard_DS1_v2  Linux LabVMVMNic …d

PS /home/cloud> Get-AzResource | ft

Name                                         ResourceGroupName                                  Resourc
                                                                                                eType
----                                         -----------------                                  -------
LabVM_disk1_11c55414d4384462bc21a4b95fb3b2f8 72-40E161B5-ACCESSING-AND-USING-THE-AZURE-CLOUD-SH Micros…
LabVM                                        72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…
LabVMVMNic                                   72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…
LabVMPublicIP                                72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…
LabVMVNET                                    72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…
LabVMNSG                                     72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…
cloudchaseddemoshelllab                      72-40e161b5-accessing-and-using-the-azure-cloud-sh Micros…

PS /home/cloud> Remove-AzVM 

cmdlet Remove-AzVM at command pipeline position 1
Supply values for the following parameters:
(Type !? for Help.)
Name: LabVM
ResourceGroupName: 72-40e161b5-accessing-and-using-the-azure-cloud-sh

Virtual machine removal operation
This cmdlet will remove the specified virtual machine. Do you want to continue?
[Y] Yes  [N] No  [S] Suspend  [?] Help (default is "Y"): Y

OperationId : fcb58a04-5e83-4f3a-9b42-cfacc6009bf1
Status      : Succeeded
StartTime   : 12/21/2022 3:53:30 PM
EndTime     : 12/21/2022 3:54:19 PM
Error       : 


PS /home/cloud> Get
