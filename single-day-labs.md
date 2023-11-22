# Simplified labs

Here are some labs that do not require Visual Studio and C#.

## LAB 1: Examining the Azure Portal
1. Log in to the portal
2. Have a look around

## LAB 2: Storage account
1. Create a storage account
2. Create a blob container
3. Upload some files, including some images
4. View an uploaded image in a web browser using an URL

## LAB 3: Static web site
1. Install Visual Studio Code
2. Follow the instructions here:
   https://learn.microsoft.com/en-us/azure/static-web-apps/getting-started
   (Choose the No Framework tab unless you are feeling brave)
3. Make some changes to the index.html file and publish again
   (Try including an image hosted in your storage account)

## LAB 4: Creating a Web App on AppService
0. Create a fork of https://github.com/benc-uk/dotnet-demoapp on github
1. Log in to the portal
2. Go to App Services
3. Choose Create and the "Create Web App"
4. Use the following details:

   * Resource Group: Edument
   * Name: It's up to you, be creative!
   * Publish: Code
   * Runtime stack: .NET 8
   * OS: Linux
   * Region: West Europe
   * App Service Plan: Choose existing Edument
5. Create your app service
6. View it in the browser
7. Now setup continuous deployment from the github repo that you cloned above
