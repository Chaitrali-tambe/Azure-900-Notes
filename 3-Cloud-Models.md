                |---- Public Cloud (Azure)		
Cloud Models ---|---- Private Cloud (On-Prem/Azure Stack)
                |----	Hybrid Cloud (Azure Arc)
                |---- Community Cloud

► Public Cloud (Azure)		
  Infrastructure is owned and operated by a third-party provider (e.g., Microsoft) and shared across organizations (multi-tenant). 
  ▫ Pros: Cost-effective, no maintenance, high elasticity.
  ▫ Cons: Limited control, potential data security concerns.
  ▫ Example: A web application using Azure App Service and Azure SQL Database that scales automatically to handle traffic spikes without purchasing hardware.
   
► Private Cloud (On-Prem/Azure Stack)
  Cloud infrastructure used exclusively by a single organization, hosted on-premises or by a third party (single-tenant).
  ▫ Pros: Maximum security, customization, compliance.
  ▫ Cons: High cost (CapEx), high management effort.
  ▫ Example: A company using Azure Stack in their own data center to run legacy applications while maintaining, for regulatory reasons, strict control over the hardware.
  
► Hybrid Cloud (Azure Arc)
  A combination of public and private clouds, allowing data and applications to be shared between them. 
  ▫ Pros: Flexibility, "bursting" capability to handle spikes, cost-optimization.
  ▫ Cons: Complex to set up, security management for both environments.
  ▫ Azure Example: A retail company using an on-premises datacenter for sensitive transaction data (private), while using Azure Kubernetes Service (AKS) for their customer-facing website, using Azure Arc to manage both environments as one
  
► Community Cloud
  Infrastructure shared by several organizations with common concerns (e.g., compliance, security).
  ▫ Pros: Better security than public, cheaper than private, collaborative.
  ▫ Cons: Limited customization, shared responsibility.
  ▫ Example: A consortium of hospitals using a shared, compliant Azure environment for sharing medical imaging data.
