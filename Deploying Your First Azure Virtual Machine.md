# **Deploying Your First Azure Virtual Machine**

## **Introduction**

In this hands-on lab, we will use the Azure Portal to create and connect to an Azure virtual machine. We will log in to the Azure Portal and create a virtual machine. Then, we will connect to the virtual machine via RDP. Finally, we will use the Azure Portal to stop the virtual machine. After completing this lab, you will have gained the experience required to create and connect to your first Azure virtual machine.

## **Log into the Azure Portal**

* Log in to the Azure portal using the credentials provided on the lab page. Be sure to use an incognito or private browser window to ensure you're using the lab account rather than your own.
* Take note of the region for the lab-provided resource group.

## **Create a Virtual Machine**

* In the Azure Portal, navigate to the **Virtual machines** dashboard.
* Click the **+ Create a resource** button and click **virtual machine**.
* On the **Create a virtual machine** page, configure the following settings:
  * **Resource group:** Select the pre-provisioned group from the dropdown
    * **Virtual machine name:** _acg-firstdeploy_
    * **Region:** Select the same region as the lab-provided resource group
    * **Image:** **Windows Server 2016 Datacenter - Gen 2**
    * **Size:** Leave as the default size
    * **Username:** _acg-admin_
    * **Password:** _Admin123456!_
* Click **Next : Disks >**.
* Leave the default settings and click **Next : Networking >**.
* Click **Next : Management >**.
* Click **Next : Advanced >**.
* Click **Next : Tags >**.
* Click **Next : Review + create >**.
* Click **Create**.
* Click the notifications icon at the top of the page to monitor the deployment.
* When the deployment is complete, click **Go to resource**.

## **Connect to the Virtual Machine**

* At the top of the page, click the **Connect** dropdown and select **RDP**.
* Click **Download RDP File**.
* Run the file and when prompted, click **Connect**.
* Enter in the credentials for the virtual machine and click **Continue**.
* Click **Continue**.
* Wait a few minutes for the virtual machine connection to be established.

## **Stop and Delete the Virtual Machine**

* Using the Windows icon in the bottom-left corner of the page, click the **Account** icon and click **Sign Out**.
* Once you are signed out, return to the virtual machine **Overview** page in the Azure Portal, and click **Stop**.
* Click **Yes**.
* Refresh the page and verify the **Status** has changed to **Stopped (deallocated)**.
* Click on **Delete**.
* In the delete pop-up dialog, select the **OS disk**, **Network Interfaces**, and **Public IP addresses** resources.
* Check the box acknowledging you under the Virtual Machine and associated resources selected will be deleted, then click **Delete**.
* Refresh the page and verify the virtual machine has been successfully deleted.

## **Conclusion**

Congratulations, you've successfully completed this hands-on lab!
