Premium Storage Azure VM preconfigured for max storage performance
==================================================================

            

This script sample demonstrates how to utilize Azure PowerShell to deploy a Windows based virtual machine from the Azure image gallery and configure Premium Storage & Storage Spaces to get the highest storage performance currently available.


Script functionality:


  *  Checks to make sure you have the proper version of Azure PowerShell installed (greater than or equal to 0.8.16)

  *  Launches secure user interface to authenticate with an Azure account 
  *  Presents option to choose an Azure Subscription 
  *  Presents option to select an Azure datacenter for virtual machine to reside that currently hosts premium storage

  *  Automates building of unique Premium_LRS storage account for selected virtual machine 

  *  Automates username and password creation for virtual machine 
  *  Presents option to choose a VM DS-Series which permits higher I/O loads 
  *  Presents option to select from latest virtual machine images available in the Azure image gallery

  *  Presents selection for number ofone terabyte data disks based on selected virtual machine size ([See Azure storage pricing details](http://azure.microsoft.com/en-us/pricing/details/storage/) for more information.)


  *  Connects to the newly created VM and automates the creation and configuration of a Storage Space for
[maximum performance](http://social.technet.microsoft.com/wiki/contents/articles/15200.storage-spaces-designing-for-performance.aspx)

  *  Configures the number of columns that match number of attached data disks 

  *  Configures the Interleave and Allocation Unit Size 



Recommendations to follow:


[Set up monitoring for storage account throttling](http://blogs.msdn.com/b/wats/archive/2014/08/02/how-to-monitor-for-storage-account-throttling.aspx)
[Insure that that you follow best practices for SQL Server in Azure virtual machines](http://msdn.microsoft.com/en-us/library/azure/dn133149.aspx)


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
