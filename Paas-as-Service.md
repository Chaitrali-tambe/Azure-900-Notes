::::::: Platform as a Service (PaaS) in Azure :::::::

																	      PaaS 
	Responsibility             |--	Information and data                    ◼        		 
	Always retained          --|    Devices (mobiles & PCs)                 ◼        
	by customer		           |	Accounts and Identities                 ◼       		    
					           |--	Identity and directory infrastructure   ◩       		   
	Responsibility             |	Applications                            ◩       		   
	varies by type           --|	Network Controls                        ◩       		   
					           |--	Operating System                        ☐       		    
	Responsibility transfers   |	Physical hosts                          ☐       		   
	to cloud providers		   |	Physical network                        ☐       
							   |--	Physical Datacenter                     ☐       


PaaS provides a framework for developers to build, test, and deploy applications without worrying about underlying infrastructure management.
▫ How it Works: Azure handles the OS, middleware, and runtime. You focus solely on developing and managing your application code and data.
▫ Azure Examples: Azure App Service, Azure SQL Database, Azure Functions, Azure Kubernetes Service (AKS).
▫ Pros: 
  ► Faster Development: Accelerates development cycles by removing infrastructure setup.
  ► Reduced Maintenance: Azure handles patching and OS updates.
  ► Cost-Effective: Pay only for resources consumed, reducing idle hardware costs.
▫ Cons:
  ► Limited Customization: Less control over the underlying infrastructure and configuration.
  ► Vendor Lock-in: Applications may be tied specifically to Azure services. 
  


