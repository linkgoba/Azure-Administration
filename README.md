# Onboard Automator (Manage Azure identities and governance)

## Azure AD Setup:
Set up a new Azure AD instance (if not already present) using the Azure portal.
![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/078f1b27-d1d7-4f2a-a53e-e938e7ce1323)

## Logic App Workflow Design:
Design a Logic App workflow triggered by an event (New flat file uploaded to OneDrive) indicating a new employee hire.


## Azure AD User Creation:
Use the Azure AD connector in Logic Apps to automatically create a new user in Azure AD based on the trigger event's details.

## Role and Group Assignment:
Assign predefined roles and groups to the new user based on the job position or department indicated in the trigger.

## Resource Provisioning:
Use the Azure Resource Manager connector in Logic Apps to provision any necessary Azure resources for the user (like VMs or specific permissions).

## Welcome Email:
Leverage the Email connector in Logic Apps to send a welcome email to the new hire with instructions and necessary access details.

## Monitoring and Review:
Monitor and review the onboarding process through Logic Apps runs history and Azure AD logs to ensure smooth operations.
