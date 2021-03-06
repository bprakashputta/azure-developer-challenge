# azure-developer-challenge

## Azure AppService

Azure app service is an HTTP-based service for hosting web-applications, 
REST APIs and mobile backends. You can develop the application in any of 
the modern web programming languages like Node.js, Java, .NET, Ruby, Python.

It has the following features to support development:-


**1. Auto scaling**

       Baked into Azure App Service is the ability to scale up/down or scale out/in. 
       Depending on the usage of the web app, you can scale your app up/down the 
       resources of the underlying machine that is hosting your web app.

**2. Continuous Integration and Deployment.**
        
        The Azure portal provides out-of-the-box continuous integration and deployment
        with Azure DevOps, GitHub, Bitbucket, FTP, or a local Git repository on your 
        development machine. 

**3. Deployment Slots**

        Using the Azure portal, or command-line tools, you can easily add deployment
        slots to an App Service web app. For instance, you can create a staging 
        deployment slot where you can push your code to test on Azure. Once you are 
        happy with your code, you can easily swap the staging deployment slot with
        the production slot. You do all this with a few simple mouse clicks in the 
        Azure portal.

**4. App Service on Linux**
    
        App service can host web apps natively on linux for supported application 
        stacks. It can also run custom linux containers. App service on linux 
        supports a number of language specific built-in images.

## Service plans

There are different types of plans for deploying apps to the Azure App Service.
Go to the Microsoft website to check out them.

## Deploy to App Service

### Automated Deployment
Automated deployment, or continuous integration is a process used to push out new
features and bug fixes in a fast and repetitive pattern with minimal impact on end
users.
Azure supports automated deployment directly from 


**1. Azure DevOps:-** 

    Here you can run and test your code, after successful testing push
    the production code to your Azure Web App.

**2. GitHub:-** 
    
    Azure supports automated deployment directly from GitHub. When you 
    connect your GitHub repository to Azure for automated deployment, 
    any changes you push to your production branch on GitHub will be 
    automatically deployed for you.

**3. BitBucket**

    With its similarities to GitHub, you can configure an automated 
    deployment with BitBucket.


### Manual Deployment