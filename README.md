Current Azure (ARM) subscription - PowerShell profile
=====================================================

            

For Azure Resource Manager usage only (classic version [here](https://gallery.technet.microsoft.com/scriptcenter/Current-Azure-subscription-bb76498a)). Use this script to customize your PowerShell profile. It will enable you to display what Azure subscription is currently selected when you start a new PowerShell session. It can save you the shame of having to explain why you deleted VMs from a production
 subscription because you thought you where still in that development subscription ;)


 


If you already have custom logic in your PowerShell profile, simply append the content of this script to it. If you don't have any PS profile yet, simply save & rename this file as:


%UserProfile%\My Documents\WindowsPowerShell\profile.ps1


 

Updates

2019-03-14 - **Added support for both Az & AzureRM cmdlets**


 

Output


PowerShell
Edit|Remove
powershell
VERBOSE: Using Azure PowerShell Az.Accounts v1.3.1
VERBOSE: Actually targeting Azure subscription: mycompany-dev - 53174c59-2689-4cf7-82c0-c9dcb4732bd9.

VERBOSE: Using Azure PowerShell Az.Accounts v1.3.1 
VERBOSE: Actually targeting Azure subscription: mycompany-dev - 53174c59-2689-4cf7-82c0-c9dcb4732bd9.




 


 

Requirements

Tested with Az.Accounts Version 1.x


Tested with AzureRM.Profile Version 5.x & 6.x


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
