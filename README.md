# Onboard Automator (Manage Azure identities and governance)

## Azure AD Setup:
Set up a new Azure AD instance (if not already present) using the Azure portal.
![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/078f1b27-d1d7-4f2a-a53e-e938e7ce1323)

## Logic App Workflow Design:
Design a Logic App workflow triggered by an event (New flat file uploaded to OneDrive) indicating a new employee hire.
1. Text file uploaded to OneDrive under Documents, initialised variable to capture content of file

   ![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/6d0c7e8d-3a3a-4cf8-894a-f4c350053076)

2. Input file captured and content split by line

   ![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/42b6679b-cf8a-463d-a4a4-a910b63d627f)

## Azure AD User Creation:
Use the Azure AD connector in Logic Apps to automatically create a new user in Azure AD based on the trigger event's details.

![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/454f1851-e4ea-41a5-8a1c-db70c1c28623)

## Upload file to OneDrive

![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/37e90edd-af76-4ea2-b6a0-64457f8340ff)

![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/2cba3674-f1c6-4e13-9755-86c9ff5802e3)


## Run Trigger on Logic Apps and check AD user on Entra ID

![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/4a002d3b-0b7d-4546-8f97-e80cf26a49d9)

![image](https://github.com/linkgoba/Azure-Administration/assets/129736461/16c68638-d8f0-46bc-b98e-30e1202cf751)





