---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Compute
- platforms: java
---

# Getting Started with Compute - Manage Virtual Machine Async - in Java #


  Azure Compute sample for managing virtual machines -
   - Create a virtual machine with managed OS Disk based on Windows OS image
   - Once Network is created start creation of virtual machine based on Linux OS image in the same network
   - Update both virtual machines in parallel
     - for Linux based:
       - add Tag
     - for Windows based:
       - add a data disk
   - List virtual machines and print details
   - Delete all virtual machines.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-vm-async.git

    cd compute-java-manage-vm-async

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.