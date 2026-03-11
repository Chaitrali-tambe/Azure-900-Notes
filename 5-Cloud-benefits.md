High Availability (HA) - "Always On":
Simple Idea: Preventing downtime. If one part of your app breaks, another takes over.
Azure Tools:
▫ Availability Zones: Spreading apps across physically separate, data centers within a region.
▫ Fault Domains: Ensuring VMs are on different racks (power/network) to avoid simultaneous failure.
▫ Load Balancers: Spreading traffic across healthy servers. 

Scalability - "Always Just Right":
Simple Idea: Handling growth. Adding more power (scale up) or more servers (scale out) when busy.
Types:
▸ Vertical Scaling (Scale Up/Down): Increasing the size of a single instance, such as moving from 4GB RAM to 16GB RAM.
▸ Horizontal Scaling (Scale Out/In): Increasing or decreasing the number of instances (VMs), such as going from 2 servers to 5.
Azure Tools:
▫ Virtual Machine Scale Sets: Automatically adding/removing virtual machines based on demand.
▫ App Service Auto-scaling: Adjusting web app resources automatically. 

Reliability - "Keeping it Running":
Reliability in Azure means your applications stay running even if servers fail, using backups and global data centers to prevent downtime
▫ Azure Availability Zones: Physically separate datacenters within a region; if one fails, your apps failover to another.
▫ Azure Regions: Deploying across multiple geographical areas to ensure global availability.
▫ Azure Site Recovery: A disaster recovery service that keeps apps working during outages.
▫ Azure Chaos Studio: A tool to intentionally induce failures to test and improve application resilience.  

Predictability - "Knowing What Will Happen":
Predictability means you can forecast costs and performance, using tools to manage, monitor, and scale resources automatically, so you know exactly what to expect
▫ Azure Advisor: Provides recommendations to optimize resources for better performance and lower costs.
▫ Azure Cost Management + Billing: Tools to monitor, allocate, and forecast your cloud spend.
▫ Azure Virtual Machines (SKUs): Standardized, well-defined machine sizes that guarantee specific performance levels (CPU, memory, storage).
▫ Azure Load Balancer & Autoscale: Automatically distributes traffic and adjusts resources to maintain consistent performance, even during high traffic.

Security:
Security is about protecting data and resources from threats.
▫ Microsoft Entra ID (Formerly Azure Active Directory): The identity security guard.
  eg. Requires Multi-Factor Authentication (MFA) before allowing users to log in to the Azure Portal, stopping stolen passwords.
▫ Microsoft Defender for Cloud: A security monitor that gives you a "score" and tells you how to fix risks.
  eg. It scans your Virtual Machines (servers) and alerts you if they are not properly patched or are open to the public internet.
▫ Azure Firewall: A digital security guard at the perimeter of your network.
  eg. Blocks all incoming traffic from specific countries and only allows traffic from trusted IP addresses to reach your servers.
▫ Azure NSG (Network Security Group): A firewall for a single, specific resource (like a VM).
  eg. You create a rule to only allow port 443 (HTTPS) traffic into your web server and block everything else.

Governance:
Governance is about setting rules to ensure everyone follows company standards (e.g., only using certain regions to save costs or comply with laws).
▫ Azure Management Groups: Folders to organize multiple subscriptions.
  eg. Grouping all "Production" subscriptions under one Management Group, and all "Testing" under another, to apply different policies to each.
▫ Azure Role-Based Access Control (RBAC): A tool to assign permissions based on job roles (Least Privilege).
  eg. Giving a developer "Contributor" access to a specific project folder, but only "Reader" access to the production database.


