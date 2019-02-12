# Notes

* Create a AzureResourceGroup project. This will contain the ARM template which you will modify to setup the deployment steps.

* `login-azurermaccount` command will allow the powershell to be authenticated with azure

* `get-azurermsubscription` command will list all the azure subscriptions you have.

* `set-azurermcontext -SubscriptionName SUBSNAME` will set the powershell command prompt where you want to be

* `.\Deploy-AzureResourceGroup.ps1 -ResourceGroupName "CCHelloWorld" -ResourceGroupLocation "Australia Southeast"` command will create the required azure resource group in the cloud.

* In the template file you can right-click the "website" node and add a setting (`Application Setting for Web Apps` to be precise) to use the source control.