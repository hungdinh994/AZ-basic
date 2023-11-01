# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Analyze:

Web App Service:
- Cost: The cheapest price to deploy is $0.013/hour(Sku D1).
- Availability: The App will be available 99.95% of the time.
- Scalability: Using built-in service(Autoscaling).
- Workflow: Something like an operating system, hardware is not required, so deployment will be fast.
Virtual Machine:
- Cost: The cheapest price to deploy is $0.0146/hour(Sku B1s).
- Availability: Available time is from 95% to 99.95%.
- Scalability: Using Virtual machine scale sets.
- Workflow: Deployment will be more complicated because it involes the operation system such as OS update.

Choice: I use Web App Service. As I can deverlop on app deployment without worrying about something such as hardware, upgrading OS. In addition, using Virtual Machine for deploying the project is more expensive than using Web app service. In the end, I chose this way because it is simpler and faster to implement.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
Details how the application and any other needs will have to change for you to change your mind in the final section. If this project requires something like OS, hardware, software installation or we want to manage our resources like CPU, memory, disk, VM is the best choice to deploy the project .