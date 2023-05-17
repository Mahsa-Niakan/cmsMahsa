# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

In this solution, I chose Web App, since here we are just deploying a simple CMS tool and for now the amount of requests and ... is not that much. Consider it as a test project, which we want to deploy and make it work, We might later need to scale it up and simply we can switch to a premium web app plan or VM. Here we don't need to take care of infrastructure, maintanance and security stuff. 
Web app might be not always up, but in compare to our requirements, it's the most suitable choice for now.
Also it's lower in costs. based on the resources we need, we can choose a simple plan and avoid spending too much time and money for things which are not important for us for now and they can be easily handled by web app.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 


In case in feauture, the number of users will be increasing, or we need to have dedicated servers, installing some other customized softwares on OS, I might think of switching to a VM.