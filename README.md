#### [To be completed] Cloud Cost Optimization - Microsoft Azure <br/><br/>
* Cloud cost can skyrocket due to various reasons. Each service can have its own cost optimization techniques but in general below are some strategies which can be followed to reduce cost in Azure. <br/>
* There are three fundamental drivers of cost in Cloud which should be kept in mind while architecting solutions : compute, storage, and outbound data transfer. <br/>
* There are 3 types of Azure Cost Optimization Techniques : Resource-based, Usage-based and Pricing-based. <br/>
* Below are some key cost optimization strategies. (Each service can have its own optimization technique - for e.g. Azure AKS has some best practices to run workloads in lowest price point & is not covered here) <br/>
  * Start early with cost optimization : This includes Azure services, tools, and resources to organize and track cost and usage data, enhance control through consolidated billing and access permission, enable better planning through budgeting and forecasts, and further lower cost with resources and pricing optimizations. [7 ways to optimize costs in Azure](https://azure.microsoft.com/en-us/solutions/cost-optimization/#ways-to-optimize) <br/>
  * Choose right pricing model : Opt for reserved or spot instances <br/>
  * Implement processes to identify resource waste : For example find and delete unattached disks, idle load balancers. <br/>
  * [Refer Azure Advisor](https://azure.microsoft.com/en-us/products/advisor/#features) recommendations regularly and take actions if needed <br/>
  * Have Right size resources : For example to right size VM's start with four main metrics - CPU, memory, I/O and networking. <br/>
  * Have capacity planning : use autoscaling of resources to avoid overspend <br/>
  * Limit data transfer fees : for e.g. use private endpoints. Ensure that systems that swap a lot of data are together in same cloud/region. Start with an assessment of cloud provider's transfer fees. Then, adjust cloud architecture to reduce the number of necessary data transfers. For example, move on-premises applications that frequently access cloud-hosted data into the cloud to eliminate hops.<br/>
  * Use Azure cost monitoring tools regularly : Azure Cost Management + Billing. This suite of tools tracks spending across individual Azure services, provides future bill forecasts and alerts users when they go over budget. <br/>
  * Prevent cloud sprawl <br/>
  * Cache storage strategically <br/>
  * Make use of storage tiering <br/>
  
  




#### Further References <br/>
* [Cloud cost-optimization simulator](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/cloud-cost-optimization-simulator#)<br/>
* [Mastering Cloud Cost Optimization: The Principles](https://www.ibm.com/cloud/blog/mastering-cloud-cost-optimization-the-principles)<br/>
* [8 ways to reduce cloud costs](https://www.techtarget.com/searchcloudcomputing/feature/5-ways-to-reduce-cloud-costs)<br/>
* [Optimize Azure costs](https://azure.microsoft.com/en-us/solutions/cost-optimization/#tools)<br/>
* [Cloud Cost Optimization: Four Steps to Success](https://www.bmc.com/blogs/cloud-cost-optimization/)<br/>
* [Cloust cost optimization best practices](https://spot.io/resources/cloud-cost/cloud-cost-optimization-15-ways-to-optimize-your-cloud/#eliminate)<br/>
* [Key principles - three fundamental drivers of cost with AWS](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/key-principles.html)<br/>
* [Optimise your Azure costs](https://azure.microsoft.com/en-in/solutions/cost-optimization/)<br/>
* [How to optimize your cloud investment with Cost Management](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)<br/>
* [AWS Cost Optimization](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.costOptimization.en.html)<br/>
* [Azure Cost Optimization Techniques](https://www.linkedin.com/pulse/azure-cost-optimization-techniques-dr-rabi-prasad-padhy?trk=pulse-article_more-articles_related-content-card)<br/>
* [Azure cost optimization: 8 ways to save when using Azure](https://www.nigelfrank.com/insights/8-ways-to-save-when-using-azure)<br/>
* [6 Azure cost optimization best practices](https://www.techtarget.com/searchcloudcomputing/tip/Implement-these-Azure-cost-optimization-best-practices)<br/>
* [Azure Cost Optimization: 12 Ways to Save on Azure](https://bluexp.netapp.com/blog/azure-cost-optimization-12-ways-to-save-on-azure-cvo-blg)<br/>
* [Azure Data Transfer Costs: Everything You Need To Know](https://cloudmonitor.ai/2021/08/azure-data-transfer-costs-everything-you-need-to-know/)<br/>
* [Overview of Data Transfer Costs for Common Architectures](https://aws.amazon.com/blogs/architecture/overview-of-data-transfer-costs-for-common-architectures/)<br/>
