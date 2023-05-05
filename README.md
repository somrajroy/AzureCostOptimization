#### Cloud Cost Optimization - Microsoft Azure <br/><br/>
* Cloud cost optimization is a combination of strategies, techniques, best practices, and tools that not only help reduce cloud costs but also maximize the business value of using the cloud. Optimizing cloud costs isn't just about reducing costs; it's also about aligning costs with business goals. 
* An increase in costs is not necessarily a problem if it's accompanied by an increase in revenue. One of the most important goals is to ensure that costs correlate with productive and profitable activities.<br/>
* Eventhough the benefits of using cloud services are numerous, the costs can quickly add up, especially for customers that are not actively managing their cloud spending. Microsoft recommends customers should take a proactive approach to managing cloud costs to significantly reduce their Cloud spending without sacrificing the performance and reliability of their services.<br/>
* Cloud cost optimization isn’t just about cutting costs & reducing cloud costs should never be an absolute goal. Rather focus should be on [reducing costs in relation to business outcomes](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/business-outcomes/). If a certain cloud spend brings a lot of business value then there is no point reducing costs there. This means there is more then just managing costs. By optimization of cloud costs customers optimize all aspects of their cloud computing to maximize business benefits. Some aspects are; performance of applications, speed of innovation, time-to-market, continuity, compliance and costs.<br/>
* There are three fundamental drivers of cost in Cloud which should be kept in mind while architecting solutions : compute, storage, and outbound data transfer. <br/>
* Additionally there are 3 types of Azure Cost Optimization Techniques : Resource-based, Usage-based and Pricing-based. <br/>
* [According to Microsoft Azure WAF(well architected framework)](https://learn.microsoft.com/en-us/azure/architecture/framework/#cost-optimization) - focus should be on [generating incremental business value early](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/innovate/business-value?source=recommendations). This is an exhaustive list artcle and covers every aspect of cost optimization on MS Azure as on date. This will help customers in making smart investments in the right Azure services and tools and aligning cloud strategy with customers business goals. If done correctly, these cloud cost optimization techniques can help businesses leverage the full power of the cloud to drive innovation, growth, and success.<br/><br/>
  * Increase Linux Compute   : There’s no such thing as the perfect operating system, but many in the tech world would probably say that Linux comes close. With the ability to run on almost any machine, configured how client want it, and with a super-low TCO (just to name a few of its awesome attributes), a Linux based operating system should be go-to for the next time there is a challenge to tackle. This vital and popular OS will only continue to gain ground as cloud-native apps become more prevalent and companies look for new ways to build the future & create success.<br/>
  * Leverage Automation in Cloud : Apply Automation to optimize performance at the lowest cost & deliver business value at lowest price point. Automation enhances system productivity, improves performance, and reduces costs and Cloud is meant for automation.<br/>
  * Review Pricing and Billing Information : Azure provides billing details explaining the cost of cloud services. This information can be leveraged to identify high-cost areas and generate savings. Understanding cloud costs helps in informed decisions <br/>
  * Start early with cost optimization : This includes Azure services, tools, and resources to organize and track cost and usage data, enhance control through consolidated billing and access permission, enable better planning through budgeting and forecasts, and further lower cost with resources and pricing optimizations. [Microsoft recommended 7 ways to optimize costs in Azure is a good place to start.](https://azure.microsoft.com/en-us/solutions/cost-optimization/#ways-to-optimize) <br/>
  * Choose right pricing model (payment options) for the use case : Opt for reserved or spot instances. Flexibility is key for business <br/>
  * Set budgets : Cloud costs can be controlled by ensuring everyone knows the goals and budgets of each project. Setting a monthly budget to plan is a good step. It helps to measure cost vs output. <br/>
  * Embrace consumption model  & align with work cycles: Schedule suspension of workloads to ensure that when people aren’t using them, they also aren’t paying for them. Customers needs to be aware that they pay for what they provision. The gap between consumption and allocation is what causes the large and unexpected bills. <br/>
    * Implement processes to identify resource waste (or idle resources) & prevent cloud sprawl : A cloud cost optimization strategy helps identify unused and unattached resources and remove them to eliminate unnecessary expenses. Resources should be de-provisioned immediately when job finishes. For example [Delete unattached disks](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/find-unattached-disks), idle load balancers etc. Automation should be applied as that is what cloud is meant for <br/>
  * Tag Azure resources : Resource tagging is a cloud cost optimization strategy that involves assigning tags to Azure resources to organize them better and monitor them to subsequently optimize workloads once lay of the land is understood/stable. A good resource tagging policy can save costs. For example, resources with non-production tags can be de-provisioned or shut down in holidays or when not used. Tags helps to analyze and attribute expenditure. Tags makes it easier to accurately identify the usage and cost of systems, which then allows transparent attribution of IT costs to individual workload owners. This helps measure return on investment (ROI) and gives workload owners an opportunity to optimize their resources and reduce costs. Tagging resources increases the amount of data monitoring tools can obtain.<br/>
  * [Refer Azure Advisor](https://azure.microsoft.com/en-us/products/advisor/#features) recommendations regularly and take actions if needed. [Azure Advisor helps in reducing cost & increasing operational excellence.](https://learn.microsoft.com/en-us/azure/advisor/advisor-overview)  <br/>
  * Right size services/resources : Every application’s and workload’s needs are unique— and these requirements evolve over time. Hence it is very important to measure efficiency and optimize over time. [For example to right size VM's start with four main metrics](https://learn.microsoft.com/en-us/azure/advisor/advisor-cost-recommendations) - CPU, memory, I/O and networking. [Azure cost optimization & Right Sizing Full list](https://learn.microsoft.com/en-us/azure/advisor/advisor-reference-cost-recommendations)<br/>
  * Have capacity planning : use autoscaling of resources to avoid overspend <br/>
  * Limit data transfer fees : [These charges are labelled as Bandwith pricing](https://azure.microsoft.com/en-in/pricing/details/bandwidth/). Private endpoints can be very useful. Limiting egress through Private IPs can be a good strategy to reduce egress charges. It is recommended to reduce the number of Public IPs in an architecture which is beneficial both from a cost as well as security perspective. Ensure that systems that swap a lot of data are together in same cloud/region. Start with an assessment of cloud provider's transfer fees. Then, adjust the cloud architecture to minimize the necessary data transfers. For example, move on-premises applications that frequently access cloud-hosted data into the cloud to eliminate hops. Data transfers from Azure services to Azure CDN are free of charge. Customers can consider Azure CDN for applications with higher outbound data transfer requirements, such as streaming services, for example. There can be some rule/metric in place, for example, no more than 15% of cloud expenditure should be spent on data transfer.<br/>
  * Azure Hybrid Benefit (AHB)/Bring-your-own-license (BYOL) : Azure Hybrid Benefit is a licensing benefit that helps to significantly reduce the costs of running workloads in Azure Cloud. Its an azure based program that providing BYOL to Azure and it available for Enterprise customers with Software Assurance that provides license mobility. It works by reuse on-premises Software Assurance-enabled Windows Server, RedHat, SUSE and SQL Server licenses on Azure. Azure Hybrid Benefit can lead to the highest level of savings on VMs i.e. up to 82% off pay-as-you-go pricing. <br/>
  * Use Azure cost monitoring tools regularly : Azure Cost Management + Billing. This suite of tools tracks spending across individual Azure services, provides future bill forecasts and alerts users when they go over budget. Cost Management is a free tool built into the Azure portal. It collects data and enables analysis that can help save costs on Azure services. Azure provides additional tools for cost planning and optimization, including the Azure Advisor, Cost Calculator, Cost Analysis, Azure Budgets, and Cloudyn, which lets track resource usage and expenditure for Azure alongside other clouds. <br/>
  * Azure cost analysis : Once workloads run in Azure, use the cost analysis feature in the Azure portal to understand how much each workload will cost. This tool also forecasts future spending based on current configurations.<br/>
  * [Leverage Azure Dev/Test Pricing](https://azure.microsoft.com/en-us/pricing/dev-test/) :  Azure provides deep discounts on services if they are used for development and testing: For example Run Windows and SQL Server VMs with no charge for Microsoft software (same price as Linux instances), Up to 55% discount on Azure SQL Database,Up to 50% discount on Logic Apps etc. <br/>
  * [Leverage B-series VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/sizes-b-series-burstable) : B-Series VMs grant discounts of between 15-55% compared to equivalent VMs. Identify if there are workloads that need to be available but only occasionally require high performance or throughput, and can be moved  to B-Series VMs. Azure offers B-Series virtual machines, designed for applications that are typically idle and then have sudden bursts of usage. A B-Series VM usually runs with a low, baseline level of CPU power, and as long as this low level is suitable for the workload, customers accumulate credits which can be utlized in "bursts".  <br/>
  * Make use of storage tiering : Storage can become very costly is not optimized properly. Azure Blob Storage model offers Premium, Hot, Cool, and Archive storage tiers with pricing to match, so customers can discover what’s right for them. Less frequent data can be archieved.<br/>
  * Base VMs stop/start schedule on your usage : it’s highly recommended to perform an analysis of usage patterns and availability so as to create a VM stop/start schedule that is optimal. This custom scheduling can be combined with autoscaling for better cost-effectiveness in the long run.  Azure Automation Runbooks gives the tools needed to implement automatic stop/start functions (can be very helpful for non-production enviornments). <br/>
  * (Choosing the right technology) Switching/rearchitect workloads to containers/microservices : Simple “lift and shift” to the cloud costs more than necessary, and when the dust settles, cloud cost optimization benefits become clear because minimizing overhead is a fundamental business process. Customers should check workload affinity and consider switching to containers/microservices. Hosting costs will immediately reduce. Containerazation of cloud estate can lead to a leaner Cloud environment with much lower cost.  <br/>
  * (Choosing the right technology) Serverless : This can save lot of costs. Serverless functions runs on demand, based on user-defined triggers. Serverless computing is best suited for compute-intensive workloads that run intermittently.<br/>
  * Avoid undifferentiated heavy lifting and leverage managed services : For example moving away from traditional databases to PaaS options (elastic databases). <br/>
  * Reduce licensing burden :  Software licensing is a major component of cloud operating costs. Manual license management is challenging, increasing the risk of paying for unused software licenses. Migrating to an open source equivalent product/software can save millions. <br/>
  * Choose the right region : Azure pricing often varies by regions -- with the North American regions typically being the cheapest -- so selecting a certain region could save money. If possible, move workloads to a less expensive region.(consider network latency and packet loss)<br/>
  * [Optimize networking cost with routing preference](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/routing-preference-overview) : This also applies to storage cost optimization. <br/>
  * Apply governance policies : Cloud sprawl tends to happen when customers lacks visibility into the spread of their cloud instances, services, or providers across the organization. Without governance policies, the self-service nature of the cloud leads to cloud sprawl. Defining and implementing governance policies will help maintain and gain control of unchecked cloud growth in customers cloud environment. <br/>
  * Establish review cadence : Cloud Cost Optimization should be a continuous process to measure and monitor overall efficiency of workloads. Keeping the cloud environment constantly optimized ensures that customers capitalize on the promise of the cloud — only pay for what they use — by constantly ensuring that applications are receiving exactly the resources they need to deliver on their SLAs, as cost-effectively as possible. One good approach would be to periodically perform Azure Well-Architected reviews & implement FinOps using Azure Well-Architected framework. The overall process can consist of - Review spend, Action findings, Monitor actions, Automate & Document. Establishing a review cadence will reduce costs monthly and will provide larger savings over a customers lifetime on Azure. <br/>
  
 #### Further References <br/>
* [The comprehensive WAF Cost Optimization documentation](https://learn.microsoft.com/en-us/azure/architecture/framework/cost/).<br/>
* [4 cloud cost optimization strategies with Microsoft Azure with E-Book](https://azure.microsoft.com/en-gb/blog/4-cloud-cost-optimization-strategies-with-microsoft-azure/)<br/>
* [Overview of Azure Cost optimization pillar & Principles](https://learn.microsoft.com/en-us/azure/architecture/framework/cost/overview)<br/>
* [Cloud cost-optimization simulator](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/cloud-cost-optimization-simulator#)<br/>
* [Mastering Cloud Cost Optimization: The Principles](https://www.ibm.com/cloud/blog/mastering-cloud-cost-optimization-the-principles)<br/>
* [Optimize Azure costs](https://azure.microsoft.com/en-us/solutions/cost-optimization/#tools)<br/>
* [How to optimize your cloud investment with Cost Management](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)<br/>
* [Azure Cost Optimization Techniques](https://www.linkedin.com/pulse/azure-cost-optimization-techniques-dr-rabi-prasad-padhy?trk=pulse-article_more-articles_related-content-card)<br/>
* [Azure Cost Optimisation - Azure Architecture Blog](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-cost-optimisation/ba-p/3624817)<br/>

