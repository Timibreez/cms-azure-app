# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Picking web App Service over VM, cause i'm tasked with deploying a small scale cms article app, which will not 
require high maintenance and will result in lower cost than in setting up a virtual machine. To also avoid security configurations for such a manageable app, I used the App service, considering the time frame for the project, using a web App service is faster and easier to implement to me. And in case of future up scaling, scaling will be much more easier.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I probably will scale up the application in no distant time, and have no idea what level of scaling I might commence, so I will prolly be required to have more control over deployment.
