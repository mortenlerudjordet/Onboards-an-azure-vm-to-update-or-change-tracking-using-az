# Onboards an azure vm to update or change tracking using az

This sample automation runbook onboards an Azure VM for either the Update or ChangeTracking (which includes Inventory) solution using the Az-module. It requires an existing Azure VM to already be onboarded to the solution as it uses this information to onboard the new VM to the same Log Analytics workspace and Automation Account. This Runbook needs to be run from the Automation account that you wish to connect the new VM to.

This is an update of the existing Enable-AutomationSolution.ps1 with multiple bug-fixes and updates to use new Az-module

Remebmer to read the description in Enable-AutomationSolutionAz.ps1 for how to use in Azure Automation account
