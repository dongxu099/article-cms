# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*

Costs: VM can be shut down whenever capable in order to cut costs, while app services have a more flexible plan.

Scalability: Both the VM and the App service can be scaled easily.

Avalability: VM usually has more availability than app service.

Workflow: VM requires more configurations and maintaenance. In addition, it's relatively easier to deploy applications to app services.


- *Choose the appropriate solution (VM or App Service) for deploying the app*

App Service.

- *Justify your choice*

Choosing app service to deploy this ariticle CMS allow me not to configure,maintain and optimize the underlying infrastructure. The app service also provides a number of deployment options that allow me to easily deploy and maintain the code, so I as the developer can focus more on the development and iteration of app itself.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

App services have a cap on the underlying infrastructure to be used. If there are too many app users log in the app frequently, then we need to change to the VM deployment solution.
