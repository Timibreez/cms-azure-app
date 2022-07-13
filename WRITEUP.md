# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

#### App service
- Using an app service is relatively cheaper
- High Availability 
- High Infrastructure maintenance and scaling
- Continuous Deployment (CI / CD)
The major challenge here, is that there is little to no control over infrastructure.

#### Virtual Machine
There is an increased complexity in Virtual machines over Web app services, although
- High availability with an uptime of up to 99.5%
- Can be scaled to multiple Virtual machine instances
- Infrastructure can easily be manipulated, allowing complex controls

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

In the nearest future, I probably will scale up the application in no distant time, and have no idea what level of functionality the app will end up requiring. So I will prolly be required to have more control over deployment and Infrastructure generally. Therefore, I might have to change my decision, and use a Virtual Machine instead.
