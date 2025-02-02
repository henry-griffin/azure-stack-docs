---
title: AksHci PowerShell module for AKS on Azure Stack HCI and Windows Server
description: Learn how to use the AksHci module commands to manage AKS on Azure Stack HCI and Windows Server 
author: sethmanheim
ms.topic: reference
ms.date: 04/15/2022
ms.author: sethm 
ms.lastreviewed: 04/15/2022
ms.reviewer: jeguan

---

# AksHci PowerShell Reference

Commands to interact with Azure Kubernetes Service on Azure Stack HCI and Windows Server.

## AksHci cmdlets

|    Cmdlet    |    Description        |
| ------- | ---------- |
| [Add-AksHciGmsaCredentialSpec](./add-akshcigmsacredentialspec.md) | Adds a credentials spec for gMSA deployments on a cluster. |
| [Add-AksHciNode](./add-akshcinode.md) | Adds a new physical node to a deployment. |
| [Disable-AksHciArcConnection](./disable-akshciarcconnection.md) | Disables the Arc connection on an AKS on Azure Stack HCI and Windows Server cluster.|
| [Disable-AksHciOfflineDownload](disable-akshciofflinedownload.md) | Disables offline downloading to get the AKS on Azure Stack HCI images. |
| [Disable-AksHciPreview](disable-akshcipreview.md) | Reverts AKS on Azure Stack HCI and Windows Server from a preview channel back to the stable channel. |
| [Get-AksHciAutoScalerProfile](./get-akshciautoscalerprofile.md) | Retrieves a list of available autoscaler configuration profiles in the system or a specific autoscaler configuration profile and its settings. |
| [Enable-AksHciArcConnection](./enable-akshciarcconnection.md) |  Enables the Arc connection for an AKS on Azure Stack HCI and Windows Server cluster. |
| [Enable-AksHciOfflineDownload](enable-akshciofflinedownload.md) | Enables offline downloading to get the AKS on Azure Stack HCI images.
| [Enable-AksHciPreview](enable-akshcipreview.md) | Updates AKS on Azure Stack HCI and Windows Server to a preview channel. |
| [Get-AksHciBillingStatus](./get-akshcibillingstatus.md) | Gets billing status for the Azure Kubernetes Service on Azure Stack HCI and Windows Server deployment. |
| [Get-AksHciCluster](./get-akshcicluster.md) | Lists deployed clusters including the Azure Kubernetes Service host. |
| [Get-AksHciClusterNetwork](./get-akshciclusternetwork.md) | Retrieves virtual network settings by name, cluster name, or a list of all virtual network settings in the system. |
| [Get-AksHciClusterUpdates](./get-akshciclusterupdates.md) | Gets the available upgrades for an Azure Kubernetes Service cluster. |
| [Get-AksHciConfig](./get-akshciconfig.md) | Lists the current configuration settings for the Azure Kubernetes Service host. |
| [Get-AksHciCredential](./get-akshcicredential.md) | Accesses your cluster using kubectl. |
| [Get-AksHciEventLog](./get-akshcieventlog.md) | Gets all the event logs from the AKS HCI PowerShell module. |
| [Get-AksHciKubernetesVersion](./get-akshcikubernetesversion.md) | Lists available version for creating managed Kubernetes cluster. |
| [Get-AksHciLogs](./get-akshcilogs.md) | Creates a zipped folder with logs from all your pods. |
| [Get-AksHciNodePool](./get-akshcinodepool.md) | Lists the node pools in a Kubernetes cluster. |
| [Get-AksHciProxySetting](./get-akshciproxysetting.md) | Retrieves a list or an individual proxy settings object. |
| [Get-AksHciRegistration](./get-akshciregistration.md) | Gets registration information for the Azure Kubernetes Service on Azure Stack HCI and Windows Server deployment. |
  [Get-AksHciRelease](get-akshcirelease.md) | Downloads the install and upgrade bits to a local share that was configured in [Enable-AksHciOfflineDownload](enable-akshciofflinedownload.md). |
| [Get-AksHciContainerStorage](./get-akshcistoragecontainer.md) | Gets the information of the specified storage container. |
| [Get-AksHciUpdates](./get-akshciupdates.md) | Lists available updates for Azure Kubernetes Service on Azure Stack HCI and Windows Server. |
| [Get-AksHciVersion](./get-akshciversion.md) | Gets the current version of Azure Kubernetes Service on Azure Stack HCI and Windows Server. |
| [Get-AksHciVmSize](./get-akshcivmsize.md) | Lists supported VM sizes. |
| [Initialize-AksHciNode](./initialize-akshcinode.md) | Runs checks on every physical node to see if all requirements are satisfied to install Azure Kubernetes Service on Azure Stack HCI and Windows Server. |
| [Install-AksHci](./install-akshci.md) | Installs the Azure Kubernetes Service on Azure Stack HCI and Windows Server agents/services and host. |
| [Install-AksHciAdAuth](./install-akshciadauth.md) | Installs Active Directory authentication. |
| [Install-AksHciCsiNfs](./install-akshcicsinfs.md) | Installs the CSI NFS plug-in to a cluster. |
| [Install-AksHciCsiSmb](./install-akshcicsismb.md) | Installs the CSI SMB plug-in to a cluster. |
| [Install-AksHciGmsaWebhook](./install-akshcigmsawebhook.md) | Installs gMSA webhook add-on to the cluster.  |
| [Install-AksHciMonitoring](./install-akshcimonitoring.md) | Installs Prometheus for monitoring in the Azure Kubernetes Service on Azure Stack HCI and Windows Server deployment. |
| [New-AksHciAutoScalerProfile](./new-akshciautoscalerprofile.md) | Creates a new autoscaler configuration profile for the node pool autoscaler. | 
| [New-AksHciCluster](./new-akshcicluster.md) | Creates a new managed Kubernetes cluster. |
| [New-AksHciClusterNetwork](./new-akshciclusternetwork.md) | Creates an object for a new virtual network. |
| [New-AksHciLoadBalancerSetting](./new-akshciloadbalancersetting.md) | Creates a load balancer object for the workload clusters. |
| [New-AksHciNetworkSetting](./new-akshcinetworksetting.md) | Creates an object for a new virtual network. |
| [New-AksHciNodePool](./new-akshcinodepool.md) | Creates a new node pool to an existing cluster. |
| [New-AksHciProxySetting](./new-akshciproxysetting.md) | Creates an object defining proxy server settings to pass into `Set-AksHciConfig`. |
| [New-AksHciStorageContainer](./new-akshcistoragecontainer.md) | Creates a new storage container.  |
| [Remove-AksHciAutoScalerProfile](./remove-akshciautoscalerprofile.md) | Removes an unused autoscaler configuration profile from the system.  |
| [Remove-AksHciCluster](./remove-akshcicluster.md) | Deletes a managed Kubernetes cluster. |
| [Remove-AksHciGmsaCredentialSpec](./remove-akshcigmsacredentialspec.md) | Deletes a credentials spec for gMSA deployments on a cluster. |
| [Remove-AksHciClusterNetwork](./remove-akshciclusternetwork.md) | Removes a cluster network object. |
| [Remove-AksHciCluster](./remove-akshcicluster.md) | Deletes a managed Kubernetes cluster. |
| [Remove-AksHciGmsaCredentialSpec](./remove-akshcigmsacredentialspec.md) | Deletes a credentials spec for gMSA deployments on a cluster. |
| [Remove-AksHciNode](./remove-akshcinode.md) | Removes a physical node from your deployment. |
| [Remove-AksHciNodePool](./remove-akshcinodepool.md) | Deletes a node pool from a cluster. |
| [Repair-AksHciCerts](./repair-akshcicerts.md) | Troubleshoots and fixes errors related to expired certificates for the AKS on Azure Stack HCI and Windows Server host. |
| [Repair-AksHciClusterCerts](./repair-akshciclustercerts.md) | Troubleshoots and fixes errors related to expired certificated for Kubernetes built-in components. |
| [Restart-AksHci](./restart-akshci.md) | Restarts Azure Kubernetes Service on Azure Stack HCI and Windows Server and removes all deployed Kubernetes clusters. |
| [Set-AksHciAutoScalerProfile](./set-akshciautoscalerprofile.md) | Configures individual settings of an autoscaler configuration profile.  |
| [Set-AksHciCluster](./set-akshcicluster.md) | Scales the number of control plane nodes or worker nodes in a cluster. |
| [Set-AksHciConfig](./set-akshciconfig.md) | Sets or updates the configurations settings for the Azure Kubernetes Service host. |
| [Set-AksHciNodePool](./set-akshcinodepool.md) | Scales a node pool within a Kubernetes cluster. |
| [Set-AksHciOffsiteConfig](set-akshcioffsiteconfig.md) | Sets the offsite configuration to get the AKS on HCI images with offline downloading at an offsite location. |
| [Set-AksHciRegistration](./set-akshciregistration.md) | Registers Azure Kubernetes Service on Azure Stack HCI and Windows Server with Azure. |
| [Sync-AksHciBilling](./sync-akshcibilling.md) | Manually triggers a billing records sync. |
| [Uninstall-AksHci](./uninstall-akshci.md) | Removes Azure Kubernetes Service on Azure Stack HCI and Windows Server. |
| [Uninstall-AksHciAdAuth](./uninstall-akshciadauth.md) | Removes Active Directory authentication. |
| [Uninstall-AksHciCsiNfs](./uninstall-akshcicsinfs.md) | Uninstalls CSI NFS Plugin in a cluster. |
| [Uninstall-AksHciCsiSmb](./uninstall-akshcicsismb.md) | Uninstalls the CSI SMB plug-in in a cluster. |
| [Uninstall-AksHciGmsaWebhook](./uninstall-akshcigmsawebhook.md) | Uninstalls the gMSA webhook add-on to the cluster. |
| [Uninstall-AksHciMonitoring](./uninstall-akshcimonitoring.md) | Removes Prometheus for monitoring from the Azure Kubernetes Service on Azure Stack HCI and Windows Server deployment. |
| [Update-AksHci](./update-akshci.md) | Updates the Azure Kubernetes Service host to the latest Kubernetes version. |
| [Update-AksHciCluster](./update-akshcicluster.md) | Update a managed Kubernetes cluster to a newer Kubernetes or OS version. |

## Next steps

For more information, about the [AKS on the Azure Stack HCI](../../index.yml).